---
TOCTitle: FindAll Method
Title: 'ModuleConfigurationElementCollection.FindAll Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleConfigurationElementCollection.FindAll(System.Predicate{Microsoft.Practices.Prism.Modularity.ModuleConfigurationElement})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405895(v=PandP.50)'
---

Prism Class Library

ModuleConfigurationElementCollection.FindAll Method
=======================================================

Searches the collection for all the [ModuleConfigurationElement](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleconfigurationelement) that match the specified predicate.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public IList&lt;ModuleConfigurationElement&gt; FindAll( Predicate&lt;ModuleConfigurationElement&gt; match )Public Function FindAll ( match As Predicate(Of ModuleConfigurationElement) ) As IList(Of ModuleConfigurationElement)
#### Parameters

match  
Type: [System.Predicate](http://msdn2.microsoft.com/en-us/library/bfcke1bz)&lt;(Of &lt;([ModuleConfigurationElement](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleconfigurationelement)&gt;)&gt;)
A [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/bfcke1bz) that implements the match test.

#### Return Value

Type: [IList](http://msdn2.microsoft.com/en-us/library/5y536ey6)&lt;(Of &lt;([ModuleConfigurationElement](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleconfigurationelement)&gt;)&gt;)
A [List&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/6sh2ey19) with the successful matches.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                                                 |
|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) is thrown if match is null. |

See Also
--------


[ModuleConfigurationElementCollection Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleconfigurationelementcollection)

[ModuleConfigurationElementCollection Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleconfigurationelementcollection)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
