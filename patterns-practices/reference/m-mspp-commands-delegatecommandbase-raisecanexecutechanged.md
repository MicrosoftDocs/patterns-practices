---
TOCTitle: RaiseCanExecuteChanged Method
Title: 'DelegateCommandBase.RaiseCanExecuteChanged Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.RaiseCanExecuteChanged'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405758(v=PandP.50)'
---

Prism Class Library

DelegateCommandBase..::.RaiseCanExecuteChanged Method
=====================================================

Raises [CanExecuteChanged](https://msdn.microsoft.com/e:microsoft.practices.prism.commands.delegatecommandbase.canexecutechanged) on the UI thread so every command invoker can requery to check if the command can execute.
Remarks
-------

<span id="remarksToggle"></span>Note that this will trigger the execution of [CanExecute(Object)](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.delegatecommandbase.canexecute(system.object)) once for each invoker.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public void RaiseCanExecuteChanged()Public Sub RaiseCanExecuteChanged

See Also
--------

<span id="seeAlsoToggle"></span>
[DelegateCommandBase Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase)

[DelegateCommandBase Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommandbase)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
