---
TOCTitle: CanExecute Method
Title: 'CompositeCommand.CanExecute Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.CanExecute(System.Object)'
ms:mtpsurl: 'compositecommand-canexecute-method-mspp-commands.md'
---

# CompositeCommand.CanExecute Method

Forwards [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) to the registered commands and returns **truetrue** (**True** in Visual Basic) if all of the commands return **truetrue** (**True** in Visual Basic).

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)<br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual bool CanExecute(
	Object parameter
)
```

### Parameters

*parameter*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

Data used by the command. If the command does not require data to be passed, this object can be set to **null**a null reference (**Nothing** in Visual Basic).

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

**truetrue** (**True** in Visual Basic) if all of the commands return **truetrue** (**True** in Visual Basic); otherwise, **falsefalse** (**False** in Visual Basic).

## Syntax

```VB
'Declaration
Public Overridable Function CanExecute ( 
	parameter As Object
) As Boolean
```

### Parameters

*parameter*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

Data used by the command. If the command does not require data to be passed, this object can be set to **Nothing**a null reference (**Nothing** in Visual Basic).

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

**Truetrue** (**True** in Visual Basic) if all of the commands return **Truetrue** (**True** in Visual Basic); otherwise, **Falsefalse** (**False** in Visual Basic).

### Implements

[ICommand.CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093)

## See Also

[CompositeCommand Class](/patterns-practices/reference/compositecommand-class-mspp-commands)<br/>
[CompositeCommand Members](/patterns-practices/reference/compositecommand-members-mspp-commands)<br/>
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>