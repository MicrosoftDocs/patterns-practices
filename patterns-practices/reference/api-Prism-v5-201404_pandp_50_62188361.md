---
TOCTitle: CanExecute Method
Title: 'CompositeCommand.CanExecute Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.CanExecute(System.Object)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405748(v=PandP.50)'
---

Prism Class Library

CompositeCommand..::.CanExecute Method
======================================

Forwards [CanExecute(Object)](http://msdn2.microsoft.com/en-us/library/ms604093) to the registered commands and returns trueTruetruetrue (True in Visual Basic) if all of the commands return trueTruetruetrue (True in Visual Basic).

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public virtual bool CanExecute( Object parameter )Public Overridable Function CanExecute ( parameter As Object ) As Boolean
#### Parameters

parameter  
Type: [System..::.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
Data used by the command. If the command does not require data to be passed, this object can be set to nullNothingnullptra null reference (Nothing in Visual Basic).

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
trueTruetruetrue (True in Visual Basic) if all of the commands return trueTruetruetrue (True in Visual Basic); otherwise, falseFalsefalsefalse (False in Visual Basic).
#### Implements

[ICommand..::.CanExecute(Object)](http://msdn2.microsoft.com/en-us/library/ms604093)

See Also
--------

<span id="seeAlsoToggle"></span>
[CompositeCommand Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.compositecommand)

[CompositeCommand Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.compositecommand)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
