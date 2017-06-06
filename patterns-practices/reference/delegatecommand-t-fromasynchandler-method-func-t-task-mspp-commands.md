---
TOCTitle: 'FromAsyncHandler Method (Func(T, Task))'
Title: 'DelegateCommand(T).FromAsyncHandler Method (Func(T, Task)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.FromAsyncHandler(System.Func{\`0,System.Threading.Tasks.Task})'
ms:mtpsurl: 'delegatecommand-t-fromasynchandler-method-func-t-task-mspp-commands.md'
---


# DelegateCommand&lt;T&gt;.FromAsyncHandler Method (Func&lt;T, Task&gt;)

Factory method to create a new instance of [DelegateCommand&lt;T&gt;](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
    public static DelegateCommand<T> FromAsyncHandler(
	Func<T, Task> executeMethod
)
```

### Parameters

*executeMethod*
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;[T](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand), [Task](http://msdn.microsoft.com/en-us/library/dd235678)&gt;)
Delegate to execute when Execute is called on the command.

### Return Value

Type: [DelegateCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)&lt;[T](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)&gt;)
Constructed instance of [DelegateCommand&lt;T&gt;](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

## See Also

[DelegateCommand&lt;T&gt; Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

[DelegateCommand&lt;T Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommand)

[FromAsyncHandler Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.commands.delegatecommand%601.fromasynchandler)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)


# DelegateCommand(Of T).FromAsyncHandler Method (Func(Of T, Task)

Factory method to create a new instance of [DelegateCommand(Of T)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB
    'Declaration
Public Shared Function FromAsyncHandler ( 
	executeMethod As Func(Of T, Task)
) As DelegateCommand(Of T)
```

### Parameters

*executeMethod*
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)(Of T,](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand), [Task])(http://msdn.microsoft.com/en-us/library/dd235678)&gt;)
Delegate to execute when Execute is called on the command.

### Return Value

Type: [DelegateCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand) (Of [T])(https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)
Constructed instance of [DelegateCommand(Of T)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

## See Also

[DelegateCommand&lt;T&gt; Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

[DelegateCommand&lt;T Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommand)

[FromAsyncHandler Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.commands.delegatecommand%601.fromasynchandler)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)