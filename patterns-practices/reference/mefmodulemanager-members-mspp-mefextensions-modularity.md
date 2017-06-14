---
TOCTitle: MefModuleManager Members
Title: 'MefModuleManager Members (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager'
ms:mtpsurl: 'mefmodulemanager-members-mspp-mefextensions-modularity.md'
---

# MefModuleManager Members

The [MefModuleManager](https://review.docs.microsoft.com/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity) type exposes the following members.

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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>MefModuleManager</td>
<td><div class="summary">
Initializes a new instance of the [MefModuleManager](https://review.docs.microsoft.com/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity) class.
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Dispose()](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-dispose-method-mspp-modularity)</td>
<td><div class="summary">
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
</div>
(Inherited from [ModuleManager](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Dispose(Boolean)](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-dispose-method-boolean-mspp-modularity)</td>
<td><div class="summary">
Disposes the associated [IModuleTypeLoader](https://review.docs.microsoft.com/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)s.
</div>
(Inherited from [ModuleManager](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[HandleModuleTypeLoadingError](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-handlemoduletypeloadingerror-method-mspp-modularity)</td>
<td><div class="summary">
Handles any exception occurred in the module typeloading process, logs the error using the [ILoggerFacade](https://review.docs.microsoft.com/patterns-practices/reference/iloggerfacade-interface-mspp-logging) and throws a [ModuleTypeLoadingException](https://review.docs.microsoft.com/patterns-practices/reference/moduletypeloadingexception-class-mspp-modularity). This method can be overridden to provide a different behavior.
</div>
(Inherited from [ModuleManager](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[LoadModule](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-loadmodule-method-mspp-modularity)</td>
<td><div class="summary">
Loads and initializes the module on the [ModuleCatalog](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity) with the name moduleName.
</div>
(Inherited from [ModuleManager](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[LoadModulesThatAreReadyForLoad](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-loadmodulesthatarereadyforload-method-mspp-modularity)</td>
<td><div class="summary">
Loads the modules that are not intialized and have their dependencies loaded.
</div>
(Inherited from [ModuleManager](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
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
<td>[ModuleNeedsRetrieval](https://review.docs.microsoft.com/patterns-practices/reference/mefmodulemanager-moduleneedsretrieval-method-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Checks if the module needs to be retrieved before it's initialized.
</div>
(Overrides [ModuleManager.ModuleNeedsRetrieval(ModuleInfo)](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-moduleneedsretrieval-method-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[OnImportsSatisfied](https://review.docs.microsoft.com/patterns-practices/reference/mefmodulemanager-onimportssatisfied-method-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Called when a part's imports have been satisfied and it is safe to use.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Run](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-run-method-mspp-modularity)</td>
<td><div class="summary">
Initializes the modules marked as [WhenAvailable](https://review.docs.microsoft.com/patterns-practices/reference/initializationmode-enumeration-mspp-modularity) on the [ModuleCatalog](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity).
</div>
(Inherited from [ModuleManager](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
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
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ImportedModules](https://review.docs.microsoft.com/patterns-practices/reference/mefmodulemanager-importedmodules-property-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Gets or sets the modules to be imported.
</div></td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ModuleCatalog](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity)</td>
<td><div class="summary">
The module catalog specified in the constructor.
</div>
(Inherited from [ModuleManager](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ModuleTypeLoaders](https://review.docs.microsoft.com/patterns-practices/reference/mefmodulemanager-moduletypeloaders-property-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Gets or sets the type loaders used by the module manager.
</div>
(Overrides [ModuleManager.ModuleTypeLoaders](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-moduletypeloaders-property-mspp-modularity).)</td>
</tr>
</tbody>
</table>

## Events

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
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[LoadModuleCompleted](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-loadmodulecompleted-event-mspp-modularity)</td>
<td><div class="summary">
Raised when a module is loaded or fails to load.
</div>
(Inherited from [ModuleManager](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[ModuleDownloadProgressChanged](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-moduledownloadprogresschanged-event-mspp-modularity)</td>
<td><div class="summary">
Raised repeatedly to provide progress as modules are loaded in the background.
</div>
(Inherited from [ModuleManager](https://review.docs.microsoft.com/patterns-practices/reference/modulemanager-class-mspp-modularity).)</td>
</tr>
</tbody>
</table>

## See Also

[MefModuleManager Class](https://review.docs.microsoft.com/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity)<br/>
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://review.docs.microsoft.com/patterns-practices/reference/mspp-mefextensions-modularity-namespace)<br/>