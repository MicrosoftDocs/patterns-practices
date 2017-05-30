---
TOCTitle: OnCanExecuteChanged Method
Title: 'DelegateCommandBase.OnCanExecuteChanged Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.OnCanExecuteChanged'
ms:mtpsurl: 'delegatecommandbase-oncanexecutechanged-method-mspp-commands.md'
---

# DelegateCommandBase.OnCanExecuteChanged Method

Raises [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) on the UI thread so every command invoker can requery [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093).

**Namespace:** [Microsoft.Practices.Prism.Commands](mspp-commands-namespace)

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

[DelegateCommandBase Class](delegatecommandbase-class-mspp-commands)

[DelegateCommandBase Members](delegatecommandbase-members-mspp-commands)

[Microsoft.Practices.Prism.Commands Namespace](mspp-commands-namespace)
