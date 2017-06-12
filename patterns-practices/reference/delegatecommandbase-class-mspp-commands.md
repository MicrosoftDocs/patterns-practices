---
TOCTitle: DelegateCommandBase Class
Title: 'DelegateCommandBase Class (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'T:Microsoft.Practices.Prism.Commands.DelegateCommandBase'
ms:mtpsurl: 'delegatecommandbase-class-mspp-commands.md'
---


# DelegateCommandBase Class

An [ICommand](http://msdn.microsoft.com/en-us/library/ms616869) whose delegates can be attached for [Execute(Object)](/patterns-practices/reference/delegatecommandbase-execute-method-mspp-commands) and [CanExecute(Object)](/patterns-practices/reference/delegatecommandbase-canexecute-method-mspp-commands).

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax
```C#
public abstract class DelegateCommandBase : ICommand, 
	IActiveAware
```
## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)   
  Microsoft.Practices.Prism.Commands.DelegateCommandBase   
    [Microsoft-Practices-Prism-Commands-DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)   
    [Microsoft.Practices.Prism.Commands.DelegateCommand&lt;T&gt;](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)

```VB
'Declaration
Public Class DelegateCommand
	Inherits DelegateCommandBase
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)   
  Microsoft.Practices.Prism.Commands.DelegateCommandBase   
    [Microsoft-Practices-Prism-Commands-DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)   
    [Microsoft.Practices.Prism.Commands.DelegateCommand(Of T)](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)

## See Also

[DelegateCommandBase Members](/patterns-practices/reference/delegatecommandbase-members-mspp-commands)<br/>
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>