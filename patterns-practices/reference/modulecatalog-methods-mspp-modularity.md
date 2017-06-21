---
TOCTitle: ModuleCatalog Methods
Title: 'ModuleCatalog Methods (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Modularity.ModuleCatalog'
ms:mtpsurl: 'modulecatalog-methods-mspp-modularity.md'
---

# ModuleCatalog Methods

The [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) type exposes the following members.

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
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddModule(ModuleInfo)](/patterns-practices/reference/modulecatalog-addmodule-method-moduleinfo-mspp-modularity)</td>
<td><div class="summary">
Adds a [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddModule(Type, String[])](/patterns-practices/reference/addmodule-mthd-type-str)</td>
<td><div class="summary">
Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddModule(String, String, String[])](/patterns-practices/reference/addmodule-mthd-str-str-str)</td>
<td><div class="summary">
Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddModule(Type, InitializationMode, String[])](/patterns-practices/reference/addmodule-mthd-type-initializationmode-str)</td>
<td><div class="summary">
Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddModule(String, String, InitializationMode, String[])](/patterns-practices/reference/addmodule-mthd-str-str-initializationmode-str)</td>
<td><div class="summary">
Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddModule(String, String, String, InitializationMode, String[])](/patterns-practices/reference/addmodule-mthd-str-str-str-initializationmode-str)</td>
<td><div class="summary">
Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CompleteListWithDependencies](/patterns-practices/reference/modulecatalog-completelistwithdependencies-method-mspp-modularity)</td>
<td><div class="summary">
Returns a list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s that contain both the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s in <i>modules</i>, but also all the modules they depend on.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[CreateFromXaml(Stream)](/patterns-practices/reference/modulecatalog-createfromxaml-method-stream-mspp-modularity)</td>
<td><div class="summary">
Creates a [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) from XAML.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[CreateFromXaml(Uri)](/patterns-practices/reference/modulecatalog-createfromxaml-method-uri-mspp-modularity)</td>
<td><div class="summary">
Creates a [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) from a XAML included as an Application Resource.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[EnsureCatalogValidated](/patterns-practices/reference/modulecatalog-ensurecatalogvalidated-method-mspp-modularity)</td>
<td><div class="summary">
Ensures that the catalog is validated.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetDependentModules](/patterns-practices/reference/modulecatalog-getdependentmodules-method-mspp-modularity)</td>
<td><div class="summary">
Return the list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s that <i>moduleInfo</i> depends on.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[GetDependentModulesInner](/patterns-practices/reference/modulecatalog-getdependentmodulesinner-method-mspp-modularity)</td>
<td><div class="summary">
Returns the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) on which the received module dependens on.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Initialize](/patterns-practices/reference/modulecatalog-initialize-method-mspp-modularity)</td>
<td><div class="summary">
Initializes the catalog, which may load and validate the modules.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InnerLoad](/patterns-practices/reference/modulecatalog-innerload-method-mspp-modularity)</td>
<td><div class="summary">
Does the actual work of loading the catalog. The base implementation does nothing.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Load](/patterns-practices/reference/modulecatalog-load-method-mspp-modularity)</td>
<td><div class="summary">
Loads the catalog if necessary.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[SolveDependencies](/patterns-practices/reference/modulecatalog-solvedependencies-method-mspp-modularity)</td>
<td><div class="summary">
Checks for cyclic dependencies, by calling the dependencysolver.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Sort](/patterns-practices/reference/modulecatalog-sort-method-mspp-modularity)</td>
<td><div class="summary">
Sorts a list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s. This method is called by [CompleteListWithDependencies(IEnumerable&lt;ModuleInfo&gt;)](/patterns-practices/reference/modulecatalog-completelistwithdependencies-method-mspp-modularity) to return a sorted list.
</div></td>
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
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ValidateCrossGroupDependencies](/patterns-practices/reference/modulecatalog-validatecrossgroupdependencies-method-mspp-modularity)</td>
<td><div class="summary">
Ensures that there are no dependencies between modules on different groups.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[ValidateDependencies](/patterns-practices/reference/modulecatalog-validatedependencies-method-mspp-modularity)</td>
<td><div class="summary">
Ensures that all the dependencies within <i>modules</i> refer to [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s within that list.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ValidateDependenciesInitializationMode](/patterns-practices/reference/modulecatalog-validatedependenciesinitializationmode-method-mspp-modularity)</td>
<td><div class="summary">
Ensures that there are no modules marked to be loaded [WhenAvailable](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity) depending on modules loaded [OnDemand](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity)
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ValidateDependencyGraph](/patterns-practices/reference/modulecatalog-validatedependencygraph-method-mspp-modularity)</td>
<td><div class="summary">
Ensures that there are no cyclic dependencies.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ValidateUniqueModules](/patterns-practices/reference/modulecatalog-validateuniquemodules-method-mspp-modularity)</td>
<td><div class="summary">
Makes sure all modules have an Unique name.
</div></td>
</tr>
</tbody>
</table>

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  