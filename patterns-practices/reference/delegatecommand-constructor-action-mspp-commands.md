---
TOCTitle: 'DelegateCommand Constructor (Action)'
Title: 'DelegateCommand Constructor (Action) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand.\#ctor(System.Action)'
ms:mtpsurl: 'delegatecommand-constructor-action-func-boolean-mspp-commands.md'
---

# DelegateCommand Constructor (Action)

Creates a new instance of [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands) with the [Action](http://msdn.microsoft.com/en-us/library/bb534741) to invoke on execution.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax
```C#
public DelegateCommand(
	Action executeMethod
)
```
```VB
'Declaration
Public Sub New ( 
	executeMethod As Action
)
```

### Parameters

*executeMethod*

Type: [System.Action](http://msdn.microsoft.com/en-us/library/bb534741)

The [Action](http://msdn.microsoft.com/en-us/library/bb534741) to invoke when [Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094) is called.

## See Also
[DelegateCommand Class](/patterns-practices/reference/delegatecommand-class-mspp-commands)<br/>
[DelegateCommand Members](/patterns-practices/reference/delegatecommand-members-mspp-commands)<br/>
DelegateCommand Overload

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)