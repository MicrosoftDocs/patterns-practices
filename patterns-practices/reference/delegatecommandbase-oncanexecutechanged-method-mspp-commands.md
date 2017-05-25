---
TOCTitle: OnCanExecuteChanged Method
Title: 'DelegateCommandBase.OnCanExecuteChanged Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.OnCanExecuteChanged'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommandbase.oncanexecutechanged(v=pandp.50)'
---

Prism Class Library

# DelegateCommandBase.OnCanExecuteChanged Method

Raises [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) on the UI thread so every command invoker can requery [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093).

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
protected virtual void OnCanExecuteChanged()
```

```VB
'Declaration
Protected Overridable Sub OnCanExecuteChanged
```

## See Also

[DelegateCommandBase Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommandbase(v=pandp.50))

[DelegateCommandBase Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommandbase_members(v=pandp.50))

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))
