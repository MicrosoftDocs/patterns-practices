---
TOCTitle: 'SetErrors(TProperty) Method (Expression(Func(TProperty)), IEnumerable(T))'
Title: 'ErrorsContainer(T).SetErrors(TProperty) Method (Expression(Func(TProperty)), IEnumerable(T)) (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.ErrorsContainer\`1.SetErrors\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}},System.Collections.Generic.IEnumerable{\`0})'
ms:mtpsurl: 'errorscontainer-t-seterrors-tproperty-method-expression-func-tproperty-ienumerable-t-mspp-viewmodel.md'
---

# ErrorsContainer&lt;T&gt;.SetErrors&lt;TProperty&gt; Method (Expression&lt;Func&lt;TProperty&gt;&gt;, IEnumerable&lt;T&gt;)

Sets the validation errors for the specified property.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](/patterns-practices/reference/mspp-viewmodel-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public void SetErrors<TProperty>(
	Expression<Func<TProperty>> propertyExpression,
	IEnumerable<T> propertyErrors
)
```

### Parameters

*propertyExpression*  

Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)&lt;[Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;TProperty&gt;&gt;

The [Expression](http://msdn.microsoft.com/en-us/library/bb356138) indicating the property.

*propertyErrors*  

Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[T](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel)&gt;

The list of errors to set for the property.

## Type Parameters

*TProperty*

The property type for which to set errors.

## See Also

[ErrorsContainer&lt;T&gt; Class](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel)

[ErrorsContainer&lt;T&gt; Members](/patterns-practices/reference/errorscontainer-t-members-mspp-viewmodel)

[SetErrors Overload](/patterns-practices/reference/errorscontainer-t-seterrors-method-mspp-viewmodel)

[Microsoft.Practices.Prism.ViewModel Namespace](/patterns-practices/reference/mspp-viewmodel-namespace)


# ErrorsContainer(Of T).SetErrors(Of TProperty) Method (Expression(Of Func(Of TProperty)), IEnumerable(Of T))

Sets the validation errors for the specified property.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](/patterns-practices/reference/mspp-viewmodel-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Sub SetErrors(Of TProperty) ( 
	propertyExpression As Expression(Of Func(Of TProperty)),
	propertyErrors As IEnumerable(Of T)
)
```

### Parameters

*propertyExpression*  

Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)(Of [Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of TProperty))

The [Expression](http://msdn.microsoft.com/en-us/library/bb356138) indicating the property.

*propertyErrors*  

Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [T](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel))

The list of errors to set for the property.

## Type Parameters

*TProperty*

The property type for which to set errors.

## See Also

[ErrorsContainer(Of T) Class](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel)

[ErrorsContainer(Of T) Members](/patterns-practices/reference/errorscontainer-t-members-mspp-viewmodel)

[SetErrors Overload](/patterns-practices/reference/errorscontainer-t-seterrors-method-mspp-viewmodel)

[Microsoft.Practices.Prism.ViewModel Namespace](/patterns-practices/reference/mspp-viewmodel-namespace)

