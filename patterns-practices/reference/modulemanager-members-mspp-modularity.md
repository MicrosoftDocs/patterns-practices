---
TOCTitle: ModuleManager Members
Title: 'ModuleManager Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.ModuleManager'
ms:mtpsurl: 'modulemanager-members-mspp-modularity.md'
---


# ModuleManager Members

The [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity) type exposes the following members.

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
<td>ModuleManager</td>
<td><div class="summary">
Initializes an instance of the [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity) class.
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
<td>[Dispose](/patterns-practices/reference/modulemanager-dispose-method-mspp-modularity)</td>
<td><div class="summary">
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Dispose(Boolean)](/patterns-practices/reference/modulemanager-dispose-method-boolean-mspp-modularity)</td>
<td><div class="summary">
Disposes the associated [IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)s.
</div></td>
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
<td>[HandleModuleTypeLoadingError](/patterns-practices/reference/modulemanager-handlemoduletypeloadingerror-method-mspp-modularity)</td>
<td><div class="summary">
Handles any exception occurred in the module typeloading process, logs the error using the [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) and throws a [ModuleTypeLoadingException](/patterns-practices/reference/moduletypeloadingexception-class-mspp-modularity). This method can be overridden to provide a different behavior.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[LoadModule](/patterns-practices/reference/modulemanager-loadmodule-method-mspp-modularity)</td>
<td><div class="summary">
Loads and initializes the module on the [ModuleCatalog](/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity) with the name moduleName.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[LoadModulesThatAreReadyForLoad](/patterns-practices/reference/modulemanager-loadmodulesthatarereadyforload-method-mspp-modularity)</td>
<td><div class="summary">
Loads the modules that are not intialized and have their dependencies loaded.
</div></td>
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
<td>[ModuleNeedsRetrieval](/patterns-practices/reference/modulemanager-moduleneedsretrieval-method-mspp-modularity)</td>
<td><div class="summary">
Checks if the module needs to be retrieved before it's initialized.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Run](/patterns-practices/reference/modulemanager-run-method-mspp-modularity)</td>
<td><div class="summary">
Initializes the modules marked as [WhenAvailable](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity) on the [ModuleCatalog](/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity).
</div></td>
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
<td>[ModuleCatalog](/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity)</td>
<td><div class="summary">
The module catalog specified in the constructor.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ModuleTypeLoaders](/patterns-practices/reference/modulemanager-moduletypeloaders-property-mspp-modularity)</td>
<td><div class="summary">
Returns the list of registered [IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity) instances that will be used to load the types of modules.
</div></td>
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
<td>[LoadModuleCompleted](/patterns-practices/reference/modulemanager-loadmodulecompleted-event-mspp-modularity)</td>
<td><div class="summary">
Raised when a module is loaded or fails to load.
</div></td>
</tr>
<tr class="even">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[ModuleDownloadProgressChanged](/patterns-practices/reference/modulemanager-moduledownloadprogresschanged-event-mspp-modularity)</td>
<td><div class="summary">
Raised repeatedly to provide progress as modules are loaded in the background.
</div></td>
</tr>
</tbody>
</table>

## See Also

[ModuleManager Class](/patterns-practices/reference/modulemanager-class-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  