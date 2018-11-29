---
TOCTitle: AddGroup Method
Title: 'ModuleCatalog.AddGroup Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.AddGroup(Microsoft.Practices.Prism.Modularity.InitializationMode,System.String,Microsoft.Practices.Prism.Modularity.ModuleInfo[])'
ms:mtpsurl: 'modulecatalog-addgroup-method-mspp-modularity.md'
---

# ModuleCatalog.AddGroup Method

Creates and adds a [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) to the catalog.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public virtual ModuleCatalog AddGroup(
	InitializationMode initializationMode,
	string refValue,
	params ModuleInfo[] moduleInfos
)
```

### Parameters

*initializationMode*  
Type: [Microsoft.Practices.Prism.Modularity.InitializationMode](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity)  
Stage on which the module group to be added will be initialized.

*refValue*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
Reference to the location of the module group to be added.

*moduleInfos*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)[]  
Collection of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) included in the group.


```VB
'Declaration
Public Overridable Function AddGroup ( 
	initializationMode As InitializationMode,
	refValue As String,
	ParamArray moduleInfos As ModuleInfo()
) As ModuleCatalog
```

### Parameters

*initializationMode*  
Type: [Microsoft.Practices.Prism.Modularity.InitializationMode](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity)  
Stage on which the module group to be added will be initialized.

*refValue*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
Reference to the location of the module group to be added.

*moduleInfos*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)()  
Collection of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) included in the group.

### Return Value

Type: [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) with the added module group.

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  

