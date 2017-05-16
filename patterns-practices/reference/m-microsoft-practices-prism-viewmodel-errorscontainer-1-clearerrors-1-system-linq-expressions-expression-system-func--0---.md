---
TOCTitle: 'ClearErrors(TProperty) Method (Expression(Func(TProperty)))'
Title: 'ErrorsContainer(T).ClearErrors(TProperty) Method (Expression(Func(TProperty))) (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.ErrorsContainer\`1.ClearErrors\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg406216(v=PandP.50)'
---

Prism Class Library

ErrorsContainer&lt;(Of &lt;(T&gt;)&gt;)..::.ClearErrors&lt;(Of &lt;(TProperty&gt;)&gt;) Method (Expression&lt;(Of &lt;(Func&lt;(Of &lt;(TProperty&gt;)&gt;)&gt;)&gt;))
======================================================================================================================================================================

Clears the errors for the property indicated by the property expression.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](https://msdn.microsoft.com/n:microsoft.practices.prism.viewmodel)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public void ClearErrors&lt;TProperty&gt;( Expression&lt;Func&lt;TProperty&gt;&gt; propertyExpression ) Public Sub ClearErrors(Of TProperty) ( propertyExpression As Expression(Of Func(Of TProperty)) )
#### Parameters

propertyExpression  
Type: [System.Linq.Expressions..::.Expression](http://msdn2.microsoft.com/en-us/library/bb335710)&lt;(Of &lt;([Func](http://msdn2.microsoft.com/en-us/library/bb534960)&lt;(Of &lt;(TProperty&gt;)&gt;)&gt;)&gt;)
The expression indicating a property.

Type Parameters
---------------

<span id="templatesToggle"></span>
TProperty  
The property type.

Examples
--------

<span id="exampleToggle"></span> container.ClearErrors(()=&gt;SomeProperty);

See Also
--------

<span id="seeAlsoToggle"></span>
[ErrorsContainer&lt;(Of &lt;(T&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.viewmodel.errorscontainer%601)

[ErrorsContainer&lt;(Of &lt;(T&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.viewmodel.errorscontainer%601)

[ClearErrors Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.viewmodel.errorscontainer%601.clearerrors)

[Microsoft.Practices.Prism.ViewModel Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.viewmodel)
