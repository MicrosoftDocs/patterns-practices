---
TOCTitle: 'ExtractPropertyName(T) Method'
Title: 'PropertySupport.ExtractPropertyName(T) Method (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.PropertySupport.ExtractPropertyName\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}})'
ms:mtpsurl: 'propertysupport-extractpropertyname-t-method-mspp-mvvm.md'
---


# PropertySupport.ExtractPropertyName&lt;T&gt; Method

Extracts the property name from a property expression.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public static string ExtractPropertyName<T>(
	Expression<Func<T>> propertyExpression
)
```

#### Parameters

*propertyExpression*  
Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)&lt;[Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;T&gt;&gt;  
The property expression (e.g. p =&gt; p.PropertyName)

### Type Parameters

*T*  
The object type containing the property specified in the expression.

#### Return Value

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
<td>[System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)</td>
<td>Thrown if the <i>propertyExpression</i> is null.</td>
</tr>
<tr class="even">
<td>[System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)</td>
<td>Thrown when the expression is:<br />
Not a [MemberExpression](http://msdn.microsoft.com/en-us/library/bb353260)<br />
The [MemberExpression](http://msdn.microsoft.com/en-us/library/bb353260) does not represent a property.<br />
Or, the property is static.</td>
</tr>
</tbody>
</table>

## See Also

[PropertySupport Class](/patterns-practices/reference/propertysupport-class-mspp-mvvm)  
[PropertySupport Members](/patterns-practices/reference/propertysupport-members-mspp-mvvm)  
[Microsoft.Practices.Prism.Mvvm Namespace](/patterns-practices/reference/mspp-mvvm-namespace)  



# PropertySupport.ExtractPropertyName(Of T) Method

Extracts the property name from a property expression.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Shared Function ExtractPropertyName(Of T) ( 
	propertyExpression As Expression(Of Func(Of T))
) As String
```

#### Parameters

*propertyExpression*  
Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)(Of [Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of T))  
The property expression (e.g. p =&gt; p.PropertyName)

### Type Parameters

*T*  
The object type containing the property specified in the expression.

#### Return Value

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
<td>[System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)</td>
<td>Thrown if the <i>propertyExpression</i> is null.</td>
</tr>
<tr class="even">
<td>[System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)</td>
<td>Thrown when the expression is:<br />
Not a [MemberExpression](http://msdn.microsoft.com/en-us/library/bb353260)<br />
The [MemberExpression](http://msdn.microsoft.com/en-us/library/bb353260) does not represent a property.<br />
Or, the property is static.</td>
</tr>
</tbody>
</table>

## See Also	

[PropertySupport Class](/patterns-practices/reference/propertysupport-class-mspp-mvvm)  
[PropertySupport Members](/patterns-practices/reference/propertysupport-members-mspp-mvvm)  
[Microsoft.Practices.Prism.Mvvm Namespace](/patterns-practices/reference/mspp-mvvm-namespace)  