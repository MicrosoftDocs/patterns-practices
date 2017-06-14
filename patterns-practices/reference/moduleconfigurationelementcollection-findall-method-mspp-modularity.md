---
TOCTitle: FindAll Method
Title: 'ModuleConfigurationElementCollection.FindAll Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleConfigurationElementCollection.FindAll(System.Predicate{Microsoft.Practices.Prism.Modularity.ModuleConfigurationElement})'
ms:mtpsurl: 'moduleconfigurationelementcollection-findall-method-mspp-modularity.md'
---

# ModuleConfigurationElementCollection.FindAll Method

Searches the collection for all the [ModuleConfigurationElement](/patterns-practices/reference/moduleconfigurationelement-class-mspp-modularity) that match the specified predicate.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public IList<ModuleConfigurationElement> FindAll(
	Predicate<ModuleConfigurationElement> match
)
```
### Parameters

match  
Type: [System.Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)&lt;[ModuleConfigurationElement](/patterns-practices/reference/moduleconfigurationelement-class-mspp-modularity)&gt;   
A [Predicate&lt;T&gt;](http://msdn.microsoft.com/en-us/library/bfcke1bz) that implements the match test.

### Return Value

Type: [IList](http://msdn.microsoft.com/en-us/library/5y536ey6)&lt;[ModuleConfigurationElement](/patterns-practices/reference/moduleconfigurationelement-class-mspp-modularity)&gt;   
A [List&lt;T&gt;](http://msdn.microsoft.com/en-us/library/6sh2ey19) with the successful matches.


```VB
'Declaration
Public Function FindAll ( 
	match As Predicate(Of ModuleConfigurationElement)
) As IList(Of ModuleConfigurationElement)
```

### Parameters

match  
Type: [System.Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)(Of [ModuleConfigurationElement](/patterns-practices/reference/moduleconfigurationelement-class-mspp-modularity))   
A [Predicate(Of T)](http://msdn.microsoft.com/en-us/library/bfcke1bz) that implements the match test.

### Return Value

Type: [IList](http://msdn.microsoft.com/en-us/library/5y536ey6)(Of [ModuleConfigurationElement](/patterns-practices/reference/moduleconfigurationelement-class-mspp-modularity))  
A [List(Of T)](http://msdn.microsoft.com/en-us/library/6sh2ey19) with the successful matches.

## Exceptions


| Exception                                                                             | Condition                                                                                                 |
|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) is thrown if *match* is null. |

## See Also

[ModuleConfigurationElementCollection Class](/patterns-practices/reference/moduleconfigurationelementcollection-class-mspp-modularity)  
[ModuleConfigurationElementCollection Members](/patterns-practices/reference/moduleconfigurationelementcollection-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)