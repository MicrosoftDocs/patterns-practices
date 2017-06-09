---
TOCTitle: FindAllValues Method
Title: 'ListDictionary(TKey, TValue).FindAllValues Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ListDictionary\`2.FindAllValues(System.Predicate{\`1})'
ms:mtpsurl: 'listdictionary-tkey-tvalue-findallvalues-method-mspp.md'
---
# ListDictionary&lt;TKey, TValue&gt;.FindAllValues Method 

Retrieves all the elements that match the condition defined by the specified predicate.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public IEnumerable<TValue> FindAllValues(
	Predicate<TValue> valueFilter
)
```

### Parameters

_valueFilter_  
Type: [System.Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)&lt;[TValue](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)&gt;  
The filter with the condition to use to filter values.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[TValue](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)&gt;  
The elements that match the condition defined by the specified predicate.

## See Also

[ListDictionary&lt;TKey, TValue&gt; Class](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)

[ListDictionary&lt;TKey, TValue&gt; Members](/patterns-practices/reference/listdictionary-tkey-tvalue-members-mspp)

[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)


# ListDictionary(Of TKey, TValue).FindAllValues Method

Retrieves all the elements that match the condition defined by the specified predicate.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Function FindAllValues ( 
	valueFilter As Predicate(Of TValue)
) As IEnumerable(Of TValue)
```

### Parameters

_valueFilter_  
Type: [System.Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)(Of [TValue](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp))  
The filter with the condition to use to filter values.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [TValue](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp))  
The elements that match the condition defined by the specified predicate.

## See Also

[ListDictionary(Of TKey, TValue) Class](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)

[ListDictionary(Of TKey, TValue) Members](/patterns-practices/reference/listdictionary-tkey-tvalue-members-mspp)

[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)
