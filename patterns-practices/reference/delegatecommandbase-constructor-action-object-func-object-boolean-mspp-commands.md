---
TOCTitle: 'DelegateCommandBase Constructor (Action(Object), Func(Object, Boolean))'
Title: 'DelegateCommandBase Constructor (Action(Object), Func(Object, Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.\#ctor(System.Action{System.Object},System.Func{System.Object,System.Boolean})'
ms:mtpsurl: 'delegatecommandbase-constructor-action-object-func-object-boolean-mspp-commands.md'
---

# DelegateCommandBase Constructor (Action&lt;Object&gt;, Func&lt;Object, Boolean&gt;)

Creates a new instance of a [DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands), specifying both the execute action and the can execute function.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)<br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
protected DelegateCommandBase(
	Action<Object> executeMethod,
	Func<Object, bool> canExecuteMethod
)
```

### Parameters

*executeMethod* 

Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;

The [Action](http://msdn.microsoft.com/en-us/library/bb534741) to execute when [Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094) is invoked.

*canExecuteMethod*  

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b), [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)&gt;

The [Func&lt;T, TResult&gt;](http://msdn.microsoft.com/en-us/library/bb549151) to invoked when [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) is invoked.

## See Also

[DelegateCommandBase Class](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)<br/>
[DelegateCommandBase Members](/patterns-practices/reference/delegatecommandbase-members-mspp-commands)<br/>
DelegateCommandBase Overload

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>

# DelegateCommandBase Constructor (Action(Of Object), Func(Of Object, Boolean))

Creates a new instance of a [DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands), specifying both the execute action and the can execute function.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) <br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Protected Sub New ( 
	executeMethod As Action(Of Object),
	canExecuteMethod As Func(Of Object, Boolean)
)
```

### Parameters

*executeMethod* 

Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))

The [Action](http://msdn.microsoft.com/en-us/library/bb534741) to execute when [Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094) is invoked.

*canExecuteMethod*  

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b), [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50))

The [Func(Of T, TResult)](http://msdn.microsoft.com/en-us/library/bb549151) to invoked when [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) is invoked.

## See Also

[DelegateCommandBase Class](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)<br/>
[DelegateCommandBase Members](/patterns-practices/reference/delegatecommandbase-members-mspp-commands)<br/>
DelegateCommandBase Overload

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>