---
TOCTitle: 'RaisePropertyChanged(T) Method (Expression(Func(T)))'
Title: 'NotificationObject.RaisePropertyChanged(T) Method (Expression(Func(T))) (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.NotificationObject.RaisePropertyChanged\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg406218(v=PandP.50)'
---

Prism Class Library

NotificationObject.RaisePropertyChanged&lt;(Of &lt;(T&gt;)&gt;) Method (Expression&lt;(Of &lt;(Func&lt;(Of &lt;(T&gt;)&gt;)&gt;)&gt;))
==========================================================================================================================================

Raises this object's PropertyChanged event.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](https://msdn.microsoft.com/n:microsoft.practices.prism.viewmodel)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>protected void RaisePropertyChanged&lt;T&gt;( Expression&lt;Func&lt;T&gt;&gt; propertyExpression ) Protected Sub RaisePropertyChanged(Of T) ( propertyExpression As Expression(Of Func(Of T)) )
#### Parameters

propertyExpression  
Type: [System.Linq.Expressions.Expression](http://msdn2.microsoft.com/en-us/library/bb335710)&lt;(Of &lt;([Func](http://msdn2.microsoft.com/en-us/library/bb534960)&lt;(Of &lt;(T&gt;)&gt;)&gt;)&gt;)
A Lambda expression representing the property that has a new value.

Type Parameters
---------------

<span id="templatesToggle"></span>
T  
The type of the property that has a new value

See Also
--------


[NotificationObject Class](https://msdn.microsoft.com/t:microsoft.practices.prism.viewmodel.notificationobject)

[NotificationObject Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.viewmodel.notificationobject)

[RaisePropertyChanged Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.viewmodel.notificationobject.raisepropertychanged)

[Microsoft.Practices.Prism.ViewModel Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.viewmodel)
