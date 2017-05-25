---
TOCTitle: 'FromAsyncHandler Method (Func(Task), Func(Boolean))'
Title: 'DelegateCommand.FromAsyncHandler Method (Func(Task), Func(Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand.FromAsyncHandler(System.Func{System.Threading.Tasks.Task},System.Func{System.Boolean})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736304(v=PandP.50)'
---


# DelegateCommand.FromAsyncHandler Method (Func&lt;(Of &lt;(Task&gt;)&gt;), Func&lt;(Of &lt;(Boolean&gt;)&gt;))

Factory method to create a new instance of [DelegateCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

public static DelegateCommand FromAsyncHandler( Func&lt;Task&gt; executeMethod, Func&lt;bool&gt; canExecuteMethod )Public Shared Function FromAsyncHandler ( executeMethod As Func(Of Task), canExecuteMethod As Func(Of Boolean) ) As DelegateCommand

### Parameters

executeMethod  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;(Of &lt;([Task](http://msdn.microsoft.com/en-us/library/dd235678)&gt;)&gt;)
Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

canExecuteMethod  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;(Of &lt;([Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)&gt;)&gt;)
Delegate to execute when CanExecute is called on the command. This can be null.

### Return Value

Type: [DelegateCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)
Constructed instance of [DelegateCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

## See Also

[DelegateCommand Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

[DelegateCommand Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommand)

[FromAsyncHandler Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.commands.delegatecommand.fromasynchandler)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
