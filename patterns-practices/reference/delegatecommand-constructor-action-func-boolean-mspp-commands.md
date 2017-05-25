---
TOCTitle: 'DelegateCommand Constructor (Action, Func(Boolean))'
Title: 'DelegateCommand Constructor (Action, Func(Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand.\#ctor(System.Action,System.Func{System.Boolean})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg406161(v=PandP.50)'
---


# DelegateCommand Constructor (Action, Func(Of Boolean))

Creates a new instance of [DelegateCommand](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommand(v=pandp.50)) with the [Action](http://msdn.microsoft.com/en-us/library/bb534741) to invoke on execution and a Func to query for determining if the command can execute.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

# Syntax

```C#
public DelegateCommand(
	Action executeMethod,
	Func<bool> canExecuteMethod
)
```

```VB
'Declaration
Public Sub New ( 
	executeMethod As Action,
	canExecuteMethod As Func(Of Boolean)
)
```

### Parameters

*executeMethod*

     Type: [System.Action](http://msdn.microsoft.com/en-us/library/bb534741)
     The [Action](http://msdn.microsoft.com/en-us/library/bb534741) to invoke when [Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094) is called.

*canExecuteMethod*  

    Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of ([Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)))
    The [Func(Of (TResult))](http://msdn.microsoft.com/en-us/library/bb534960) to invoke when [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) is called

## See Also

[DelegateCommand Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommand(v=pandp.50))

[DelegateCommand Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommand_members(v=pandp.50))

DelegateCommand Overload

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))
