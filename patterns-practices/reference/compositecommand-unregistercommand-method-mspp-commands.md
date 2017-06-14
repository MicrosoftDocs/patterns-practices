---
TOCTitle: UnregisterCommand Method
Title: 'CompositeCommand.UnregisterCommand Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.UnregisterCommand(System.Windows.Input.ICommand)'
ms:mtpsurl: 'compositecommand-unregistercommand-method-mspp-commands.md'
---

# CompositeCommand.UnregisterCommand Method

Removes a command from the collection and removes itself from the [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) event of it.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual void UnregisterCommand(
	ICommand command
)
```

```VB
'Declaration
Public Overridable Sub UnregisterCommand ( 
	command As ICommand
)
```

### Parameters

*command*

Type: [System.Windows.Input.ICommand](http://msdn.microsoft.com/en-us/library/ms616869)  
The command to unregister.

## See Also

[CompositeCommand Class](/patterns-practices/reference/compositecommand-class-mspp-commands)  
[CompositeCommand Members](/patterns-practices/reference/compositecommand-members-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  