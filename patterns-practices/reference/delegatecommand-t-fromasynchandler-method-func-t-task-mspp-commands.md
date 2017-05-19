---
TOCTitle: 'FromAsyncHandler Method (Func(T, Task))'
Title: 'DelegateCommand(T).FromAsyncHandler Method (Func(T, Task)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.FromAsyncHandler(System.Func{\`0,System.Threading.Tasks.Task})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736266(v=PandP.50)'
---

Prism Class Library

DelegateCommand&lt;(Of &lt;(T&gt;)&gt;).FromAsyncHandler Method (Func&lt;(Of &lt;(T, Task&gt;)&gt;))
========================================================================================================

Factory method to create a new instance of [DelegateCommand&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand%601) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public static DelegateCommand&lt;T&gt; FromAsyncHandler( Func&lt;T, Task&gt; executeMethod )Public Shared Function FromAsyncHandler ( executeMethod As Func(Of T, Task) ) As DelegateCommand(Of T)

### Parameters

executeMethod  
Type: [System.Func](http://msdn2.microsoft.com/en-us/library/bb549151)&lt;(Of &lt;([T](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand%601), [Task](http://msdn2.microsoft.com/en-us/library/dd235678)&gt;)&gt;)
Delegate to execute when Execute is called on the command.

### Return Value

Type: [DelegateCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand%601)&lt;(Of &lt;([T](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand%601)&gt;)&gt;)
Constructed instance of [DelegateCommand&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand%601)

See Also
--------


[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand%601)

[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommand%601)

[FromAsyncHandler Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.commands.delegatecommand%601.fromasynchandler)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
