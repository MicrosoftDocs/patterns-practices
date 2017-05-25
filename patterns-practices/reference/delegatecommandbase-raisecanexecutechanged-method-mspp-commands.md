---
TOCTitle: RaiseCanExecuteChanged Method
Title: 'DelegateCommandBase.RaiseCanExecuteChanged Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.RaiseCanExecuteChanged'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommandbase.raisecanexecutechanged(v=pandp.50)'
---

# DelegateCommandBase.RaiseCanExecuteChanged Method

Raises [CanExecuteChanged](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommandbase.canexecutechanged(v=pandp.50)) on the UI thread so every command invoker can requery to check if the command can execute.

### Remarks

Note that this will trigger the execution of [CanExecute(Object)](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommandbase.canexecute(v=pandp.50)) once for each invoker.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))

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

[DelegateCommandBase Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommandbase(v=pandp.50))

[DelegateCommandBase Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommandbase_members(v=pandp.50))

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))