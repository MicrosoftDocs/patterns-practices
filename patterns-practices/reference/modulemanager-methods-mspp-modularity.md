---
TOCTitle: ModuleManager Methods
Title: 'ModuleManager Methods (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Modularity.ModuleManager'
ms:mtpsurl: 'modulemanager-methods-mspp-modularity.md'
---

# ModuleManager Methods

The [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity) type exposes the following members.

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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/modulemanager-dispose-method-mspp-modularity" data-raw-source="[Dispose](/patterns-practices/reference/modulemanager-dispose-method-mspp-modularity)">Dispose</a></td>
<td><div class="summary">
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/modulemanager-dispose-method-boolean-mspp-modularity" data-raw-source="[Dispose(Boolean)](/patterns-practices/reference/modulemanager-dispose-method-boolean-mspp-modularity)">Dispose(Boolean)</a></td>
<td><div class="summary">
Disposes the associated <a href="/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity" data-raw-source="[IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)">IModuleTypeLoader</a>s.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47" data-raw-source="[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7" data-raw-source="[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y" data-raw-source="[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9" data-raw-source="[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65" data-raw-source="[Type](http://msdn.microsoft.com/en-us/library/42892f65)">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/modulemanager-handlemoduletypeloadingerror-method-mspp-modularity" data-raw-source="[HandleModuleTypeLoadingError](/patterns-practices/reference/modulemanager-handlemoduletypeloadingerror-method-mspp-modularity)">HandleModuleTypeLoadingError</a></td>
<td><div class="summary">
Handles any exception occurred in the module typeloading process, logs the error using the <a href="/patterns-practices/reference/iloggerfacade-interface-mspp-logging" data-raw-source="[ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)">ILoggerFacade</a> and throws a <a href="/patterns-practices/reference/moduletypeloadingexception-class-mspp-modularity" data-raw-source="[ModuleTypeLoadingException](/patterns-practices/reference/moduletypeloadingexception-class-mspp-modularity)">ModuleTypeLoadingException</a>. This method can be overridden to provide a different behavior.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/modulemanager-loadmodule-method-mspp-modularity" data-raw-source="[LoadModule](/patterns-practices/reference/modulemanager-loadmodule-method-mspp-modularity)">LoadModule</a></td>
<td><div class="summary">
Loads and initializes the module on the <a href="/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity)">ModuleCatalog</a> with the name moduleName.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/modulemanager-loadmodulesthatarereadyforload-method-mspp-modularity" data-raw-source="[LoadModulesThatAreReadyForLoad](/patterns-practices/reference/modulemanager-loadmodulesthatarereadyforload-method-mspp-modularity)">LoadModulesThatAreReadyForLoad</a></td>
<td><div class="summary">
Loads the modules that are not intialized and have their dependencies loaded.
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
<td><a href="/patterns-practices/reference/modulemanager-moduleneedsretrieval-method-mspp-modularity" data-raw-source="[ModuleNeedsRetrieval](/patterns-practices/reference/modulemanager-moduleneedsretrieval-method-mspp-modularity)">ModuleNeedsRetrieval</a></td>
<td><div class="summary">
Checks if the module needs to be retrieved before it&#39;s initialized.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/modulemanager-run-method-mspp-modularity" data-raw-source="[Run](/patterns-practices/reference/modulemanager-run-method-mspp-modularity)">Run</a></td>
<td><div class="summary">
Initializes the modules marked as <a href="/patterns-practices/reference/initializationmode-enumeration-mspp-modularity" data-raw-source="[WhenAvailable](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity)">WhenAvailable</a> on the <a href="/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity)">ModuleCatalog</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2" data-raw-source="[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[ModuleManager Class](/patterns-practices/reference/modulemanager-class-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  