---
TOCTitle: Item Property
Title: 'ListDictionary(TKey, TValue).Item Property (Microsoft.Practices.Prism)'
ms:assetid: 'P:Microsoft.Practices.Prism.ListDictionary\`2.Item(\`0)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431256(v=PandP.50)'
---

Prism Class Library

ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;).Item Property
===================================================================

Gets or sets the list associated with the given key. The access always succeeds, eventually returning an empty list.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/n:microsoft.practices.prism)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public IList&lt;TValue&gt; this[ TKey key \] { get; set; }Public Default Property Item ( key As TKey ) As IList(Of TValue) Get Set
#### Parameters

key  
Type: [TKey](https://msdn.microsoft.com/t:microsoft.practices.prism.listdictionary%602)
The key of the list to access.

#### Return Value

Type: [IList](http://msdn2.microsoft.com/en-us/library/5y536ey6)&lt;(Of &lt;([TValue](https://msdn.microsoft.com/t:microsoft.practices.prism.listdictionary%602)&gt;)&gt;)
The list associated with the key.
#### Implements

[IDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;).Item[([(TKey\])\])](http://msdn2.microsoft.com/en-us/library/zyxt2e2h)

See Also
--------


[ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.listdictionary%602)

[ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.listdictionary%602)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
