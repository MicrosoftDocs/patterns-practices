---
TOCTitle: 'RaisePropertyChanged(T) Method (Expression(Func(T)))'
Title: 'NotificationObject.RaisePropertyChanged(T) Method (Expression(Func(T))) (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.NotificationObject.RaisePropertyChanged\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}})'
ms:mtpsurl: 'notificationobject-raisepropertychanged-t-method-expression-func-t-mspp-viewmodel.md'
---


# NotificationObject.RaisePropertyChanged&lt;T&gt; Method (Expression&lt;Func&lt;T&gt;&gt;)

Raises this object's PropertyChanged event.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](/patterns-practices/reference/mspp-viewmodel-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected void RaisePropertyChanged<T>(
	Expression<Func<T>> propertyExpression
)
```

### Parameters

*propertyExpression*  

Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)&lt;[Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;T&gt;&gt;

A Lambda expression representing the property that has a new value.

## Type Parameters


*T*  

The type of the property that has a new value

## See Also

[NotificationObject Class](/patterns-practices/reference/notificationobject-class-mspp-viewmodel)  
[NotificationObject Members](/patterns-practices/reference/notificationobject-members-mspp-viewmodel)  
[RaisePropertyChanged Overload](/patterns-practices/reference/notificationobject-raisepropertychanged-method-mspp-viewmodel)  
[Microsoft.Practices.Prism.ViewModel Namespace](/patterns-practices/reference/mspp-viewmodel-namespace)  

# NotificationObject.RaisePropertyChanged(Of T) Method (Expression(Of Func(Of T)))

Raises this object's PropertyChanged event.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](/patterns-practices/reference/mspp-viewmodel-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Protected Sub RaisePropertyChanged(Of T) ( 
	propertyExpression As Expression(Of Func(Of T))
)
```

### Parameters

*propertyExpression*  

Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)(Of [Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of T))

A Lambda expression representing the property that has a new value.

## Type Parameters


*T*  

The type of the property that has a new value

## See Also

[NotificationObject Class](/patterns-practices/reference/notificationobject-class-mspp-viewmodel)  
[NotificationObject Members](/patterns-practices/reference/notificationobject-members-mspp-viewmodel)  
[RaisePropertyChanged Overload](/patterns-practices/reference/notificationobject-raisepropertychanged-method-mspp-viewmodel)  
[Microsoft.Practices.Prism.ViewModel Namespace](/patterns-practices/reference/mspp-viewmodel-namespace)  