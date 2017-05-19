---
TOCTitle: 'SetErrors(TProperty) Method (Expression(Func(TProperty)), IEnumerable(T))'
Title: 'ErrorsContainer(T).SetErrors(TProperty) Method (Expression(Func(TProperty)), IEnumerable(T)) (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.ErrorsContainer\`1.SetErrors\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}},System.Collections.Generic.IEnumerable{\`0})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg406217(v=PandP.50)'
---

Prism Class Library

ErrorsContainer&lt;(Of &lt;(T&gt;)&gt;).SetErrors&lt;(Of &lt;(TProperty&gt;)&gt;) Method (Expression&lt;(Of &lt;(Func&lt;(Of &lt;(TProperty&gt;)&gt;)&gt;)&gt;), IEnumerable&lt;(Of &lt;(T&gt;)&gt;))
=========================================================================================================================================================================================================

Sets the validation errors for the specified property.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](https://msdn.microsoft.com/n:microsoft.practices.prism.viewmodel)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public void SetErrors&lt;TProperty&gt;( Expression&lt;Func&lt;TProperty&gt;&gt; propertyExpression, IEnumerable&lt;T&gt; propertyErrors ) Public Sub SetErrors(Of TProperty) ( propertyExpression As Expression(Of Func(Of TProperty)), propertyErrors As IEnumerable(Of T) )
#### Parameters

propertyExpression  
Type: [System.Linq.Expressions.Expression](http://msdn2.microsoft.com/en-us/library/bb335710)&lt;(Of &lt;([Func](http://msdn2.microsoft.com/en-us/library/bb534960)&lt;(Of &lt;(TProperty&gt;)&gt;)&gt;)&gt;)
The [Expression](http://msdn2.microsoft.com/en-us/library/bb356138) indicating the property.

propertyErrors  
Type: [System.Collections.Generic.IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([T](https://msdn.microsoft.com/t:microsoft.practices.prism.viewmodel.errorscontainer%601)&gt;)&gt;)
The list of errors to set for the property.

Type Parameters
---------------

<span id="templatesToggle"></span>
TProperty  
The property type for which to set errors.

See Also
--------


[ErrorsContainer&lt;(Of &lt;(T&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.viewmodel.errorscontainer%601)

[ErrorsContainer&lt;(Of &lt;(T&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.viewmodel.errorscontainer%601)

[SetErrors Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.viewmodel.errorscontainer%601.seterrors)

[Microsoft.Practices.Prism.ViewModel Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.viewmodel)
