---
TOCTitle: MefModuleManager Members
Title: 'MefModuleManager Members (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager'
ms:mtpsurl: 'mefmodulemanager-members-mspp-mefextensions-modularity.md'
---

# MefModuleManager Members

The [MefModuleManager](/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity) type exposes the following members.

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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>MefModuleManager</td>
<td>Initializes a new instance of the [MefModuleManager](/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity) class.</td>
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Dispose()](/patterns-practices/reference/modulemanager-dispose-method-mspp-modularity)</td>
<td>Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
(Inherited from [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Dispose(Boolean)](/patterns-practices/reference/modulemanager-dispose-method-boolean-mspp-modularity)</td>
<td>Disposes the associated [IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)s.
(Inherited from [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td>Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td>Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td>Serves as a hash function for a particular type.
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td>Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[HandleModuleTypeLoadingError](/patterns-practices/reference/modulemanager-handlemoduletypeloadingerror-method-mspp-modularity)</td>
<td>Handles any exception occurred in the module typeloading process, logs the error using the [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) and throws a [ModuleTypeLoadingException](/patterns-practices/reference/moduletypeloadingexception-class-mspp-modularity). This method can be overridden to provide a different behavior.
(Inherited from [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[LoadModule](/patterns-practices/reference/modulemanager-loadmodule-method-mspp-modularity)</td>
<td>Loads and initializes the module on the [ModuleCatalog](/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity) with the name moduleName.
(Inherited from [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[LoadModulesThatAreReadyForLoad](/patterns-practices/reference/modulemanager-loadmodulesthatarereadyforload-method-mspp-modularity)</td>
<td>Loads the modules that are not intialized and have their dependencies loaded.
(Inherited from [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td>Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ModuleNeedsRetrieval](/patterns-practices/reference/mefmodulemanager-moduleneedsretrieval-method-mspp-mefextensions-modularity)</td>
<td>Checks if the module needs to be retrieved before it's initialized.
(Overrides [ModuleManager.ModuleNeedsRetrieval(ModuleInfo)](/patterns-practices/reference/modulemanager-moduleneedsretrieval-method-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[OnImportsSatisfied](/patterns-practices/reference/mefmodulemanager-onimportssatisfied-method-mspp-mefextensions-modularity)</td>
<td>Called when a part's imports have been satisfied and it is safe to use.</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Run](/patterns-practices/reference/modulemanager-run-method-mspp-modularity)</td>
<td>Initializes the modules marked as [WhenAvailable](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity) on the [ModuleCatalog](/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity).
(Inherited from [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td>Returns a string that represents the current object.
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
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
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ImportedModules](/patterns-practices/reference/mefmodulemanager-importedmodules-property-mspp-mefextensions-modularity)</td>
<td>Gets or sets the modules to be imported.</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ModuleCatalog](/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity)</td>
<td>The module catalog specified in the constructor.
(Inherited from [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ModuleTypeLoaders](/patterns-practices/reference/mefmodulemanager-moduletypeloaders-property-mspp-mefextensions-modularity)</td>
<td>Gets or sets the type loaders used by the module manager.
(Overrides [ModuleManager.ModuleTypeLoaders](/patterns-practices/reference/modulemanager-moduletypeloaders-property-mspp-modularity).)</td>
</tr>
</tbody>
</table>

## Events

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
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[LoadModuleCompleted](/patterns-practices/reference/modulemanager-loadmodulecompleted-event-mspp-modularity)</td>
<td>Raised when a module is loaded or fails to load.
(Inherited from [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[ModuleDownloadProgressChanged](/patterns-practices/reference/modulemanager-moduledownloadprogresschanged-event-mspp-modularity)</td>
<td>Raised repeatedly to provide progress as modules are loaded in the background.
(Inherited from [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
</tbody>
</table>

## See Also

[MefModuleManager Class](/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
