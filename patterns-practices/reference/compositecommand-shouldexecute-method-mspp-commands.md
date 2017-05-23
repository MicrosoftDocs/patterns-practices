---
TOCTitle: ShouldExecute Method
Title: 'CompositeCommand.ShouldExecute Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.ShouldExecute(System.Windows.Input.ICommand)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405752(v=PandP.50)'
---

Prism Class Library

CompositeCommand.ShouldExecute Method
=========================================

Evaluates if a command should execute.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


protected virtual bool ShouldExecute( ICommand command )Protected Overridable Function ShouldExecute ( command As ICommand ) As Boolean

### Parameters

command  
Type: [System.Windows.Input.ICommand](http://msdn.microsoft.com/en-us/library/ms616869)
The command to evaluate.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
A [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50) value indicating whether the command should be used when evaluating [CanExecute(Object)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.compositecommand.canexecute(system.object)) and [Execute(Object)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.compositecommand.execute(system.object)).

Remarks
-------

<span id="remarksToggle"></span> If this command is set to monitor command activity, and command implements the [!:IActiveAwareCommand\] interface, this method will return falseFalsefalsefalse (False in Visual Basic) if the command's [!:IActiveAwareCommand.IsActive\] property is falseFalsefalsefalse (False in Visual Basic); otherwise it always returns trueTruetruetrue (True in Visual Basic).

See Also
--------


[CompositeCommand Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.compositecommand)

[CompositeCommand Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.compositecommand)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
