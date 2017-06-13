---
TOCTitle: GrouplessModules Property
Title: 'ModuleCatalog.GrouplessModules Property (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.Modularity.ModuleCatalog.GrouplessModules'
ms:mtpsurl: 'modulecatalog-grouplessmodules-property-mspp-modularity.md'
---

# ModuleCatalog.GrouplessModules Property

Returns the list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s that are not contained within any [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity).

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected IEnumerable<ModuleInfo> GrouplessModules { get; }
```

### Property Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)&gt;
The groupless modules.

```VB
'Declaration
Protected ReadOnly Property GrouplessModules As IEnumerable(Of ModuleInfo)
	Get
```
### Property Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity))
The groupless modules.

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)<br/>
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>