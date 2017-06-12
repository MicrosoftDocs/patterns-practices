---
TOCTitle: 'DelegateCommand Constructor (Action, Func(Boolean))'
Title: 'DelegateCommand Constructor (Action, Func(Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand.\#ctor(System.Action,System.Func{System.Boolean})'
ms:mtpsurl: 'delegatecommand-constructor-action-func-boolean-mspp-commands.md'
---

# DelegateCommand Constructor (Action, Func&lt;Boolean&gt;)

Creates a new instance of [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands) with the [Action](http://msdn.microsoft.com/en-us/library/bb534741) to invoke on execution and a **Func** to query for determining if the command can execute.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)

**Version:** 1.0.0.0 (1.0.0.0)

# Syntax

```C#
public DelegateCommand(
	Action executeMethod,
	Func<bool> canExecuteMethod
)
```

### Parameters

*executeMethod*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/bb534741)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The [Action](http://msdn.microsoft.com/en-us/library/bb534741) to invoke when [Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094) is called.

*canExecuteMethod*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;[Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)&gt;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The [Func&lt;TResult&gt;](http://msdn.microsoft.com/en-us/library/bb534960) to invoke when [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) is called

## See Also

[DelegateCommand Class](/patterns-practices/reference/delegatecommand-class-mspp-commands)<br/>
[DelegateCommand Members](/patterns-practices/reference/delegatecommand-members-mspp-commands)<br/>
DelegateCommand Overload

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>

# DelegateCommand Constructor (Action, Func(Of Boolean))

Creates a new instance of [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands) with the [Action](http://msdn.microsoft.com/en-us/library/bb534741) to invoke on execution and a **Func** to query for determining if the command can execute.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)

**Version:** 1.0.0.0 (1.0.0.0)

# Syntax

```VB
'Declaration
Public Sub New ( 
	executeMethod As Action,
	canExecuteMethod As Func(Of Boolean)
)
```

### Parameters

*executeMethod*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/bb534741)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The [Action](http://msdn.microsoft.com/en-us/library/bb534741) to invoke when [Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094) is called.

*canExecuteMethod*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of ([Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The [Func(Of (TResult))](http://msdn.microsoft.com/en-us/library/bb534960) to invoke when [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) is called

## See Also

[DelegateCommand Class](/patterns-practices/reference/delegatecommand-class-mspp-commands)<br/>
[DelegateCommand Members](/patterns-practices/reference/delegatecommand-members-mspp-commands)<br/>
DelegateCommand Overload

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>