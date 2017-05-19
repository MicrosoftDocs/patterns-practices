---
TOCTitle: 'ClearErrors(TProperty) Method (Expression(Func(TProperty)))'
Title: 'ErrorsContainer(T).ClearErrors(TProperty) Method (Expression(Func(TProperty))) (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.ErrorsContainer\`1.ClearErrors\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg406216(v=PandP.50)'
---

Prism Class Library

# ErrorsContainer&lt;T&gt;.ClearErrors&lt;TProperty&gt; Method (Expression&lt;Func&lt;TProperty&gt;&gt;)

Clears the errors for the property indicated by the property expression.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public void ClearErrors<TProperty>(
	Expression<Func<TProperty>> propertyExpression
)
```

#### Parameters

*propertyExpression*

	Type: [System.Linq.Expressions.Expression](http://msdn2.microsoft.com/en-us/library/bb335710)<[Func](http://msdn2.microsoft.com/en-us/library/bb534960)<TProperty>>
	The expression indicating a property.
	
### Type Parameters

*TProperty*<br/>
	The property type.

## Examples
container.ClearErrors(()=>SomeProperty);

## See Also

[ErrorsContainer&lt;T&gt; Class](https://msdn.microsoft.com/en-us/library/gg431577(v=pandp.50))<br/>
[ErrorsContainer&lt;T&gt; Members](https://msdn.microsoft.com/en-us/library/gg405531(v=pandp.50))<br/>
[ClearErrors Overload](https://msdn.microsoft.com/en-us/library/gg419151(v=pandp.50))<br/>
[Microsoft.Practices.Prism.ViewModel Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel(v=pandp.50))

# ErrorsContainer(Of T).ClearErrors(Of TProperty) Method (Expression(Of Func(Of TProperty)))

Clears the errors for the property indicated by the property expression.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Sub ClearErrors(Of TProperty) ( 
	propertyExpression As Expression(Of Func(Of TProperty))
)
```

#### Parameters

*propertyExpression*  

	Type: [System.Linq.Expressions.Expression](http://msdn2.microsoft.com/en-us/library/bb335710)(Of [Func](http://msdn2.microsoft.com/en-us/library/bb534960)(Of TProperty))

	The expression indicating a property.

### Type Parameters

*TProperty*

	The property type.

## Examples

container.ClearErrors(()=&gt;SomeProperty);

## See Also

<span id="seeAlsoToggle"></span>
[ErrorsContainer(Of T) Class](https://msdn.microsoft.com/en-us/library/gg431577(v=pandp.50))

[ErrorsContainer(Of T) Members](https://msdn.microsoft.com/en-us/library/gg405531(v=pandp.50))

[ClearErrors Overload](https://msdn.microsoft.com/en-us/library/gg419151(v=pandp.50))

[Microsoft.Practices.Prism.ViewModel Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel(v=pandp.50))
