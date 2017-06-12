---
TOCTitle: 'FromAsyncHandler Method (Func(T, Task), Func(T, Boolean))'
Title: 'DelegateCommand(T).FromAsyncHandler Method (Func(T, Task), Func(T, Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.FromAsyncHandler(System.Func{\`0,System.Threading.Tasks.Task},System.Func{\`0,System.Boolean})'
ms:mtpsurl: 'delegatecommand-t-fromasynchandler-method-func-t-task-func-t-boolean-mspp-commands.md'
---


# DelegateCommand&lt;T&gt;.FromAsyncHandler Method (Func&lt;T, Task&gt;, Func&lt;T, Boolean&gt;)

Factory method to create a new instance of [DelegateCommand&lt;T&gt;](/patterns-practices/reference/delegatecommand-class-mspp-commands) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public static DelegateCommand<T> FromAsyncHandler(
	Func<T, Task> executeMethod,
	Func<T, bool> canExecuteMethod
)
```

### Parameters

*executeMethod*  

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;[T](/patterns-practices/reference/delegatecommand-class-mspp-commands), [Task](http://msdn.microsoft.com/en-us/library/dd235678)&gt;

Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

*canExecuteMethod*

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;[T](/patterns-practices/reference/delegatecommand-class-mspp-commands), [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)&gt;

Delegate to execute when CanExecute is called on the command. This can be null.

### Return Value

Type: [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)&lt;[T](/patterns-practices/reference/mspp-commands-namespace)&gt;

Constructed instance of [DelegateCommand&lt;T&gt;](/patterns-practices/reference/delegatecommand-class-mspp-commands)

## See Also

[DelegateCommand&lt;T&gt; Class](/patterns-practices/reference/delegatecommand-class-mspp-commands)<br/>
[DelegateCommand&lt;T&gt; Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)<br/>
[FromAsyncHandler Overload](/patterns-practices/reference/delegatecommand-t-fromasynchandler-method-mspp-commands)<br/>
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>


# DelegateCommand(Of T).FromAsyncHandler Method (Func(Of T, Task), Func(Of T, Boolean))

Factory method to create a new instance of [DelegateCommand(Of T)](/patterns-practices/reference/delegatecommand-class-mspp-commands) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Shared Function FromAsyncHandler ( 
	executeMethod As Func(Of T, Task),
	canExecuteMethod As Func(Of T, Boolean)
) As DelegateCommand(Of T)
```

### Parameters

*executeMethod*

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)(Of [T](/patterns-practices/reference/delegatecommand-class-mspp-commands), [Task](http://msdn.microsoft.com/en-us/library/dd235678))

Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

*canExecuteMethod*  

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)(Of [T](/patterns-practices/reference/delegatecommand-class-mspp-commands), [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50))

Delegate to execute when CanExecute is called on the command. This can be null.

### Return Value

Type: [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)(Of [T](/patterns-practices/reference/delegatecommand-class-mspp-commands))

Constructed instance of [DelegateCommand(Of T)]
(https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

## See Also

[DelegateCommand(Of T) Class](/patterns-practices/reference/delegatecommand-class-mspp-commands)<br/>
[DelegateCommand(Of T) Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)<br/>
[FromAsyncHandler Overload](/patterns-practices/reference/delegatecommand-t-fromasynchandler-method-mspp-commands)<br/>
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)