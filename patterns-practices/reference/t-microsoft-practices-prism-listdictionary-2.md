---
TOCTitle: 'ListDictionary(TKey, TValue) Class'
Title: 'ListDictionary(TKey, TValue) Class (Microsoft.Practices.Prism)'
ms:assetid: 'T:Microsoft.Practices.Prism.ListDictionary\`2'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431434(v=PandP.50)'
---

Prism Class Library

ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;) Class
=======================================================

A dictionary of lists.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/n:microsoft.practices.prism)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public sealed class ListDictionary&lt;TKey, TValue&gt; : IDictionary&lt;TKey, IList&lt;TValue&gt;&gt;, ICollection&lt;KeyValuePair&lt;TKey, IList&lt;TValue&gt;&gt;&gt;, IEnumerable&lt;KeyValuePair&lt;TKey, IList&lt;TValue&gt;&gt;&gt;, IEnumerable Public NotInheritable Class ListDictionary(Of TKey, TValue) Implements IDictionary(Of TKey, IList(Of TValue)), ICollection(Of KeyValuePair(Of TKey, IList(Of TValue))), IEnumerable(Of KeyValuePair(Of TKey, IList(Of TValue))), IEnumerable
Type Parameters
---------------

<span id="templatesToggle"></span>
TKey  
The key to use for lists.

TValue  
The type of the value held by lists.

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System..::.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
  Microsoft.Practices.Prism..::.ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;)

See Also
--------

<span id="seeAlsoToggle"></span>
[ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.listdictionary%602)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
