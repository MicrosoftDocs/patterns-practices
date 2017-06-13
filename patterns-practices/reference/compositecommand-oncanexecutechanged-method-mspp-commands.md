---
TOCTitle: OnCanExecuteChanged Method
Title: 'CompositeCommand.OnCanExecuteChanged Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.OnCanExecuteChanged'
ms:mtpsurl: 'compositecommand-oncanexecutechanged-method-mspp-commands.md'
---

# CompositeCommand.OnCanExecuteChanged Method

Raises [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) on the UI thread so every command invoker can requery [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) to check if the [CompositeCommand](/patterns-practices/reference/compositecommand-class-mspp-commands) can execute.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
protected virtual void OnCanExecuteChanged()
```
```VB
'Declaration
Protected Overridable Sub OnCanExecuteChanged
```

## See Also

[CompositeCommand Class](/patterns-practices/reference/compositecommand-class-mspp-commands)<br/>
[CompositeCommand Members](/patterns-practices/reference/compositecommand-members-mspp-commands)<br/>
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>