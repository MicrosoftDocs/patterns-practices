---
TOCTitle: InitializationMode Property
Title: 'ModuleInfoGroup.InitializationMode Property (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.InitializationMode'
ms:mtpsurl: 'moduleinfogroup-initializationmode-property-mspp-modularity.md'
---


# ModuleInfoGroup.InitializationMode Property

Gets or sets the [InitializationMode](/patterns-practices/reference/moduleinfo-initializationmode-property-mspp-modularity) for the whole group. Any [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) classes that are added after setting this value will also get this InitializationMode.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public InitializationMode InitializationMode { get; set; }
```

```VB
'Declaration
Public Property InitializationMode As InitializationMode
	Get
	Set
```
### Property Value

Type: [InitializationMode](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity)  
The initialization mode.

## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)  
[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)