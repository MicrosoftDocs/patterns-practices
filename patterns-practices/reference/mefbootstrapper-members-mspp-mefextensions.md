---
TOCTitle: MefBootstrapper Members
Title: 'MefBootstrapper Members (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper'
ms:mtpsurl: 'mefbootstrapper-members-mspp-mefextensions.md'
---

# MefBootstrapper Members

The [MefBootstrapper](/patterns-practices/reference/mefextensions.mefbootstrapper) type exposes the following members.

## Constructors

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
<td>MefBootstrapper</td>
<td><div class="summary">
Initializes a new instance of the <a href="/patterns-practices/reference/mefbootstrapper-class-mspp-mefextensions">MefBootstrapper</a> class
</div></td>
</tr>
</tbody>
</table>

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
<td><a href="/patterns-practices/reference/mefbootstrapper-configureaggregatecatalog-method-mspp-mefextensions">ConfigureAggregateCatalog</a></td>
<td><div class="summary">
Configures the <a href="/patterns-practices/reference/mefbootstrapper-aggregatecatalog-property-mspp-mefextensions">AggregateCatalog</a> used by MEF.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/mefbootstrapper-configurecontainer-method-mspp-mefextensions">ConfigureContainer</a></td>
<td><div class="summary">
Configures the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. May be overwritten in a derived class to add specific type mappings required by the application.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/bootstrapper-configuredefaultregionbehaviors-method-mspp">ConfigureDefaultRegionBehaviors</a></td>
<td><div class="summary">
Configures the <a href="/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions">IRegionBehaviorFactory</a>. This will be the list of default behaviors that will be added to a region.
</div>
(Inherited from <a href="/patterns-practices/reference/bootstrapper-class-mspp">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/bootstrapper-configuremodulecatalog-method-mspp">ConfigureModuleCatalog</a></td>
<td><div class="summary">
Configures the <a href="/patterns-practices/reference/imodulecatalog-addmodule-method-mspp-modularity">IModuleCatalog</a> used by Prism.
</div>
(Inherited from <a href="/patterns-practices/reference/bootstrapper-class-mspp">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/bootstrapper-configureregionadaptermappings-method-mspp">ConfigureRegionAdapterMappings</a></td>
<td><div class="summary">
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.
</div>
(Inherited from <a href="/patterns-practices/reference/bootstrapper-class-mspp">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/mefbootstrapper-configureservicelocator-method-mspp-mefextensions">ConfigureServiceLocator</a></td>
<td><div class="summary">
Configures the LocatorProvider for the ServiceLocator.
</div>
(Overrides <a href="/patterns-practices/reference/bootstrapper-configureservicelocator-method-mspp">Bootstrapper.ConfigureServiceLocator()</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/mefbootstrapper-createaggregatecatalog-method-mspp-mefextensions">CreateAggregateCatalog</a></td>
<td><div class="summary">
Configures the <a href="/patterns-practices/reference/mefbootstrapper-aggregatecatalog-property-mspp-mefextensions">AggregateCatalog</a> used by MEF.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/mefbootstrapper-createcontainer-method-mspp-mefextensions">CreateContainer</a></td>
<td><div class="summary">
Creates the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a> that will be used as the default container.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/bootstrapper-createlogger-method-mspp">CreateLogger</a></td>
<td><div class="summary">
Create the <a href="/patterns-practices/reference/iloggerfacade-members-mspp-logging">ILoggerFacade</a> used by the bootstrapper.
</div>
(Inherited from <a href="/patterns-practices/reference/bootstrapper-class-mspp">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/bootstrapper-createmodulecatalog-method-mspp">CreateModuleCatalog</a></td>
<td><div class="summary">
Creates the <a href="/patterns-practices/reference/imodulecatalog-members-mspp-modularity">IModuleCatalog</a> used by Prism.
</div>
(Inherited from <a href="/patterns-practices/reference/bootstrapper-class-mspp">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/bootstrapper-createshell-method-mspp">CreateShell</a></td>
<td><div class="summary">
Creates the shell or main window of the application.
</div>
(Inherited from <a href="/patterns-practices/reference/bootstrapper-class-mspp">Bootstrapper</a>.)</td>
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
<td><a href="/patterns-practices/reference/mefbootstrapper-initializemodules-method-mspp-mefextensions">InitializeModules</a></td>
<td><div class="summary">
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog
</div>
(Overrides <a href="/patterns-practices/reference/bootstrapper-initializemodules-method-mspp">Bootstrapper.InitializeModules()</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/mefbootstrapper-initializeshell-method-mspp-mefextensions">InitializeShell</a></td>
<td><div class="summary">
Initializes the shell.
</div>
(Overrides <a href="/patterns-practices/reference/bootstrapper-initializemodules-method-mspp">Bootstrapper.InitializeShell()</a>.)</td>
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
<td><a href="/patterns-practices/reference/mefbootstrapper-registerbootstrapperprovidedtypes-method-mspp-mefextensions">RegisterBootstrapperProvidedTypes</a></td>
<td><div class="summary">
Helper method for configuring the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. Registers all the types direct instantiated by the bootstrapper with the container.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/mefbootstrapper-registerdefaulttypesifmissing-method-mspp-mefextensions">RegisterDefaultTypesIfMissing</a></td>
<td><div class="summary">
Helper method for configuring the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. Registers defaults for all the types necessary for Prism to work, if they are not already registered.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/bootstrapper-registerframeworkexceptiontypes-method-mspp">RegisterFrameworkExceptionTypes</a></td>
<td><div class="summary">
Registers the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a>s of the Exceptions that are not considered root exceptions by the <a href="/patterns-practices/reference/exceptionextensions">ExceptionExtensions</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/bootstrapper-class-mspp">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/run-mthd">Run()</a></td>
<td><div class="summary">
Runs the bootstrapper process.
</div>
(Inherited from <a href="/patterns-practices/reference/bootstrapper-class-mspp">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/mefbootstrapper-run-method-boolean-mspp-mefextensions">Run(Boolean)</a></td>
<td><div class="summary">
Run the bootstrapper process.
</div>
(Overrides <a href="/patterns-practices/reference/bootstrapper-run-method-boolean-mspp">Bootstrapper.Run(Boolean)</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

## Properties

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
<td>![Protected property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/mefbootstrapper-aggregatecatalog-property-mspp-mefextensions">AggregateCatalog</a></td>
<td><div class="summary">
Gets or sets the default <a href="/patterns-practices/reference/mefbootstrapper-aggregatecatalog-property-mspp-mefextensions">AggregateCatalog</a> for the application.
</div></td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/mefbootstrapper-container-property-mspp-mefextensions">Container</a></td>
<td><div class="summary">
Gets or sets the default <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a> for the application.
</div></td>
</tr>
<tr class="odd">
<td>![Protected property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/bootstrapper-logger-property-mspp">Logger</a></td>
<td><div class="summary">
Gets the <a href="/patterns-practices/reference/iloggerfacade-interface-mspp-logging">ILoggerFacade</a> for the application.
</div>
(Inherited from <a href="/patterns-practices/reference/bootstrapper-class-mspp">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/bootstrapper-modulecatalog-property-mspp">ModuleCatalog</a></td>
<td><div class="summary">
Gets the default <a href="/patterns-practices/reference/imodulecatalog-interface-mspp-modularity">IModuleCatalog</a> for the application.
</div>
(Inherited from <a href="/patterns-practices/reference/bootstrapper-class-mspp">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/bootstrapper-shell-property-mspp">Shell</a></td>
<td><div class="summary">
Gets the shell user interface
</div>
(Inherited from <a href="/patterns-practices/reference/bootstrapper-class-mspp">Bootstrapper</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[MefBootstrapper Class](/patterns-practices/reference/mefbootstrapper-class-mspp-mefextensions)

[Microsoft.Practices.Prism.MefExtensions Namespace](/patterns-practices/reference/mspp-mefextensions-namespace)
