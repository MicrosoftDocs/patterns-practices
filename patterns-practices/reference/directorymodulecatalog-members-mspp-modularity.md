---
TOCTitle: DirectoryModuleCatalog Members
Title: 'DirectoryModuleCatalog Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.DirectoryModuleCatalog'
ms:mtpsurl: 'directorymodulecatalog-members-mspp-modularity.md'
---

# DirectoryModuleCatalog Members

The [DirectoryModuleCatalog](/patterns-practices/reference/directorymodulecatalog-class-mspp-modularity) type exposes the following members.

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
<td>DirectoryModuleCatalog</td>
<td><div class="summary">
Initializes a new instance of the [DirectoryModuleCatalog](/patterns-practices/reference/directorymodulecatalog-class-mspp-modularity) class
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
<td>[AddGroup](/patterns-practices/reference/modulecatalog-addgroup-method-mspp-modularity)</td>
<td><div class="summary">
Creates and adds a [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) to the catalog.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddModule(ModuleInfo)](/patterns-practices/reference/modulecatalog-addmodule-method-moduleinfo-mspp-modularity)</td>
<td><div class="summary">
Adds a [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddModule(Type, String())](/patterns-practices/reference/addmodule-mthd-type-str)</td>
<td><div class="summary">
Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddModule(String, String, String())](/patterns-practices/reference/addmodule-mthd-str-str-str)</td>
<td><div class="summary">
Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddModule(Type, InitializationMode, String())](/patterns-practices/reference/addmodule-mthd-type-initializationmode-str)</td>
<td><div class="summary">
Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddModule(String, String, InitializationMode, String())](/patterns-practices/reference/addmodule-mthd-str-str-initializationmode-str)</td>
<td><div class="summary">
Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddModule(String, String, String, InitializationMode, String())](/patterns-practices/reference/addmodule-mthd-str-str-str-initializationmode-str)</td>
<td><div class="summary">
Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[BuildChildDomain](/patterns-practices/reference/directorymodulecatalog-buildchilddomain-method-mspp-modularity)</td>
<td><div class="summary">
Creates a new child domain and copies the evidence from a parent domain.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CompleteListWithDependencies](/patterns-practices/reference/modulecatalog-completelistwithdependencies-method-mspp-modularity)</td>
<td><div class="summary">
Returns a list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s that contain both the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s in modules, but also all the modules they depend on.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[EnsureCatalogValidated](/patterns-practices/reference/modulecatalog-ensurecatalogvalidated-method-mspp-modularity)</td>
<td><div class="summary">
Ensures that the catalog is validated.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
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
<td>[GetDependentModules](/patterns-practices/reference/modulecatalog-getdependentmodules-method-mspp-modularity)</td>
<td><div class="summary">
Return the list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s that moduleInfo depends on.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[GetDependentModulesInner](/patterns-practices/reference/modulecatalog-getdependentmodulesinner-method-mspp-modularity)</td>
<td><div class="summary">
Returns the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) on which the received module dependens on.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Initialize](/patterns-practices/reference/modulecatalog-initialize-method-mspp-modularity)</td>
<td><div class="summary">
Initializes the catalog, which may load and validate the modules.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InnerLoad](/patterns-practices/reference/directorymodulecatalog-innerload-method-mspp-modularity)</td>
<td><div class="summary">
Drives the main logic of building the child domain and searching for the assemblies.
</div>
(Overrides [ModuleCatalog.InnerLoad()](/patterns-practices/reference/modulecatalog-innerload-method-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Load](/patterns-practices/reference/modulecatalog-load-method-mspp-modularity)</td>
<td><div class="summary">
Loads the catalog if necessary.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
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
<td>[Sort](/patterns-practices/reference/modulecatalog-sort-method-mspp-modularity)</td>
<td><div class="summary">
Sorts a list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s. This method is called by [CompleteListWithDependencies(IEnumerable&lt;ModuleInfo&gt;)](/patterns-practices/reference/modulecatalog-completelistwithdependencies-method-mspp-modularity) to return a sorted list.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Validate](/patterns-practices/reference/modulecatalog-validate-method-mspp-modularity)</td>
<td><div class="summary">
Validates the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ValidateCrossGroupDependencies](/patterns-practices/reference/modulecatalog-validatecrossgroupdependencies-method-mspp-modularity)</td>
<td><div class="summary">
Ensures that there are no dependencies between modules on different groups.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ValidateDependenciesInitializationMode](/patterns-practices/reference/modulecatalog-validatedependenciesinitializationmode-method-mspp-modularity)</td>
<td><div class="summary">
Ensures that there are no modules marked to be loaded [WhenAvailable](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity) depending on modules loaded [OnDemand](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity)
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ValidateDependencyGraph](/patterns-practices/reference/modulecatalog-validatedependencygraph-method-mspp-modularity)</td>
<td><div class="summary">
Ensures that there are no cyclic dependencies.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ValidateUniqueModules](/patterns-practices/reference/modulecatalog-validateuniquemodules-method-mspp-modularity)</td>
<td><div class="summary">
Makes sure all modules have an Unique name.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
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
<td>[GrouplessModules](/patterns-practices/reference/modulecatalog-grouplessmodules-property-mspp-modularity)</td>
<td><div class="summary">
Returns the list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s that are not contained within any [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity).
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Groups](/patterns-practices/reference/modulecatalog-groups-property-mspp-modularity)</td>
<td><div class="summary">
Gets the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)s that have been added to the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Items](/patterns-practices/reference/modulecatalog-items-property-mspp-modularity)</td>
<td><div class="summary">
Gets the items in the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity). This property is mainly used to add [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)s or [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s through XAML.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ModulePath](/patterns-practices/reference/directorymodulecatalog-modulepath-property-mspp-modularity)</td>
<td><div class="summary">
Directory containing modules to search for.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Modules](/patterns-practices/reference/modulecatalog-modules-property-mspp-modularity)</td>
<td><div class="summary">
Gets all the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) classes that are in the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity), regardless if they are within a [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) or not.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[Validated](/patterns-practices/reference/modulecatalog-validated-property-mspp-modularity)</td>
<td><div class="summary">
Gets or sets a value that remembers whether the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) has been validated already.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
</tbody>
</table>

## See Also

[DirectoryModuleCatalog Class](/patterns-practices/reference/directorymodulecatalog-class-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)