---
TOCTitle: Bootstrapper Members
Title: 'Bootstrapper Members (Microsoft.Practices.Prism)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Bootstrapper'
ms:mtpsurl: 'bootstrapper-members-mspp.md'
---

# Bootstrapper Members

The [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp) type exposes the following members.

## Constructors

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-class-mspp" data-raw-source="[Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp)">Bootstrapper</a></td>
<td><div class="summary">
Initializes a new instance of the <a href="/patterns-practices/reference/bootstrapper-class-mspp" data-raw-source="[Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp)">Bootstrapper</a> class
</div></td>
</tr>
</tbody>
</table>

## Methods

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-configuredefaultregionbehaviors-method-mspp" data-raw-source="[ConfigureDefaultRegionBehaviors](/patterns-practices/reference/bootstrapper-configuredefaultregionbehaviors-method-mspp)">ConfigureDefaultRegionBehaviors</a></td>
<td><div class="summary">
Configures the <a href="/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions" data-raw-source="[IRegionBehaviorFactory](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions)">IRegionBehaviorFactory</a>. This will be the list of default behaviors that will be added to a region.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-configuremodulecatalog-method-mspp" data-raw-source="[ConfigureModuleCatalog](/patterns-practices/reference/bootstrapper-configuremodulecatalog-method-mspp)">ConfigureModuleCatalog</a></td>
<td><div class="summary">
Configures the <a href="/patterns-practices/reference/imodulecatalog-interface-mspp-modularity" data-raw-source="[IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity)">IModuleCatalog</a> used by Prism.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-configureregionadaptermappings-method-mspp" data-raw-source="[ConfigureRegionAdapterMappings](/patterns-practices/reference/bootstrapper-configureregionadaptermappings-method-mspp)">ConfigureRegionAdapterMappings</a></td>
<td><div class="summary">
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-configureservicelocator-method-mspp" data-raw-source="[ConfigureServiceLocator](/patterns-practices/reference/bootstrapper-configureservicelocator-method-mspp)">ConfigureServiceLocator</a></td>
<td><div class="summary">
Configures the LocatorProvider for the ServiceLocator.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-createlogger-method-mspp" data-raw-source="[CreateLogger](/patterns-practices/reference/bootstrapper-createlogger-method-mspp)">CreateLogger</a></td>
<td><div class="summary">
Create the <a href="/patterns-practices/reference/iloggerfacade-interface-mspp-logging" data-raw-source="[ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)">ILoggerFacade</a> used by the bootstrapper.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-createmodulecatalog-method-mspp" data-raw-source="[CreateModuleCatalog](/patterns-practices/reference/bootstrapper-createmodulecatalog-method-mspp)">CreateModuleCatalog</a></td>
<td><div class="summary">
Creates the <a href="/patterns-practices/reference/imodulecatalog-interface-mspp-modularity" data-raw-source="[IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity)">IModuleCatalog</a> used by Prism.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-createshell-method-mspp" data-raw-source="[CreateShell](/patterns-practices/reference/bootstrapper-createshell-method-mspp)">CreateShell</a></td>
<td><div class="summary">
Creates the shell or main window of the application.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47" data-raw-source="[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7" data-raw-source="[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y" data-raw-source="[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9" data-raw-source="[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65" data-raw-source="[Type](http://msdn.microsoft.com/en-us/library/42892f65)">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-initializemodules-method-mspp" data-raw-source="[InitializeModules](/patterns-practices/reference/bootstrapper-initializemodules-method-mspp)">InitializeModules</a></td>
<td><div class="summary">
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-initializeshell-method-mspp" data-raw-source="[InitializeShell](/patterns-practices/reference/bootstrapper-initializeshell-method-mspp)">InitializeShell</a></td>
<td><div class="summary">
Initializes the shell.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a" data-raw-source="[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-registerframeworkexceptiontypes-method-mspp" data-raw-source="[RegisterFrameworkExceptionTypes](/patterns-practices/reference/bootstrapper-registerframeworkexceptiontypes-method-mspp)">RegisterFrameworkExceptionTypes</a></td>
<td><div class="summary">
Registers the <a href="http://msdn.microsoft.com/en-us/library/42892f65" data-raw-source="[Type](http://msdn.microsoft.com/en-us/library/42892f65)">Type</a>s of the Exceptions that are not considered root exceptions by the <a href="/patterns-practices/reference/exceptionextensions-class-mspp" data-raw-source="[ExceptionExtensions](/patterns-practices/reference/exceptionextensions-class-mspp)">ExceptionExtensions</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-run-method-mspp" data-raw-source="[Run()](/patterns-practices/reference/bootstrapper-run-method-mspp)">Run()</a></td>
<td><div class="summary">
Runs the bootstrapper process.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-run-method-mspp" data-raw-source="[Run(Boolean)](/patterns-practices/reference/bootstrapper-run-method-mspp)">Run(Boolean)</a></td>
<td><div class="summary">
Run the bootstrapper process.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2" data-raw-source="[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
</tbody>
</table>

## Properties

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protproperty.gif" alt="Protected property"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-logger-property-mspp" data-raw-source="[Logger](/patterns-practices/reference/bootstrapper-logger-property-mspp)">Logger</a></td>
<td><div class="summary">
Gets the <a href="/patterns-practices/reference/iloggerfacade-interface-mspp-logging" data-raw-source="[ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)">ILoggerFacade</a> for the application.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protproperty.gif" alt="Protected property"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-modulecatalog-property-mspp" data-raw-source="[ModuleCatalog](/patterns-practices/reference/bootstrapper-modulecatalog-property-mspp)">ModuleCatalog</a></td>
<td><div class="summary">
Gets the default <a href="/patterns-practices/reference/imodulecatalog-interface-mspp-modularity" data-raw-source="[IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity)">IModuleCatalog</a> for the application.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protproperty.gif" alt="Protected property"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-shell-property-mspp" data-raw-source="[Shell](/patterns-practices/reference/bootstrapper-shell-property-mspp)">Shell</a></td>
<td><div class="summary">
Gets the shell user interface
</div></td>
</tr>
</tbody>
</table>

## See Also

[Bootstrapper Class](/patterns-practices/reference/bootstrapper-class-mspp)  
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)  