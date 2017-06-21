---
TOCTitle: ModuleInfoGroup Class
Title: 'ModuleInfoGroup Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup'
ms:mtpsurl: 'moduleinfogroup-class-mspp-modularity.md'
---


# ModuleInfoGroup Class

Represents a group of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) instances that are usually deployed together. ModuleInfoGroups are also used by the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) to prevent common deployment problems such as having a module that's required at startup that depends on modules that will only be downloaded on demand. The group also forwards [Ref](/patterns-practices/reference/moduleinfogroup-ref-property-mspp-modularity) and [InitializationMode](/patterns-practices/reference/moduleinfogroup-initializationmode-property-mspp-modularity) values to the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s that it contains.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class ModuleInfoGroup : IModuleCatalogItem, 
	IList<ModuleInfo>, ICollection<ModuleInfo>, IEnumerable<ModuleInfo>, 
	IList, ICollection, IEnumerable
```

```VB
'Declaration
Public Class ModuleInfoGroup
	Implements IModuleCatalogItem, IList(Of ModuleInfo), 
	ICollection(Of ModuleInfo), IEnumerable(Of ModuleInfo), IList, 
	ICollection, IEnumerable
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  Microsoft.Practices.Prism.Modularity.ModuleInfoGroup

## See Also

[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  