---
TOCTitle: RaiseCanExecuteChanged Method
Title: 'DelegateCommandBase.RaiseCanExecuteChanged Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.RaiseCanExecuteChanged'
ms:mtpsurl: 'delegatecommandbase-raisecanexecutechanged-method-mspp-commands.md'
---

# DelegateCommandBase.RaiseCanExecuteChanged Method

Raises [CanExecuteChanged](/patterns-practices/reference/delegatecommandbase-canexecutechanged-event-mspp-commands) on the UI thread so every command invoker can requery to check if the command can execute.

### Remarks

Note that this will trigger the execution of [CanExecute(Object)](/patterns-practices/reference/delegatecommandbase-canexecute-method-mspp-commands) once for each invoker.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

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

[DelegateCommandBase Class](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)

[DelegateCommandBase Members](/patterns-practices/reference/delegatecommandbase-members-mspp-commands)

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)