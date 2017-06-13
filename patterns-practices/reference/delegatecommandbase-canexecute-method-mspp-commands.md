---
TOCTitle: CanExecute Method
Title: 'DelegateCommandBase.CanExecute Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.CanExecute(System.Object)'
ms:mtpsurl: 'delegatecommandbase-canexecute-method-mspp-commands.md'
---

# DelegateCommandBase.CanExecute Method

Determines if the command can execute with the provided parameter by invoking the [Func&lt;T, TResult&gt;](http://msdn.microsoft.com/en-us/library/bb549151) supplied during construction.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) <br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
protected bool CanExecute(
	Object parameter
)
```

### Parameters

*parameter*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
The parameter to use when determining if this command can execute.

### Return Value  
Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
Returns **truetrue** (**True** in Visual Basic) if the command can execute. **falsefalse** (**False** in Visual Basic) otherwise.

# DelegateCommandBase.CanExecute Method

Determines if the command can execute with the provided parameter by invoking the [Func(Of T, TResult)](http://msdn.microsoft.com/en-us/library/bb549151) supplied during construction.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)<br/>
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) <br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Protected Function CanExecute ( 
	parameter As Object
) As Boolean
```

### Parameters

*parameter*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
The parameter to use when determining if this command can execute.

### Return Value  
Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
Returns **Truetrue** (**True** in Visual Basic) if the command can execute. **Falsefalse** (**False** in Visual Basic) otherwise.

## See Also

[DelegateCommandBase Class](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)<br/>
[DelegateCommandBase Members](/patterns-practices/reference/delegatecommandbase-members-mspp-commands)<br/>
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>