---
TOCTitle: Contains Method
Title: 'ModuleConfigurationElementCollection.Contains Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleConfigurationElementCollection.Contains(System.String)'
ms:mtpsurl: 'moduleconfigurationelementcollection-contains-method-mspp-modularity.md'
---

# ModuleConfigurationElementCollection.Contains Method

Tests if the collection contains the configuration for the specified module name.

**Namespace:** [Microsoft.Practices.Prism.Modularity](mspp-modularity-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public bool Contains(
	string moduleName
)
```

```VB
'Declaration
Public Function Contains ( 
	moduleName As String
) As Boolean
```


### Parameters

*moduleName*

  &nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
  &nbsp;&nbsp;&nbsp;&nbsp;The name of the module to search the configuration for.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)<br/>
**Truetrue** (**True** in Visual Basic) if a configuration for the module is present; otherwise **Falsefalse** (**False** in Visual Basic).

## See Also

[ModuleConfigurationElementCollection Class](moduleconfigurationelementcollection-class-mspp-modularity.md)

[ModuleConfigurationElementCollection Members](moduleconfigurationelementcollection-members-mspp-modularity.md)

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace.md)