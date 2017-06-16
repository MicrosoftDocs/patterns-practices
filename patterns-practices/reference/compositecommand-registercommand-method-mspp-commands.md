---
TOCTitle: RegisterCommand Method
Title: 'CompositeCommand.RegisterCommand Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.RegisterCommand(System.Windows.Input.ICommand)'
ms:mtpsurl: 'compositecommand-registercommand-method-mspp-commands.md'
---

# CompositeCommand.RegisterCommand Method

Adds a command to the collection and signs up for the [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) event of it.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

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

[CompositeCommand Class](/patterns-practices/reference/compositecommand-class-mspp-commands)  
[CompositeCommand Members](/patterns-practices/reference/compositecommand-members-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  