---
TOCTitle: 'ClearErrors(TProperty) Method (Expression(Func(TProperty)))'
Title: 'ErrorsContainer(T).ClearErrors(TProperty) Method (Expression(Func(TProperty))) (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.ErrorsContainer\`1.ClearErrors\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}})'
ms:mtpsurl: 'errorscontainer-t-clearerrors-tproperty-method-expression-func-tproperty-mspp-viewmodel.md'
---

# ErrorsContainer&lt;T&gt;.ClearErrors&lt;TProperty&gt; Method (Expression&lt;Func&lt;TProperty&gt;&gt;)

Clears the errors for the property indicated by the property expression.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](mspp-viewmodel-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public void ClearErrors<TProperty>(
	Expression<Func<TProperty>> propertyExpression
)
```
### Parameters

*propertyExpression*

	Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)<[Func](http://msdn.microsoft.com/en-us/library/bb534960)<TProperty>>
	The expression indicating a property.
	
### Type Parameters

*TProperty*<br/>
	The property type.

## Examples
container.ClearErrors(()=>SomeProperty);

## See Also

[ErrorsContainer&lt;T&gt; Class](errorscontainer-t-class-mspp-viewmodel)<br/>
[ErrorsContainer&lt;T&gt; Members](errorscontainer-t-members-mspp-viewmodel)<br/>
[ClearErrors Overload](errorscontainer-t-clearerrors-method-mspp-viewmodel)<br/>
[Microsoft.Practices.Prism.ViewModel Namespace](mspp-viewmodel-namespace)

# ErrorsContainer(Of T).ClearErrors(Of TProperty) Method (Expression(Of Func(Of TProperty)))

Clears the errors for the property indicated by the property expression.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](mspp-viewmodel-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Sub ClearErrors(Of TProperty) ( 
	propertyExpression As Expression(Of Func(Of TProperty))
)
```
### Parameters

*propertyExpression*  

	Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)(Of [Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of TProperty))

	The expression indicating a property.

### Type Parameters

*TProperty*

	The property type.

## Examples

container.ClearErrors(()=&gt;SomeProperty);

## See Also
[ErrorsContainer(Of T) Class](errorscontainer-t-class-mspp-viewmodel)

[ErrorsContainer(Of T) Members](errorscontainer-t-members-mspp-viewmodel)

[ClearErrors Overload](errorscontainer-t-clearerrors-method-mspp-viewmodel)

[Microsoft.Practices.Prism.ViewModel Namespace](mspp-viewmodel-namespace)
