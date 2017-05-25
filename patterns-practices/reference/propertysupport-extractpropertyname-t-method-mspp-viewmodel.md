---
TOCTitle: 'ExtractPropertyName(T) Method'
Title: 'PropertySupport.ExtractPropertyName(T) Method (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.PropertySupport.ExtractPropertyName\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg406219(v=PandP.50)'
---

# PropertySupport.ExtractPropertyName&lt;T&gt; Method

Extracts the property name from a property expression.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static string ExtractPropertyName<T>(
	Expression<Func<T>> propertyExpression
)
```

### Parameters

*propertyExpression* 

Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)&lt;[Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;T&gt;&gt;

The property expression (e.g. p =&gt; p.PropertyName)

### Type Parameters

*T*
 
  The object type containing the property specified in the expression.

### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

The name of the property.

## Exceptions

<table>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://msdn.microsoft.com/en-us/library/27426hcy">System.ArgumentNullException</a></td>
<td>Thrown if the propertyExpression is null.</td>
</tr>
<tr class="even">
<td><a href="http://msdn.microsoft.com/en-us/library/3w1b3114">System.ArgumentException</a></td>
<td>Thrown when the expression is:<br />
Not a <a href="http://msdn.microsoft.com/en-us/library/bb353260">MemberExpression</a><br />
The <a href="http://msdn.microsoft.com/en-us/library/bb353260">MemberExpression</a> does not represent a property.<br />
Or, the property is static.</td>
</tr>
</tbody>
</table>

## See Also

[PropertySupport Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel.propertysupport(v=pandp.50))

[PropertySupport Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel.propertysupport_members(v=pandp.50))

[Microsoft.Practices.Prism.ViewModel Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel(v=pandp.50))

# PropertySupport.ExtractPropertyName(Of T) Method

Extracts the property name from a property expression.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Shared Function ExtractPropertyName(Of T) ( 
	propertyExpression As Expression(Of Func(Of T))
) As String
```

### Parameters

*propertyExpression*
 
Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)(Of [Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of T))

The property expression (e.g. p =&gt; p.PropertyName)

### Type Parameters

*T* 

The object type containing the property specified in the expression.

### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The name of the property.

## Exceptions

<table>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://msdn.microsoft.com/en-us/library/27426hcy">System.ArgumentNullException</a></td>
<td>Thrown if the propertyExpression is null.</td>
</tr>
<tr class="even">
<td><a href="http://msdn.microsoft.com/en-us/library/3w1b3114">System.ArgumentException</a></td>
<td>Thrown when the expression is:<br />
Not a <a href="http://msdn.microsoft.com/en-us/library/bb353260">MemberExpression</a><br />
The <a href="http://msdn.microsoft.com/en-us/library/bb353260">MemberExpression</a> does not represent a property.<br />
Or, the property is static.</td>
</tr>
</tbody>
</table>

## See Also

[PropertySupport Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel.propertysupport(v=pandp.50))

[PropertySupport Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel.propertysupport_members(v=pandp.50))

[Microsoft.Practices.Prism.ViewModel Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel(v=pandp.50))
