---
TOCTitle: 'FromAsyncHandler Method (Func(Task))'
Title: 'DelegateCommand.FromAsyncHandler Method (Func(Task)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand.FromAsyncHandler(System.Func{System.Threading.Tasks.Task})'
ms:mtpsurl: 'delegatecommand-fromasynchandler-method-func-task-func-boolean-mspp-commands.md'
---

# DelegateCommand.FromAsyncHandler Method (Func&lt;Task&gt;)

Factory method to create a new instance of [DelegateCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#  
public static DelegateCommand FromAsyncHandler(
	Func<Task> executeMethod
)
```

### Parameters

*executeMethod*  

Type: [System.Func](http://msdn2.microsoft.com/en-us/library/bb534960)&lt;[Task](http://msdn2.microsoft.com/en-us/library/dd235678)&gt;

Delegate to execute when Execute is called on the command.

### Return Value

Type: [DelegateCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

Constructed instance of [DelegateCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

## See Also

[DelegateCommand Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

[DelegateCommand Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommand_members)

[FromAsyncHandler Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommand.fromasynchandler)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)



# DelegateCommand.FromAsyncHandler Method (Func(Of Task))

Factory method to create a new instance of [DelegateCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB  
'Declaration
Public Shared Function FromAsyncHandler ( 
	executeMethod As Func(Of Task)
) As DelegateCommand
```

### Parameters

*executeMethod*  

Type: [System.Func](http://msdn2.microsoft.com/en-us/library/bb534960)(Of [Task](http://msdn2.microsoft.com/en-us/library/dd235678))

Delegate to execute when Execute is called on the command.

### Return Value

Type: [DelegateCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

Constructed instance of [DelegateCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

## See Also

[DelegateCommand Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

[DelegateCommand Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommand_members)

[FromAsyncHandler Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommand.fromasynchandler)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
