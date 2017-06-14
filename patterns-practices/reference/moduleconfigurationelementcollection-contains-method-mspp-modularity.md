---
TOCTitle: Contains Method
Title: 'ModuleConfigurationElementCollection.Contains Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleConfigurationElementCollection.Contains(System.String)'
ms:mtpsurl: 'moduleconfigurationelementcollection-contains-method-mspp-modularity.md'
---

# ModuleConfigurationElementCollection.Contains Method

Tests if the collection contains the configuration for the specified module name.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public bool Contains(
	string moduleName
)
```

### Parameters

*moduleName*

Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

The name of the module to search the configuration for.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

**truetrue** (**True** in Visual Basic) if a configuration for the module is present; otherwise **falsefalse** (**False** in Visual Basic).



```VB
'Declaration
Public Function Contains ( 
	moduleName As String
) As Boolean
```

### Parameters

*moduleName*

Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

The name of the module to search the configuration for.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

**Truetrue** (**True** in Visual Basic) if a configuration for the module is present; otherwise **Falsefalse** (**False** in Visual Basic).

## See Also

[ModuleConfigurationElementCollection Class](/patterns-practices/reference/moduleconfigurationelementcollection-class-mspp-modularity)<br/>
[ModuleConfigurationElementCollection Members](/patterns-practices/reference/moduleconfigurationelementcollection-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)