---
TOCTitle: RegisterCommand Method
Title: 'CompositeCommand.RegisterCommand Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.RegisterCommand(System.Windows.Input.ICommand)'
ms:mtpsurl: 'compositecommand-registercommand-method-mspp-commands.md'
---

Prism Class Library

CompositeCommand.RegisterCommand Method
===========================================

Adds a command to the collection and signs up for the [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) event of it.

**Namespace:** [Microsoft.Practices.Prism.Commands](mspp-commands-namespace.md)

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

Remarks
-------

 If this command is set to monitor command activity, and command implements the [!:IActiveAwareCommand] interface, this method will subscribe to its [!:IActiveAwareCommand.IsActiveChanged] event.

See Also
--------


[CompositeCommand Class](compositecommand-class-mspp-commands.md)

[CompositeCommand Members](compositecommand-members-mspp-commands.md)

[Microsoft.Practices.Prism.Commands Namespace](mspp-commands-namespace.md)
