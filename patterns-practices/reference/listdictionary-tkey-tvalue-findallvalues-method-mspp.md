---
TOCTitle: FindAllValues Method
Title: 'ListDictionary(TKey, TValue).FindAllValues Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ListDictionary\`2.FindAllValues(System.Predicate{\`1})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405802(v=PandP.50)'
---

Prism Class Library

ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;).FindAllValues Method
==========================================================================

Retrieves all the elements that match the condition defined by the specified predicate.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/n:microsoft.practices.prism)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public IEnumerable&lt;TValue&gt; FindAllValues( Predicate&lt;TValue&gt; valueFilter )Public Function FindAllValues ( valueFilter As Predicate(Of TValue) ) As IEnumerable(Of TValue)
#### Parameters

valueFilter  
Type: [System.Predicate](http://msdn2.microsoft.com/en-us/library/bfcke1bz)&lt;(Of &lt;([TValue](https://msdn.microsoft.com/t:microsoft.practices.prism.listdictionary%602)&gt;)&gt;)
The filter with the condition to use to filter values.

#### Return Value

Type: [IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([TValue](https://msdn.microsoft.com/t:microsoft.practices.prism.listdictionary%602)&gt;)&gt;)
The elements that match the condition defined by the specified predicate.

See Also
--------


[ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.listdictionary%602)

[ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.listdictionary%602)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
