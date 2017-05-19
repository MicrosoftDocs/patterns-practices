---
TOCTitle: CanExecute Method
Title: 'CompositeCommand.CanExecute Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.CanExecute(System.Object)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405748(v=PandP.50)'
---

Prism Class Library

# CompositeCommand.CanExecute Method

Forwards [CanExecute(Object)](http://msdn2.microsoft.com/en-us/library/ms604093) to the registered commands and returns **truetrue** (**True** in Visual Basic) if all of the commands return **truetrue** (**True** in Visual Basic).

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual bool CanExecute(
	Object parameter
)
```
```VB
'Declaration
Public Overridable Function CanExecute ( 
	parameter As Object
) As Boolean
```


### Parameters

*parameter*  
Type: [System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)

Data used by the command. If the command does not require data to be passed, this object can be set to **null**a null                   reference (**Nothing** in Visual Basic).

### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)

**truetrue** (**True** in Visual Basic) if all of the commands return **truetrue** (**True** in Visual Basic); otherwise, **falsefalse** (**False** in Visual Basic).
### Implements

[ICommand.CanExecute(Object)](http://msdn2.microsoft.com/en-us/library/ms604093)

## See Also


[CompositeCommand Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.compositecommand(v=pandp.50))

[CompositeCommand Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.compositecommand_members(v=pandp.50))

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))
