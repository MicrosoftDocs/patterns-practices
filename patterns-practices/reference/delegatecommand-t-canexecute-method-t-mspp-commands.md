---
TOCTitle: 'CanExecute Method (T)'
Title: 'DelegateCommand(T).CanExecute Method (T) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.CanExecute(\`0)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405763(v=PandP.50)'
---

Prism Class Library

DelegateCommand&lt;(Of &lt;(T&gt;)&gt;).CanExecute Method (T)
=================================================================

Determines if the command can execute by invoked the [Func&lt;(Of &lt;(T, TResult&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/bb549151) provided during construction.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public virtual bool CanExecute( T parameter )Public Overridable Function CanExecute ( parameter As T ) As Boolean
#### Parameters

parameter  
Type: [T](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand%601)
Data used by the command to determine if it can execute.

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
trueTruetruetrue (True in Visual Basic) if this command can be executed; otherwise, falseFalsefalsefalse (False in Visual Basic).

See Also
--------


[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand%601)

[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommand%601)

[CanExecute Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.commands.delegatecommand%601.canexecute)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
