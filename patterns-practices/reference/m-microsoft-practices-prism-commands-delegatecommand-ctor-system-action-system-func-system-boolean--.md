---
TOCTitle: 'DelegateCommand Constructor (Action, Func(Boolean))'
Title: 'DelegateCommand Constructor (Action, Func(Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand.\#ctor(System.Action,System.Func{System.Boolean})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg406161(v=PandP.50)'
---

Prism Class Library

DelegateCommand Constructor (Action, Func&lt;(Of &lt;(Boolean&gt;)&gt;))
========================================================================

Creates a new instance of [DelegateCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand) with the [Action](http://msdn2.microsoft.com/en-us/library/bb534741) to invoke on execution and a Func to query for determining if the command can execute.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public DelegateCommand( Action executeMethod, Func&lt;bool&gt; canExecuteMethod )Public Sub New ( executeMethod As Action, canExecuteMethod As Func(Of Boolean) )
#### Parameters

executeMethod  
Type: [System..::.Action](http://msdn2.microsoft.com/en-us/library/bb534741)
The [Action](http://msdn2.microsoft.com/en-us/library/bb534741) to invoke when [Execute(Object)](http://msdn2.microsoft.com/en-us/library/ms604094) is called.

<!-- -->

canExecuteMethod  
Type: [System..::.Func](http://msdn2.microsoft.com/en-us/library/bb534960)&lt;(Of &lt;([Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)&gt;)&gt;)
The [Func&lt;(Of &lt;(TResult&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/bb534960) to invoke when [CanExecute(Object)](http://msdn2.microsoft.com/en-us/library/ms604093) is called

See Also
--------

<span id="seeAlsoToggle"></span>
[DelegateCommand Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand)

[DelegateCommand Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommand)

[DelegateCommand Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.commands.delegatecommand.)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
