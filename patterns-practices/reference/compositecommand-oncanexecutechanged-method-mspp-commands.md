---
TOCTitle: OnCanExecuteChanged Method
Title: 'CompositeCommand.OnCanExecuteChanged Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.OnCanExecuteChanged'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405750(v=PandP.50)'
---

Prism Class Library

CompositeCommand.OnCanExecuteChanged Method
===============================================

Raises [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) on the UI thread so every command invoker can requery [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) to check if the [CompositeCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.compositecommand) can execute.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


protected virtual void OnCanExecuteChanged()Protected Overridable Sub OnCanExecuteChanged

See Also
--------


[CompositeCommand Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.compositecommand)

[CompositeCommand Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.compositecommand)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
