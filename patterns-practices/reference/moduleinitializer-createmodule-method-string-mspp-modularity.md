---
TOCTitle: 'CreateModule Method (String)'
Title: 'ModuleInitializer.CreateModule Method (String) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInitializer.CreateModule(System.String)'
ms:mtpsurl: 'moduleinitializer-createmodule-method-moduleinfo-mspp-modularity.md'
---


# ModuleInitializer.CreateModule Method (String)

Uses the container to resolve a new [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity) by specifying its [Type](http://msdn.microsoft.com/en-us/library/42892f65).

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual IModule CreateModule(
	string typeName
)
```

```VB
'Declaration
Protected Overridable Function CreateModule ( 
	typeName As String
) As IModule
```

### Parameters

*typeName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The type name to resolve. This type must implement [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity
).

### Return Value

Type: [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity)  
A new instance of *typeName*.

## See Also

[ModuleInitializer Class](/patterns-practices/reference/moduleinitializer-class-mspp-modularity)  
[ModuleInitializer Members](/patterns-practices/reference/moduleinitializer-members-mspp-modularity)  
[CreateModule Overload](/patterns-practices/reference/moduleinitializer-createmodule-method-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  