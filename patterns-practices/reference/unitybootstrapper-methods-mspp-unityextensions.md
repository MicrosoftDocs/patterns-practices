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
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.configurecontainer">ConfigureContainer</a></td>
<td><div class="summary">
Configures the IUnityContainer. May be overwritten in a derived class to add specific type mappings required by the application.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configuredefaultregionbehaviors">ConfigureDefaultRegionBehaviors</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorfactory">IRegionBehaviorFactory</a>. This will be the list of default behaviors that will be added to a region.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configuremodulecatalog">ConfigureModuleCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> used by Prism.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configureregionadaptermappings">ConfigureRegionAdapterMappings</a></td>
<td><div class="summary">
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.configureservicelocator">ConfigureServiceLocator</a></td>
<td><div class="summary">
Configures the LocatorProvider for the ServiceLocator.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configureservicelocator">Bootstrapper..::.ConfigureServiceLocator()()()</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.createcontainer">CreateContainer</a></td>
<td><div class="summary">
Creates the IUnityContainer that will be used as the default container.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createlogger">CreateLogger</a></td>
<td><div class="summary">
Create the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> used by the bootstrapper.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createmodulecatalog">CreateModuleCatalog</a></td>
<td><div class="summary">
Creates the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> used by Prism.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createshell">CreateShell</a></td>
<td><div class="summary">
Creates the shell or main window of the application.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.initializemodules">InitializeModules</a></td>
<td><div class="summary">
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.initializemodules">Bootstrapper..::.InitializeModules()()()</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.initializeshell">InitializeShell</a></td>
<td><div class="summary">
Initializes the shell.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.registerframeworkexceptiontypes">RegisterFrameworkExceptionTypes</a></td>
<td><div class="summary">
Registers in the IUnityContainer the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the Exceptions that are not considered root exceptions by the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions">ExceptionExtensions</a>.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.registerframeworkexceptiontypes">Bootstrapper..::.RegisterFrameworkExceptionTypes()()()</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.registertypeifmissing(system.type%2csystem.type%2csystem.boolean)">RegisterTypeIfMissing</a></td>
<td><div class="summary">
Registers a type in the container only if that type was not already registered.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.run">Run()()()</a></td>
<td><div class="summary">
Runs the bootstrapper process.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper.run(system.boolean)">Run(Boolean)</a></td>
<td><div class="summary">
Run the bootstrapper process.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.run(system.boolean)">Bootstrapper..::.Run(Boolean)</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

## See Also
[UnityBootstrapper Class](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapper)<br/>
[Microsoft.Practices.Prism.UnityExtensions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions)<br/>