---
TOCTitle: FindAllValuesByKey Method
Title: 'ListDictionary(TKey, TValue).FindAllValuesByKey Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ListDictionary\`2.FindAllValuesByKey(System.Predicate{\`0})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405801(v=PandP.50)'
---

Prism Class Library

ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;)..::.FindAllValuesByKey Method
===============================================================================

Retrieves the all the elements from the list which have a key that matches the condition defined by the specified predicate.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/n:microsoft.practices.prism)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public IEnumerable&lt;TValue&gt; FindAllValuesByKey( Predicate&lt;TKey&gt; keyFilter )Public Function FindAllValuesByKey ( keyFilter As Predicate(Of TKey) ) As IEnumerable(Of TValue)
#### Parameters

keyFilter  
Type: [System..::.Predicate](http://msdn2.microsoft.com/en-us/library/bfcke1bz)&lt;(Of &lt;([TKey](https://msdn.microsoft.com/t:microsoft.practices.prism.listdictionary%602)&gt;)&gt;)
The filter with the condition to use to filter lists by their key.

#### Return Value

Type: [IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([TValue](https://msdn.microsoft.com/t:microsoft.practices.prism.listdictionary%602)&gt;)&gt;)
The elements that have a key that matches the condition defined by the specified predicate.

See Also
--------

<span id="seeAlsoToggle"></span>
[ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.listdictionary%602)

[ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.listdictionary%602)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
