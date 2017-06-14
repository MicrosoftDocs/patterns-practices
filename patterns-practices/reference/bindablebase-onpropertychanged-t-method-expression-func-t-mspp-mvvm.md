---
TOCTitle: 'OnPropertyChanged(T) Method (Expression(Func(T)))'
Title: 'BindableBase.OnPropertyChanged(T) Method (Expression(Func(T))) (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.BindableBase.OnPropertyChanged\`\`1(System.Linq.Expressions.Expression{System.Func{\`\`0}})'
ms:mtpsurl: 'bindablebase-onpropertychanged-t-method-expression-func-t-mspp-mvvm.md'
---

# BindableBase.OnPropertyChanged&lt;T&gt; Method (Expression&lt;Func&lt;T&gt;&gt;)

Raises this object's PropertyChanged event. 

**Namespace:** [Microsoft.Practices.Prism.Mvvm](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
protected void OnPropertyChanged<T>(
	Expression<Func<T>> propertyExpression
)
```

### Parameters

*propertyExpression*  
Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)&lt;[Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;T&gt;&gt;

A Lambda expression representing the property that has a new value.

### Type Parameters

*T*

The type of the property that has a new value

# BindableBase.OnPropertyChanged(Of T) Method (Expression(Of Func(Of T)))

Raises this object's PropertyChanged event. 

**Namespace:** [Microsoft.Practices.Prism.Mvvm](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Protected Sub OnPropertyChanged(Of T) ( 
	propertyExpression As Expression(Of Func(Of T))
)
```

### Parameters

*propertyExpression*  
Type: [System.Linq.Expressions.Expression](http://msdn.microsoft.com/en-us/library/bb335710)(Of [Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of T))

A Lambda expression representing the property that has a new value.

### Type Parameters

*T*

The type of the property that has a new value

## See Also

[BindableBase Class](/patterns-practices/reference/bindablebase-class-mspp-mvvm)  
[BindableBase Members](/patterns-practices/reference/bindablebase-members-mspp-mvvm)  
[OnPropertyChanged Overload](/patterns-practices/reference/bindablebase-onpropertychanged-method-mspp-mvvm)  
[Microsoft.Practices.Prism.Mvvm Namespace](/patterns-practices/reference/mspp-mvvm-namespace)  