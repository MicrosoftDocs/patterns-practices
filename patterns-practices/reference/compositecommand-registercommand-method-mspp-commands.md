---
TOCTitle: RegisterCommand Method
Title: 'CompositeCommand.RegisterCommand Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.RegisterCommand(System.Windows.Input.ICommand)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405751(v=PandP.50)'
---


# CompositeCommand.RegisterCommand Method

Adds a command to the collection and signs up for the [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) event of it.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual void RegisterCommand(
	ICommand command
)
```
```VB
'Declaration
Public Overridable Sub RegisterCommand ( 
	command As ICommand
)
```

### Parameters

*command*  
Type: [System.Windows.Input.ICommand](http://msdn.microsoft.com/en-us/library/ms616869)

The command to register.

## Remarks

 If this command is set to monitor command activity, and command implements the [!:IActiveAwareCommand] interface, this method will subscribe to its [!:IActiveAwareCommand.IsActiveChanged] event.

## See Also

[CompositeCommand Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.compositecommand(v=pandp.50))

[CompositeCommand Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.compositecommand_members(v=pandp.50))

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))
