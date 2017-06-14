---
TOCTitle: 'ClearErrors(TProperty) Method (Expression(Func(TProperty)))'
Title: 'ErrorsContainer(T).ClearErrors(TProperty) Method (Expression(Func(TProperty))) (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.ErrorsContainer\`1.ClearErrors\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}})'
ms:mtpsurl: 'errorscontainer-t-clearerrors-tproperty-method-expression-func-tproperty-mspp-viewmodel.md'
---


# ErrorsContainer&lt;T&gt;.ClearErrors&lt;TProperty&gt; Method (Expression&lt;Func&lt;TProperty&gt;&gt;)

Clears the errors for the property indicated by the property expression.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](/patterns-practices/reference/mspp-viewmodel-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public void ClearErrors<TProperty>(
	Expression<Func<TProperty>> propertyExpression
)
```

### Parameters

*propertyExpression*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)&lt;[Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;TProperty&gt;&gt;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The expression indicating a property.
	
### Type Parameters

*TProperty*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The property type.

## Examples

container.ClearErrors(()=&gt;SomeProperty);

## See Also

[ErrorsContainer&lt;T&gt; Class](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel)  
[ErrorsContainer&lt;T&gt; Members](/patterns-practices/reference/errorscontainer-t-members-mspp-viewmodel)  
[ClearErrors Overload](/patterns-practices/reference/errorscontainer-t-clearerrors-method-mspp-viewmodel)  
[Microsoft.Practices.Prism.ViewModel Namespace](/patterns-practices/reference/mspp-viewmodel-namespace)  


# ErrorsContainer(Of T).ClearErrors(Of TProperty) Method (Expression(Of Func(Of TProperty)))

Clears the errors for the property indicated by the property expression.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](/patterns-practices/reference/mspp-viewmodel-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Sub ClearErrors(Of TProperty) ( 
	propertyExpression As Expression(Of Func(Of TProperty))
)
```

### Parameters

*propertyExpression*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)(Of [Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of TProperty))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The expression indicating a property.

### Type Parameters

*TProperty*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The property type.

## Examples

container.ClearErrors(()=&gt;SomeProperty);

## See Also

[ErrorsContainer(Of T) Class](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel)  
[ErrorsContainer(Of T) Members](/patterns-practices/reference/errorscontainer-t-members-mspp-viewmodel)  
[ClearErrors Overload](/patterns-practices/reference/errorscontainer-t-clearerrors-method-mspp-viewmodel)  
[Microsoft.Practices.Prism.ViewModel Namespace](/patterns-practices/reference/mspp-viewmodel-namespace)  