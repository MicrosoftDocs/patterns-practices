---
TOCTitle: 'ExtractPropertyName(T) Method'
Title: 'PropertySupport.ExtractPropertyName(T) Method (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.PropertySupport.ExtractPropertyName\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736209(v=PandP.50)'
---


# PropertySupport.ExtractPropertyName&lt;(Of &lt;(T&gt;)&gt;) Method

Extracts the property name from a property expression.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](https://msdn.microsoft.com/library/microsoft.practices.prism.mvvm)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

public static string ExtractPropertyName&lt;T&gt;( Expression&lt;Func&lt;T&gt;&gt; propertyExpression ) Public Shared Function ExtractPropertyName(Of T) ( propertyExpression As Expression(Of Func(Of T)) ) As String

### Parameters

propertyExpression  
Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)&lt;(Of &lt;([Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;(Of &lt;(T&gt;)&gt;)&gt;)&gt;)
The property expression (e.g. p =&gt; p.PropertyName)

## Type Parameters

<span id="templatesToggle"></span>
T  
The object type containing the property specified in the expression.

### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The name of the property.

## Exceptions

<span id="exceptionsToggle"></span>
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

[PropertySupport Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mvvm.propertysupport)

[PropertySupport Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mvvm.propertysupport)

[Microsoft.Practices.Prism.Mvvm Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mvvm)
