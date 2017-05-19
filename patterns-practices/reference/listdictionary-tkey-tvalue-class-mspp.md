---
TOCTitle: 'ListDictionary(TKey, TValue) Class'
Title: 'ListDictionary(TKey, TValue) Class (Microsoft.Practices.Prism)'
ms:assetid: 'T:Microsoft.Practices.Prism.ListDictionary\`2'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431434(v=PandP.50)'
---

Prism Class Library

# ListDictionary<TKey, TValue> Class

A dictionary of lists.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism(v=pandp.50))

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

[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)<br/>
    Microsoft.Practices.Prism.ListDictionary<TKey, TValue>

## See Also
[ListDictionary<TKey, TValue> Members](https://msdn.microsoft.com/en-us/library/gg430787(v=pandp.50))<br/>
[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism(v=pandp.50))
    

# ListDictionary(Of TKey, TValue) Class

A dictionary of lists.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism(v=pandp.50))

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

[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)<br/>
  Microsoft.Practices.Prism.ListDictionary(Of TKey, TValue)
  

## See Also

[ListDictionary(Of TKey, TValue) Members](https://msdn.microsoft.com/en-us/library/gg430787(v=pandp.50))<br/>
 [Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism(v=pandp.50))
