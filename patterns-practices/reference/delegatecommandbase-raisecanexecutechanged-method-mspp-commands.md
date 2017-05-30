---
TOCTitle: RaiseCanExecuteChanged Method
Title: 'DelegateCommandBase.RaiseCanExecuteChanged Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.RaiseCanExecuteChanged'
ms:mtpsurl: 'delegatecommandbase-raisecanexecutechanged-method-mspp-commands.md'
---

# DelegateCommandBase.RaiseCanExecuteChanged Method

Raises [CanExecuteChanged](delegatecommandbase-canexecutechanged-event-mspp-commands) on the UI thread so every command invoker can requery to check if the command can execute.

### Remarks

Note that this will trigger the execution of [CanExecute(Object)](delegatecommandbase-canexecute-method-mspp-commands) once for each invoker.

**Namespace:** [Microsoft.Practices.Prism.Commands](mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public void RaiseCanExecuteChanged()
```

```VB
'Declaration
Public Sub RaiseCanExecuteChanged
```

## See Also

[DelegateCommandBase Class](delegatecommandbase-class-mspp-commands)

[DelegateCommandBase Members](delegatecommandbase-members-mspp-commands)

[Microsoft.Practices.Prism.Commands Namespace](mspp-commands-namespace)