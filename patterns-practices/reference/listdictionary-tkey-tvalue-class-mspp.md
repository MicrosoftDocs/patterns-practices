---
TOCTitle: 'ListDictionary(TKey, TValue) Class'
Title: 'ListDictionary(TKey, TValue) Class (Microsoft.Practices.Prism)'
ms:assetid: 'T:Microsoft.Practices.Prism.ListDictionary\`2'
ms:mtpsurl: 'listdictionary-tkey-tvalue-class-mspp.md'
---


# ListDictionary<TKey, TValue> Class

A dictionary of lists.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public sealed class ListDictionary<TKey, TValue> : IDictionary<TKey, IList<TValue>>, 
	ICollection<KeyValuePair<TKey, IList<TValue>>>, IEnumerable<KeyValuePair<TKey, IList<TValue>>>, 
	IEnumerable
```

### Type Parameters

*TKey*
	
	The key to use for lists.
	
*TValue*
       	
	The type of the value held by lists.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
    Microsoft.Practices.Prism.ListDictionary<TKey, TValue>

## See Also
[ListDictionary<TKey, TValue> Members](/patterns-practices/reference/listdictionary-tkey-tvalue-members-mspp)  
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)<br/>    

# ListDictionary(Of TKey, TValue) Class

A dictionary of lists.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public NotInheritable Class ListDictionary(Of TKey, TValue)
	Implements IDictionary(Of TKey, IList(Of TValue)), 
	ICollection(Of KeyValuePair(Of TKey, IList(Of TValue))), 
	IEnumerable(Of KeyValuePair(Of TKey, IList(Of TValue))), 
	IEnumerable
```

### Type Parameters

*TKey*
	
	The key to use for lists.
	
*TValue*
       	
	The type of the value held by lists.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  Microsoft.Practices.Prism.ListDictionary(Of TKey, TValue)
  

## See Also

[ListDictionary(Of TKey, TValue) Members](/patterns-practices/reference/listdictionary-tkey-tvalue-members-mspp)  
 [Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)<br/>