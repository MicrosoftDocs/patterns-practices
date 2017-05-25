---
TOCTitle: Execute Method
Title: 'CompositeCommand.Execute Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.Execute(System.Object)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405749(v=PandP.50)'
---


# CompositeCommand.Execute Method

Forwards [Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094) to the registered commands.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

public virtual void Execute( Object parameter )Public Overridable Sub Execute ( parameter As Object )

### Parameters

parameter  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
Data used by the command. If the command does not require data to be passed, this object can be set to nullNothingnullptra null reference (Nothing in Visual Basic).

### Implements

[ICommand.Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094)

## See Also

[CompositeCommand Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.compositecommand)

[CompositeCommand Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.compositecommand)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
