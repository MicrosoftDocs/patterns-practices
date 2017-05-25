---
TOCTitle: ModuleCatalog Methods
Title: 'ModuleCatalog Methods (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Modularity.ModuleCatalog'
ms:mtpsurl: 'modulecatalog-methods-mspp-modularity.md'
---

Prism Class Library

ModuleCatalog Methods
=====================

The [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
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
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.addgroup(microsoft.practices.prism.modularity.initializationmode%2csystem.string%2cmicrosoft.practices.prism.modularity.moduleinfo%5b%5d)">AddGroup</a></td>
<td><div class="summary">
Creates and adds a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup">ModuleInfoGroup</a> to the catalog.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.addmodule(microsoft.practices.prism.modularity.moduleinfo)">AddModule(ModuleInfo)</a></td>
<td><div class="summary">
Adds a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> to the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.addmodule(system.type%2csystem.string%5b%5d)">AddModule(Type, array&lt;String&gt;)</a></td>
<td><div class="summary">
Adds a groupless <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> to the catalog.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.addmodule(system.string%2csystem.string%2csystem.string%5b%5d)">AddModule(String, String, array&lt;String&gt;)</a></td>
<td><div class="summary">
Adds a groupless <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> to the catalog.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.addmodule(system.type%2cmicrosoft.practices.prism.modularity.initializationmode%2csystem.string%5b%5d)">AddModule(Type, InitializationMode, array&lt;String&gt;)</a></td>
<td><div class="summary">
Adds a groupless <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> to the catalog.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.addmodule(system.string%2csystem.string%2cmicrosoft.practices.prism.modularity.initializationmode%2csystem.string%5b%5d)">AddModule(String, String, InitializationMode, array&lt;String&gt;)</a></td>
<td><div class="summary">
Adds a groupless <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> to the catalog.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.addmodule(system.string%2csystem.string%2csystem.string%2cmicrosoft.practices.prism.modularity.initializationmode%2csystem.string%5b%5d)">AddModule(String, String, String, InitializationMode, array&lt;String&gt;)</a></td>
<td><div class="summary">
Adds a groupless <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> to the catalog.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.completelistwithdependencies(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d)">CompleteListWithDependencies</a></td>
<td><div class="summary">
Returns a list of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s that contain both the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s in modules, but also all the modules they depend on.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg431050.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.createfromxaml(system.io.stream)">CreateFromXaml(Stream)</a></td>
<td><div class="summary">
Creates a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a> from XAML.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg431050.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.createfromxaml(system.uri)">CreateFromXaml(Uri)</a></td>
<td><div class="summary">
Creates a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a> from a XAML included as an Application Resource.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431050.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.ensurecatalogvalidated">EnsureCatalogValidated</a></td>
<td><div class="summary">
Ensures that the catalog is validated.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431050.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.getdependentmodules(microsoft.practices.prism.modularity.moduleinfo)">GetDependentModules</a></td>
<td><div class="summary">
Return the list of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s that moduleInfo depends on.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431050.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.getdependentmodulesinner(microsoft.practices.prism.modularity.moduleinfo)">GetDependentModulesInner</a></td>
<td><div class="summary">
Returns the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> on which the received module dependens on.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.initialize">Initialize</a></td>
<td><div class="summary">
Initializes the catalog, which may load and validate the modules.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431050.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.innerload">InnerLoad</a></td>
<td><div class="summary">
Does the actual work of loading the catalog. The base implementation does nothing.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.load">Load</a></td>
<td><div class="summary">
Loads the catalog if necessary.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431050.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431050.protmethod(en-us,PandP.50).gif" title="Protected method" /><img src="https://msdn.microsoft.com/en-us/Gg431050.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.solvedependencies(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d)">SolveDependencies</a></td>
<td><div class="summary">
Checks for cyclic dependencies, by calling the dependencysolver.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431050.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.sort(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d)">Sort</a></td>
<td><div class="summary">
Sorts a list of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s. This method is called by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.completelistwithdependencies(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d)">CompleteListWithDependencies(IEnumerable&lt;(Of &lt;(ModuleInfo&gt;)&gt;))</a> to return a sorted list.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.validate">Validate</a></td>
<td><div class="summary">
Validates the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431050.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.validatecrossgroupdependencies">ValidateCrossGroupDependencies</a></td>
<td><div class="summary">
Ensures that there are no dependencies between modules on different groups.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431050.protmethod(en-us,PandP.50).gif" title="Protected method" /><img src="https://msdn.microsoft.com/en-us/Gg431050.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.validatedependencies(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d)">ValidateDependencies</a></td>
<td><div class="summary">
Ensures that all the dependencies within modules refer to <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s within that list.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431050.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.validatedependenciesinitializationmode">ValidateDependenciesInitializationMode</a></td>
<td><div class="summary">
Ensures that there are no modules marked to be loaded <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.initializationmode">WhenAvailable</a> depending on modules loaded <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.initializationmode">OnDemand</a>
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431050.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.validatedependencygraph">ValidateDependencyGraph</a></td>
<td><div class="summary">
Ensures that there are no cyclic dependencies.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431050.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.validateuniquemodules">ValidateUniqueModules</a></td>
<td><div class="summary">
Makes sure all modules have an Unique name.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[ModuleCatalog Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
