---
TOCTitle: Ref Property
Title: 'ModuleInfoGroup.Ref Property (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.Ref'
ms:mtpsurl: 'moduleinfogroup-ref-property-mspp-modularity.md'
---


# ModuleInfoGroup.Ref Property

Gets or sets the [Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity) value for the whole group. Any [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  classes that are added after setting this value will also get this Ref. The ref value will also be used by the [IModuleManager](/patterns-practices/reference/imodulemanager-interface-mspp-modularity) to determine which [IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity) to use. For example, using an "file://" prefix with a valid URL will cause the FileModuleTypeLoader to be used (Only available in the desktop version of CAL).

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public string Ref { get; set; }
```

```VB
'Declaration
Public Property Ref As String
	Get
	Set
```

### Property Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The ref value that will be used.

## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)  
[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  