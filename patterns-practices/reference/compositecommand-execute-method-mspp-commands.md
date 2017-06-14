---
TOCTitle: Execute Method
Title: 'CompositeCommand.Execute Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.Execute(System.Object)'
ms:mtpsurl: 'compositecommand-execute-method-mspp-commands.md'
---

# CompositeCommand.Execute Method

Forwards [Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094) to the registered commands.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)<br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual void Execute(
	Object parameter
)
```
### Parameters

*parameter*  

Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

Data used by the command. If the command does not require data to be passed, this object can be set to **null**a null reference (**Nothing** in Visual Basic).


```VB
'Declaration
Public Overridable Sub Execute ( 
	parameter As Object
)
```

### Parameters

*parameter*  

Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

Data used by the command. If the command does not require data to be passed, this object can be set to **Nothing**a null reference (**Nothing** in Visual Basic).

### Implements

[ICommand.Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094)

## See Also

[CompositeCommand Class](/patterns-practices/reference/compositecommand-class-mspp-commands)<br/>
[CompositeCommand Members](/patterns-practices/reference/compositecommand-members-mspp-commands)<br/>
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>