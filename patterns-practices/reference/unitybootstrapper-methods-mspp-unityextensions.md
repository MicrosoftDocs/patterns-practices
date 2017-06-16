---
TOCTitle: UnityBootstrapper Methods
Title: 'UnityBootstrapper Methods (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.UnityExtensions.UnityBootstrapper'
ms:mtpsurl: 'unitybootstrapper-methods-mspp-unityextensions.md'
---


# UnityBootstrapper Methods

The [UnityBootstrapper](/patterns-practices/reference/unitybootstrapper-class-mspp-unityextensions) type exposes the following members.

## Methods

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureContainer](/patterns-practices/reference/unitybootstrapper-configurecontainer-method-mspp-unityextensions)</td>
<td><div class="summary">
Configures the IUnityContainer. May be overwritten in a derived class to add specific type mappings required by the application.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureDefaultRegionBehaviors](/patterns-practices/reference/bootstrapper-configuredefaultregionbehaviors-method-mspp)</td>
<td><div class="summary">
Configures the [IRegionBehaviorFactory](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions). This will be the list of default behaviors that will be added to a region.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureModuleCatalog](/patterns-practices/reference/bootstrapper-configuremodulecatalog-method-mspp)</td>
<td><div class="summary">
Configures the [IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity) used by Prism.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureRegionAdapterMappings](/patterns-practices/reference/bootstrapper-configureregionadaptermappings-method-mspp)</td>
<td><div class="summary">
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureServiceLocator](/patterns-practices/reference/unitybootstrapper-configureservicelocator-method-mspp-unityextensions)</td>
<td><div class="summary">
Configures the LocatorProvider for the ServiceLocator.
</div>
(Overrides [Bootstrapper.ConfigureServiceLocator()](/patterns-practices/reference/bootstrapper-configureservicelocator-method-mspp).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateContainer](/patterns-practices/reference/unitybootstrapper-createcontainer-method-mspp-unityextensions)</td>
<td><div class="summary">
Creates the IUnityContainer that will be used as the default container.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateLogger](/patterns-practices/reference/bootstrapper-createlogger-method-mspp)</td>
<td><div class="summary">
Create the [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) used by the bootstrapper.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateModuleCatalog](/patterns-practices/reference/bootstrapper-createmodulecatalog-method-mspp)</td>
<td><div class="summary">
Creates the [IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity) used by Prism.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateShell](/patterns-practices/reference/bootstrapper-createshell-method-mspp)</td>
<td><div class="summary">
Creates the shell or main window of the application.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InitializeModules](/patterns-practices/reference/unitybootstrapper-initializemodules-method-mspp-unityextensions)</td>
<td><div class="summary">
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog
</div>
(Overrides [Bootstrapper.InitializeModules()](/patterns-practices/reference/bootstrapper-initializemodules-method-mspp).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InitializeShell](/patterns-practices/reference/bootstrapper-initializeshell-method-mspp)</td>
<td><div class="summary">
Initializes the shell.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[RegisterFrameworkExceptionTypes](/patterns-practices/reference/unitybootstrapper-registerframeworkexceptiontypes-method-mspp-unityextensions)</td>
<td><div class="summary">
Registers in the IUnityContainer the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the Exceptions that are not considered root exceptions by the [ExceptionExtensions]/patterns-practices/reference/exceptionextensions-class-mspp).
</div>
(Overrides [Bootstrapper.RegisterFrameworkExceptionTypes()](/patterns-practices/reference/bootstrapper-registerframeworkexceptiontypes-method-mspp
).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[RegisterTypeIfMissing](/patterns-practices/reference/unitybootstrapper-registertypeifmissing-method-mspp-unityextensions))</td>
<td><div class="summary">
Registers a type in the container only if that type was not already registered.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Run()](/patterns-practices/reference/run-mthd)</td>
<td><div class="summary">
Runs the bootstrapper process.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Run(Boolean)](/patterns-practices/reference/unitybootstrapper-run-method-boolean-mspp-unityextensions)</td>
<td><div class="summary">
Run the bootstrapper process.
</div>
(Overrides [Bootstrapper.Run(Boolean)](/patterns-practices/reference/bootstrapper-run-method-boolean-mspp).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
</tbody>
</table>

## See Also

[UnityBootstrapper Class](/patterns-practices/reference/unitybootstrapper-class-mspp-unityextensions)  
[Microsoft.Practices.Prism.UnityExtensions Namespace](/patterns-practices/reference/mspp-unityextensions-namespace)  
