---
TOCTitle: ConfigurationModuleCatalog Methods
Title: 'ConfigurationModuleCatalog Methods (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Modularity.ConfigurationModuleCatalog'
ms:mtpsurl: 'configurationmodulecatalog-methods-mspp-modularity.md'
---


# ConfigurationModuleCatalog Methods

The [ConfigurationModuleCatalog](/patterns-practices/reference/configurationmodulecatalog-class-mspp-modularity) type exposes the following members.

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
<td><a href="/patterns-practices/reference/modulecatalog-addgroup-method-mspp-modularity">AddGroup</a></td>
<td><div class="summary">
Creates and adds a <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity">ModuleInfoGroup</a> to the catalog.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-addmodule-method-moduleinfo-mspp-modularity">AddModule(ModuleInfo)</a></td>
<td><div class="summary">
Adds a <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a> to the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/addmodule-mthd-type-str">AddModule(Type, String[])</a></td>
<td><div class="summary">
Adds a groupless <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a> to the catalog.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/addmodule-mthd-str-str-str">AddModule(String, String, String[])</a></td>
<td><div class="summary">
Adds a groupless <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a> to the catalog.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/addmodule-mthd-type-initializationmode-str">AddModule(Type, InitializationMode, String[])</a></td>
<td><div class="summary">
Adds a groupless <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a> to the catalog.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/addmodule-mthd-str-str-initializationmode-str">AddModule(String, String, InitializationMode, String[])</a></td>
<td><div class="summary">
Adds a groupless <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a> to the catalog.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/addmodule-mthd-str-str-str-initializationmode-str">AddModule(String, String, String, InitializationMode, String[])</a></td>
<td><div class="summary">
Adds a groupless <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a> to the catalog.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-completelistwithdependencies-method-mspp-modularity">CompleteListWithDependencies</a></td>
<td><div class="summary">
Returns a list of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a>s that contain both the <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a>s in modules, but also all the modules they depend on.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-ensurecatalogvalidated-method-mspp-modularity">EnsureCatalogValidated</a></td>
<td><div class="summary">
Ensures that the catalog is validated.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
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
<td><a href="/patterns-practices/reference/modulecatalog-getdependentmodules-method-mspp-modularity ">GetDependentModules</a></td>
<td><div class="summary">
Return the list of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a>s that moduleInfo depends on.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-getdependentmodulesinner-method-mspp-modularity">GetDependentModulesInner</a></td>
<td><div class="summary">
Returns the <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a> on which the received module dependens on.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-initialize-method-mspp-modularity">Initialize</a></td>
<td><div class="summary">
Initializes the catalog, which may load and validate the modules.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/configurationmodulecatalog-innerload-method-mspp-modularity">InnerLoad</a></td>
<td><div class="summary">
Loads the catalog from the configuration.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.innerload">ModuleCatalog.InnerLoad()</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-load-method-mspp-modularity">Load</a></td>
<td><div class="summary">
Loads the catalog if necessary.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-sort-method-mspp-modularity">Sort</a></td>
<td><div class="summary">
Sorts a list of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a>s. This method is called by <a href="/patterns-practices/reference/modulecatalog-completelistwithdependencies-method-mspp-modularity">CompleteListWithDependencies(IEnumerable&lt;ModuleInfo&gt;)</a> to return a sorted list.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-validate-method-mspp-modularity">Validate</a></td>
<td><div class="summary">
Validates the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-validatecrossgroupdependencies-method-mspp-modularity">ValidateCrossGroupDependencies</a></td>
<td><div class="summary">
Ensures that there are no dependencies between modules on different groups.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-validatedependenciesinitializationmode-method-mspp-modularity">ValidateDependenciesInitializationMode</a></td>
<td><div class="summary">
Ensures that there are no modules marked to be loaded <a href="/patterns-practices/reference/initializationmode-enumeration-mspp-modularity">WhenAvailable</a> depending on modules loaded <a href="/patterns-practices/reference/initializationmode-enumeration-mspp-modularity">OnDemand</a>
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-validatedependencygraph-method-mspp-modularity">ValidateDependencyGraph</a></td>
<td><div class="summary">
Ensures that there are no cyclic dependencies.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-validateuniquemodules-method-mspp-modularity">ValidateUniqueModules</a></td>
<td><div class="summary">
Makes sure all modules have an Unique name.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[ConfigurationModuleCatalog Class](/patterns-practices/reference/configurationmodulecatalog-class-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>