---
TOCTitle: 'OnPropertyChanged(T) Method (Expression(Func(T)))'
Title: 'BindableBase.OnPropertyChanged(T) Method (Expression(Func(T))) (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.BindableBase.OnPropertyChanged\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736238(v=PandP.50)'
---

Prism Class Library

BindableBase.OnPropertyChanged&lt;(Of &lt;(T&gt;)&gt;) Method (Expression&lt;(Of &lt;(Func&lt;(Of &lt;(T&gt;)&gt;)&gt;)&gt;))
=================================================================================================================================

Raises this object's PropertyChanged event.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](https://msdn.microsoft.com/n:microsoft.practices.prism.mvvm)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


protected void OnPropertyChanged&lt;T&gt;( Expression&lt;Func&lt;T&gt;&gt; propertyExpression ) Protected Sub OnPropertyChanged(Of T) ( propertyExpression As Expression(Of Func(Of T)) )

### Parameters

propertyExpression  
Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)&lt;(Of &lt;([Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;(Of &lt;(T&gt;)&gt;)&gt;)&gt;)
A Lambda expression representing the property that has a new value.

Type Parameters
---------------

<span id="templatesToggle"></span>
T  
The type of the property that has a new value

See Also
--------


[BindableBase Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mvvm.bindablebase)

[BindableBase Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mvvm.bindablebase)

[OnPropertyChanged Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.mvvm.bindablebase.onpropertychanged)

[Microsoft.Practices.Prism.Mvvm Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mvvm)
