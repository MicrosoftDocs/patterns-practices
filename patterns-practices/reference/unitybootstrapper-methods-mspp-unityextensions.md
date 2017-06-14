---
TOCTitle: UnityBootstrapper Methods
Title: 'UnityBootstrapper Methods (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.UnityExtensions.UnityBootstrapper'
ms:mtpsurl: 'unitybootstrapper-methods-mspp-unityextensions.md'
---

# UnityBootstrapper Methods

The [UnityBootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper) type exposes the following members.

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
<td>[ConfigureContainer](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.configurecontainer)</td>
<td><div class="summary">
Configures the IUnityContainer. May be overwritten in a derived class to add specific type mappings required by the application.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureDefaultRegionBehaviors](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configuredefaultregionbehaviors)</td>
<td><div class="summary">
Configures the [IRegionBehaviorFactory](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorfactory). This will be the list of default behaviors that will be added to a region.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configuremodulecatalog)</td>
<td><div class="summary">
Configures the [IModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog) used by Prism.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureRegionAdapterMappings](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configureregionadaptermappings)</td>
<td><div class="summary">
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureServiceLocator](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.configureservicelocator)</td>
<td><div class="summary">
Configures the LocatorProvider for the ServiceLocator.
</div>
(Overrides [Bootstrapper..::.ConfigureServiceLocator()()()](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configureservicelocator).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateContainer](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.createcontainer)</td>
<td><div class="summary">
Creates the IUnityContainer that will be used as the default container.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateLogger](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createlogger)</td>
<td><div class="summary">
Create the [ILoggerFacade](https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade) used by the bootstrapper.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createmodulecatalog)</td>
<td><div class="summary">
Creates the [IModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog) used by Prism.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateShell](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createshell)</td>
<td><div class="summary">
Creates the shell or main window of the application.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
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
<td>[InitializeModules](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.initializemodules)</td>
<td><div class="summary">
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog
</div>
(Overrides [Bootstrapper..::.InitializeModules()()()](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.initializemodules).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InitializeShell](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.initializeshell)</td>
<td><div class="summary">
Initializes the shell.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
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
<td>[RegisterFrameworkExceptionTypes](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.registerframeworkexceptiontypes)</td>
<td><div class="summary">
Registers in the IUnityContainer the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the Exceptions that are not considered root exceptions by the [ExceptionExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions).
</div>
(Overrides [Bootstrapper..::.RegisterFrameworkExceptionTypes()()()](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.registerframeworkexceptiontypes).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[RegisterTypeIfMissing](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.registertypeifmissing(system.type%2csystem.type%2csystem.boolean))</td>
<td><div class="summary">
Registers a type in the container only if that type was not already registered.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Run()()()](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.run)</td>
<td><div class="summary">
Runs the bootstrapper process.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Run(Boolean)](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.run(system.boolean))</td>
<td><div class="summary">
Run the bootstrapper process.
</div>
(Overrides [Bootstrapper..::.Run(Boolean)](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.run(system.boolean)).)</td>
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
[UnityBootstrapper Class](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper)<br/>
[Microsoft.Practices.Prism.UnityExtensions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions)<br/>