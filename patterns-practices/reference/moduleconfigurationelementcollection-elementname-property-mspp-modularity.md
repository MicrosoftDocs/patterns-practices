---
TOCTitle: ElementName Property
Title: 'ModuleConfigurationElementCollection.ElementName Property (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.Modularity.ModuleConfigurationElementCollection.ElementName'
ms:mtpsurl: 'moduleconfigurationelementcollection-elementname-property-mspp-modularity.md'
---


# ModuleConfigurationElementCollection.ElementName Property

Gets the name used to identify this collection of elements in the configuration file when overridden in a derived class.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
    protected override string ElementName { get; }
```
```VB
'Declaration
Protected Overrides ReadOnly Property ElementName As String
	Get
```
### Property Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

The name of the collection; otherwise, an empty string.

## See Also

[ModuleConfigurationElementCollection Class](/patterns-practices/reference/moduleconfigurationelementcollection-class-mspp-modularity)  
[ModuleConfigurationElementCollection Members](/patterns-practices/reference/moduleconfigurationelementcollection-members-mspp-modularity) 
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  
