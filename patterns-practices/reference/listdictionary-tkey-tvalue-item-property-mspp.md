---
TOCTitle: Item Property
Title: 'ListDictionary(TKey, TValue).Item Property (Microsoft.Practices.Prism)'
ms:assetid: 'P:Microsoft.Practices.Prism.ListDictionary\`2.Item(\`0)'
ms:mtpsurl: 'listdictionary-tkey-tvalue-item-property-mspp.md'
---

# ListDictionary&lt;TKey, TValue&gt;.Item Property

Gets or sets the list associated with the given key. The access always succeeds, eventually returning an empty list.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public IList<TValue> this[
	TKey key
] { get; set; }
```

### Parameters

*key*    
Type: [TKey](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)  
The key of the list to access.

### Return Value

Type: [IList](http://msdn.microsoft.com/en-us/library/5y536ey6)&lt;[TValue](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)&gt;  
The list associated with the key.

### Implements

[IDictionary&lt;TKey, TValue&gt;.Item[TKey]](http://msdn.microsoft.com/en-us/library/zyxt2e2h)

## See Also

[ListDictionary&lt;TKey, TValue&gt; Class](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)<br/>
[ListDictionary&lt;TKey, TValue&gt; Members](/patterns-practices/reference/listdictionary-tkey-tvalue-members-mspp)<br/>
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)<br/>

# ListDictionary(Of TKey, TValue).Item Property

Gets or sets the list associated with the given key. The access always succeeds, eventually returning an empty list.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Default Property Item ( 
	key As TKey
) As IList(Of TValue)
	Get
	Set
```

### Parameters

*key*    
Type: [TKey](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)  
The key of the list to access.

### Return Value

Type: [IList](http://msdn.microsoft.com/en-us/library/5y536ey6)(Of[TValue](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp))  
The list associated with the key.

### Implements

[IDictionary(Of TKey, TValue).Item(TKey)](http://msdn.microsoft.com/en-us/library/zyxt2e2h)

## See Also

[ListDictionary(Of TKey, TValue) Class](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)<br/>
[ListDictionary(Of TKey, TValue) Members](/patterns-practices/reference/listdictionary-tkey-tvalue-members-mspp)<br/>
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)<br/>