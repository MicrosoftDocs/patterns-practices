---
TOCTitle: UnregisterCommand Method
Title: 'CompositeCommand.UnregisterCommand Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.UnregisterCommand(System.Windows.Input.ICommand)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405753(v=PandP.50)'
---


# CompositeCommand.UnregisterCommand Method

Removes a command from the collection and removes itself from the [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) event of it.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

public virtual void UnregisterCommand( ICommand command )Public Overridable Sub UnregisterCommand ( command As ICommand )

### Parameters

command  
Type: [System.Windows.Input.ICommand](http://msdn.microsoft.com/en-us/library/ms616869)
The command to unregister.

## See Also

[CompositeCommand Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.compositecommand)

[CompositeCommand Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.compositecommand)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
