---
TOCTitle: 'AddRange(T) Method'
Title: 'CollectionExtensions.AddRange(T) Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.CollectionExtensions.AddRange\`\`1(System.Collections.ObjectModel.Collection{\`\`0},System.Collections.Generic.IEnumerable{\`\`0})'
ms:mtpsurl: 'collectionextensions-addrange-t-method-mspp.md'
---

# CollectionExtensions.AddRange&lt;T&gt; Method

Add a range of items to a collection.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static Collection<T> AddRange<T>(
	this Collection<T> collection,
	IEnumerable<T> items
)
```
### Parameters

*collection*

Type: [System.Collections.ObjectModel.Collection](http://msdn.microsoft.com/en-us/library/ms132397)&lt;T&gt;

The collection to add items to.

*items*

Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;T&gt;

The items to add to the collection.

### Type Parameters

*T*

Type of objects within the collection.

### Return Value

Type: [Collection](http://msdn.microsoft.com/en-us/library/ms132397)&lt;T&gt;

The collection.

### Usage Note

In Visual Basic and C#, you can call this method as an instance method on any object of type [Collection](http://msdn.microsoft.com/en-us/library/ms132397)&lt;T&gt;. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## Exceptions

<table style="width:100%;">
<tr>
<th>Exception</th>
<th>Condition</th>
</tr>
<tr>
<td>[System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)</td>
<td>An [ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) is thrown if <em>collection</em> or <em>items</em> is <strong>null</strong>a null reference (<strong>Nothing</strong> in Visual Basic).</td>
</tr>
</table>

# CollectionExtensions.AddRange(Of T) Method

Add a range of items to a collection.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
<ExtensionAttribute> 
Public Shared Function AddRange(Of T) ( 
	collection As Collection(Of T),
	items As IEnumerable(Of T)
) As Collection(Of T)
```

### Parameters

*collection*  

Type: [System.Collections.ObjectModel.Collection](http://msdn.microsoft.com/en-us/library/ms132397)(Of T)

The collection to add items to.

*items*  

Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of T)

The items to add to the collection.

### Type Parameters

*T* 

Type of objects within the collection.

### Return Value

Type: [Collection](http://msdn.microsoft.com/en-us/library/ms132397)(Of T)

The collection.

### Usage Note

In Visual Basic and C#, you can call this method as an instance method on any object of type [Collection](http://msdn.microsoft.com/en-us/library/ms132397)(Of T). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## Exceptions

<table style="width:100%;">
<tr>
<th>Exception</th>
<th>Condition</th>
</tr>
<tr>
<td>[System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)</td>
<td>An [ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) is thrown if <em>collection</em> or <em>items</em> is <strong>Nothing</strong>a null reference (<strong>Nothing</strong> in Visual Basic).</td>
</tr>
</table>

## See Also

[CollectionExtensions Class](/patterns-practices/reference/collectionextensions-class-mspp)<br/>
[CollectionExtensions Members](/patterns-practices/reference/collectionextensions-members-mspp)<br/>
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)<br/>