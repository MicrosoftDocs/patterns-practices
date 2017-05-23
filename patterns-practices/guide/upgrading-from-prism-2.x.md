---
TOCTitle: 'Upgrading from Prism 2.x'
Title: 'Upgrading from Prism 2.x'
ms:assetid: 'ed11a7d3-2244-479a-b72e-01a9eda86b3b'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430859(v=PandP.40)'
---

# Upgrading from Prism 2.x

From: [Prism 4.1 - Developer's Guide to Microsoft Prism Library for WPF and Silverlight](/patterns-practices/guide/index)

This topic describes how to upgrade a solution from version 2.x to version 4.0 of the Prism Library and the major changes that you should be aware of if you are considering upgrading to the 4.0 version. The following sections describe the major changes:

-   [Update Namespace and Assembly References](#_update_namespace_and)
-   [New Assemblies to Support MEF](#_new_assemblies_to)
-   [Bootstrapper API Changes](#_bootstrapper_api_changes)
-   [Regions API Changes](#_regions_api_changes)
-   [EventAggregator API Changes](#_eventaggregator_api_changes)

> [!NOTE]
> Because this version of Prism targets the .NET Framework 4.0 and Silverlight 4, it was named Prism 4.0 so it would be easy to remember. There is no version Prism 3.x.

## <a name="_update_namespace_and"></a>Update Namespace and Assembly References

The **Composite** namespace was changed into the **Prism** namespace. The **Composite.Presentation** namespace was removed and its classes were moved to the **Prism** namespace. The **Composite** and **Composite.Presentation** assemblies were collapsed into a single assembly named **Microsoft.Practices.Prism**. These changes were done to simplify deployment and adoption, and to facilitate alignment with the MVVM support in Prism 4.0. The following namespace prefix was changed across all assemblies:

-   **Microsoft.Practices.Composite** -&gt; **Microsoft.Practices.Prism**
-   **Microsoft.Practices.Composite.Presentation** -&gt; **Microsoft.Practices.Prism**

The assembly/namespace change also affects the Managed Extensibility Framework (MEF) and Unity Application Block (Unity) extensions.

In Extensible Application Markup Language (XAML), a new **XmlnsDefinition** of **http://www.codeplex.com/prism** was added. The existing **XmlnsDefinition** of **http://www.codeplex.com/CompositeWPF** was left to make the transition to Prism 4.0 easier, but only resolves the Region namespace, whereas the first one pulls in all the library namespaces. It is recommended to update all the XAML files to use the new **XmlnsDefinition**.

> [!NOTE]
> The Prism Library now includes the signed binaries to use in your solutions. They are located in the bin folder where you extracted Prism.

## <a name="_new_assemblies_to"></a>New Assemblies to Support MEF

With the addition of supporting the MEF, there were several changes to the Prism Library. You can now use MEF as the dependency injection container. This new functionality is delivered in new assemblies of the Prism Library: **Prism.MefExtensions** (Silverlight and Desktop versions). For more information about dependency injection containers and how to use MEF, see "Managing Dependencies Between Components" in the [Prism4.pdf](http://compositewpf.codeplex.com/releases/view/55580).

## <a name="_bootstrapper_api_changes"></a>Bootstrapper API Changes

With the addition of supporting MEF, there were several changes to the Prism Library's bootstrapper for both Desktop and Silverlight. These changes include the following:

-   A new **Bootstrapper** base class was added to the **Microsoft.Practices.Prism** namespace in the **Microsoft.Practices.Prism** assembly:
    -   The **UnityBootstrapper** class, in the **Microsoft.Practices.Prism.UnityExtensions** assembly, extends the new **Bootstrapper** base class.
    -   A new **MefBootstrapper** class in the new **Microsoft.Practices.Prism.MefExtensions** assembly, extends the new **Bootstrapper** base class.
-   To facilitate the addition of the **Bootstrapper** base class several properties and methods changed names for consistency:
    -   The **LoggerFacade** property was renamed to **Logger**.
    -   The **Logger** property is set in the **Run** method of the bootstrapper using the result of the **CreateLogger** method rather than the get property on the **Logger**.
    -   The **GetModuleCatalog** method in the **UnityBootstrapper** class is now called **CreateModuleCatalog**.
	```C#
		// This is the code from the Composite Application Library 2.x
		// to specify the modules that compose the application.
		protected override IModuleCatalog GetModuleCatalog()
		{
			return new ModuleCatalog()
				.AddModule(typeof (ModuleA), "ModuleB")
				.AddModule(typeof (ModuleB))
				;
		}

		// This is the migrated method for the Prism Library 4.0.
		protected override IModuleCatalog CreateModuleCatalog()
		{
			return new ModuleCatalog()
				.AddModule(typeof (ModuleA), "ModuleB")
				.AddModule(typeof (ModuleB))
				;
		}
	```
	> [!NOTE]
	> There is a new **ConfigureModuleCatalog** method in the **Bootstrapper** class, mentioned in the following bullet that can be used instead of this method.

	-   Several new methods were added to better separate creation of objects from configuration:
    -   The **ConfigureModuleCatalog** virtual method was added to allow modifying the catalog after creation.
	```C#
		// Using the ConfigureModuleCatalog method to populate
		// the module catalog.
		protected override void ConfigureModuleCatalog()
		{
			base.ConfigureModuleCatalog();
			ModuleCatalog moduleCatalog = (ModuleCatalog)this.ModuleCatalog;
			moduleCatalog.AddModule(typeof (ModuleA), "ModuleB")
						 .AddModule(typeof (ModuleB))
						 ;
		}
	```
    -   The **ConfigureServiceLocator** virtual method was added to allow overriding the configuration of the **ServiceLocator**.

For more information about the **Bootstrapper** classes, see "Initializing Prism Applications" in the [Prism4.pdf](http://compositewpf.codeplex.com/releases/view/55580).

## Module API Changes

The **IModuleCatalog** interface has changed to support the basic form of the **AddModule** method. This allows callers with only a reference to the interface, such as the **ModuleManager**, to add newly discovered modules at run time. There are several additional overloads of this method in the **ModuleCatalog** class. You will need to update any existing classes that implement this interface.

The **IModuleTypeLoader** and **IModuleManager** interfaces have changed to use the asynchronous events pattern for reporting module download and loaded events. The new events are **ModuleDownloadProgressChanged** and **LoadModuleCompleted**. You will need to update any existing classes that implement this interface.

## <a name="_regions_api_changes"></a>Regions API Changes

The **IRegion** interface has changed to support navigation features. You will need to update any existing classes that implement this interface.

The following are the new members, which are used for navigation:

-   The **NavigationService** service property. This delegates the core functionality of navigation in a region to the replaceable **IRegionNavigationService** interface.
-   The **SortComparison** property. This property is used to provide the comparison used to sort the views.
-   The **RequestNavigate** method. As the **IRegion** interface, implements the **INavigateAsync** interface, this member of that interface should be also implemented. This method initiates navigation to the target specified by the provided Uniform Resource Identifier (URI).

For more information about navigation and hints for how to implement these members, see "Composing the User Interface" in the [Prism4.pdf](http://compositewpf.codeplex.com/releases/view/55580).

The following code example shows the default implementation of these members.

```C#
    // These are the new required members of the Region interface
    // of the Prism Library 4.0.

    public IRegionNavigationService NavigationService
    {
        ...
    }

    public Comparison<object> SortComparison
    {
        ...
    }

    public void RequestNavigate(Uri target, Action<NavigationResult> navigationCallback)
    {
        ...
    }
```

## <a name="_eventaggregator_api_changes"></a>EventAggregator API Changes

The **IEventAggregator.GetEvent&lt;TEventBase&gt;** method adds the **new**() restriction on the **TEventBase** generic parameter. The **TEventBase** generic type parameter requires having a parameter-less constructor at run time; this change enforces that requirement at compile time now. This affects only those who have provided their own implementations of the **IEventAggregator** interface; for example, in mock classes. You can see this in the following code example.

```C#
    // This is the code from the Composite Application Library 2.x.
    public TEventType GetEvent<TEventType>() where TEventType : EventBase

    // This is the migrated code for the Prism Library 4.0.
    public TEventType GetEvent<TEventType>() where TEventType : EventBase, new()
```

## Commands API Changes

The **DelegateCommand** now checks for **Nullable&lt;T&gt;** or a reference type in the constructor. The constructor deliberately prevents the use of value types. Because **ICommand** takes an object, having a value type for **T** would cause unexpected behavior when **CanExecute(null)** is called during XAML initialization for command bindings. Using **default(T)** was not selected due to possible confusion in selecting the correct domain values when **ICommand** methods are invoked with null values. Instead, callers should support a value type by using a nullable value type and checking the **HasValue** property before using the **Value** property.
