---
TOCTitle: Items Property
Title: 'ModuleCatalog.Items Property (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.Modularity.ModuleCatalog.Items'
ms:mtpsurl: 'modulecatalog-items-property-mspp-modularity.md'
---

# ModuleCatalog.Items Property

Gets the items in the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity). This property is mainly used to add [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)s or [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s through XAML.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public Collection<IModuleCatalogItem> Items { get; }
```

### Property Value

Type: [Collection](http://msdn.microsoft.com/en-us/library/ms132397)&lt;[IModuleCatalogItem](/patterns-practices/reference/imodulecatalogitem-interface-mspp-modularity)&gt;
The items in the catalog

```VB
'Declaration
Public ReadOnly Property Items As Collection(Of IModuleCatalogItem)
	Get
```

### Property Value

Type: [Collection](http://msdn.microsoft.com/en-us/library/ms132397)(Of [IModuleCatalogItem](/patterns-practices/reference/imodulecatalogitem-interface-mspp-modularity))  
The items in the catalog.

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  