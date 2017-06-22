---
TOCTitle: 'FromAsyncHandler Method (Func(Task), Func(Boolean))'
Title: 'DelegateCommand.FromAsyncHandler Method (Func(Task), Func(Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand.FromAsyncHandler(System.Func{System.Threading.Tasks.Task},System.Func{System.Boolean})'
ms:mtpsurl: 'delegatecommand-fromasynchandler-method-func-task-func-boolean-mspp-commands.md'
---


# DelegateCommand.FromAsyncHandler Method (Func&lt;Task&gt;, Func&lt;Boolean&gt;)

Factory method to create a new instance of [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public static DelegateCommand FromAsyncHandler(
	Func<Task> executeMethod,
	Func<bool> canExecuteMethod
)
```

### Parameters

*executeMethod*  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;[Task](http://msdn.microsoft.com/en-us/library/dd235678)&gt;  
Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

*canExecuteMethod*  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;[Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)&gt;  
Delegate to execute when CanExecute is called on the command. This can be null.

### Return Value

Type: [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)  
Constructed instance of [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)

## See Also

[DelegateCommand Class](/patterns-practices/reference/delegatecommand-class-mspp-commands)  
[DelegateCommand Members](/patterns-practices/reference/delegatecommand-members-mspp-commands)  
[FromAsyncHandler Overload](/patterns-practices/reference/delegatecommand-fromasynchandler-method-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  


# DelegateCommand.FromAsyncHandler Method (Func(Of Task), Func(Of Boolean))

Factory method to create a new instance of [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Shared Function FromAsyncHandler ( 
	executeMethod As Func(Of Task),
	canExecuteMethod As Func(Of Boolean)
) As DelegateCommand
```

### Parameters

*executeMethod*  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of [Task](http://msdn.microsoft.com/en-us/library/dd235678))
Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

*canExecuteMethod*  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50))  
Delegate to execute when CanExecute is called on the command. This can be null.

### Return Value

Type: [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)  
Constructed instance of [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)

## See Also

[DelegateCommand Class](/patterns-practices/reference/delegatecommand-class-mspp-commands)  
[DelegateCommand Members](/patterns-practices/reference/delegatecommand-members-mspp-commands)  
[FromAsyncHandler Overload](/patterns-practices/reference/delegatecommand-fromasynchandler-method-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)