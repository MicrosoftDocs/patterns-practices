---
TOCTitle: RegisteredCommands Property
Title: 'CompositeCommand.RegisteredCommands Property (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'P:Microsoft.Practices.Prism.Commands.CompositeCommand.RegisteredCommands'
ms:mtpsurl: 'compositecommand-registeredcommands-property-mspp-commands.md'
---

# CompositeCommand.RegisteredCommands Property

Gets the list of all the registered commands.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public IList<ICommand> RegisteredCommands { get; }
```

### Property Value

Type: [IList](http://msdn2.microsoft.com/en-us/library/5y536ey6)&lt;[ICommand](http://msdn2.microsoft.com/en-us/library/ms616869)&gt;

A list of registered commands.

```VB
'Declaration
Public ReadOnly Property RegisteredCommands As IList(Of ICommand)
	Get
```

### Property Value

Type: [IList](http://msdn2.microsoft.com/en-us/library/5y536ey6)(Of [ICommand](http://msdn2.microsoft.com/en-us/library/ms616869))

A list of registered commands.

## Remarks

This returns a copy of the commands subscribed to the CompositeCommand.

## See Also

[CompositeCommand Class](/patterns-practices/reference/compositecommand-class-mspp-commands)  
[CompositeCommand Members](/patterns-practices/reference/compositecommand-members-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)