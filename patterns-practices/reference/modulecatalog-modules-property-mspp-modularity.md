---
TOCTitle: Modules Property
Title: 'ModuleCatalog.Modules Property (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.Modularity.ModuleCatalog.Modules'
ms:mtpsurl: 'modulecatalog-modules-property-mspp-modularity.md'
---

# ModuleCatalog.Modules Property

Gets all the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) classes that are in the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity), regardless if they are within a [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) or not.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public virtual IEnumerable<ModuleInfo> Modules { get; }
```

### Property Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)&gt;  
The modules.

### Implements

[IModuleCatalog.Modules](/patterns-practices/reference/imodulecatalog-modules-property-mspp-modularity)

```VB
'Declaration
Public Overridable ReadOnly Property Modules As IEnumerable(Of ModuleInfo)
	Get
```

### Property Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity))  
The modules.

### Implements

[IModuleCatalog.Modules](/patterns-practices/reference/imodulecatalog-modules-property-mspp-modularity)

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)<br/>
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>