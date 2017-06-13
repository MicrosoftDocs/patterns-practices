---
TOCTitle: FindAllValuesByKey Method
Title: 'ListDictionary(TKey, TValue).FindAllValuesByKey Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ListDictionary\`2.FindAllValuesByKey(System.Predicate{\`0})'
ms:mtpsurl: 'listdictionary-tkey-tvalue-findallvaluesbykey-method-mspp.md'
---

# ListDictionary&lt;TKey, TValue&gt;.FindAllValuesByKey Method 

Retrieves the all the elements from the list which have a key that matches the condition defined by the specified predicate.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public IEnumerable<TValue> FindAllValuesByKey(
	Predicate<TKey> keyFilter
)
```

### Parameters

_keyFilter_  
Type: [System.Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)&lt;[TKey](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)&gt;  
The filter with the condition to use to filter lists by their key.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[TValue](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)&gt;  
The elements that have a key that matches the condition defined by the specified predicate.

## See Also

[ListDictionary&lt;TKey, TValue&gt; Class](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)<br/>
[ListDictionary&lt;TKey, TValue&gt; Members](/patterns-practices/reference/listdictionary-tkey-tvalue-members-mspp)<br/>
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)<br/>

# ListDictionary(Of TKey, TValue).FindAllValuesByKey Method 

Retrieves the all the elements from the list which have a key that matches the condition defined by the specified predicate.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Function FindAllValuesByKey ( 
	keyFilter As Predicate(Of TKey)
) As IEnumerable(Of TValue)
```

### Parameters

_keyFilter_  
Type: [System.Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)(Of [TKey](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp))  
The filter with the condition to use to filter lists by their key.

### Return Value
Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [TValue](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp))  
The elements that have a key that matches the condition defined by the specified predicate.

## See Also

[ListDictionary(Of TKey, TValue) Class](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)<br/>
[ListDictionary(Of TKey, TValue) Members](/patterns-practices/reference/listdictionary-tkey-tvalue-members-mspp)<br/>
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)<br/>