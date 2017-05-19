---
TOCTitle: 'FromAsyncHandler Method (Func(Task))'
Title: 'DelegateCommand.FromAsyncHandler Method (Func(Task)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand.FromAsyncHandler(System.Func{System.Threading.Tasks.Task})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736189(v=PandP.50)'
---

Prism Class Library

DelegateCommand.FromAsyncHandler Method (Func&lt;(Of &lt;(Task&gt;)&gt;))
=============================================================================

Factory method to create a new instance of [DelegateCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public static DelegateCommand FromAsyncHandler( Func&lt;Task&gt; executeMethod )Public Shared Function FromAsyncHandler ( executeMethod As Func(Of Task) ) As DelegateCommand
#### Parameters

executeMethod  
Type: [System.Func](http://msdn2.microsoft.com/en-us/library/bb534960)&lt;(Of &lt;([Task](http://msdn2.microsoft.com/en-us/library/dd235678)&gt;)&gt;)
Delegate to execute when Execute is called on the command.

#### Return Value

Type: [DelegateCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand)
Constructed instance of [DelegateCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand)

See Also
--------


[DelegateCommand Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand)

[DelegateCommand Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommand)

[FromAsyncHandler Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.commands.delegatecommand.fromasynchandler)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
