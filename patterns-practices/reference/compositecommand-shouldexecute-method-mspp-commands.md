---
TOCTitle: ShouldExecute Method
Title: 'CompositeCommand.ShouldExecute Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.CompositeCommand.ShouldExecute(System.Windows.Input.ICommand)'
ms:mtpsurl: 'compositecommand-shouldexecute-method-mspp-commands.md'
---


# CompositeCommand.ShouldExecute Method

Evaluates if a command should execute.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax
```C#
protected virtual bool ShouldExecute( ICommand command )
```

## Parameters

*command*  
Type: [System.Windows.Input.ICommand](http://msdn.microsoft.com/en-us/library/ms616869)  
The command to evaluate.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)   
A [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50) value indicating whether the command should be used when evaluating [CanExecute(Object)](/patterns-practices/reference/compositecommand-canexecute-method-mspp-commands) and [Execute(Object)](/patterns-practices/reference/compositecommand-execute-method-mspp-commands).

## Remarks

 If this command is set to monitor command activity, and command implements the [!:IActiveAwareCommand\] interface, this method will return **falsefalse** (**False** in Visual Basic) if the command's [!:IActiveAwareCommand.IsActive\] property is **falsefalse** (**False** in Visual Basic); otherwise it always returns **truetrue** (**True** in Visual Basic).
 
```VB
Protected Overridable Function ShouldExecute ( command As ICommand ) As Boolean
```

### Parameters

*command*  
Type: [System.Windows.Input.ICommand](http://msdn.microsoft.com/en-us/library/ms616869)  
The command to evaluate.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)    
A [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50) value indicating whether the command should be used when evaluating [CanExecute(Object)](/patterns-practices/reference/compositecommand-canexecute-method-mspp-commands) and [Execute(Object)](/patterns-practices/reference/compositecommand-execute-method-mspp-commands).

## Remarks

 If this command is set to monitor command activity, and command implements the [!:IActiveAwareCommand\] interface, this method will return **Falsefalse** (**False** in Visual Basic) if the command's [!:IActiveAwareCommand.IsActive\] property is **Falsefalse** (**False** in Visual Basic); otherwise it always returns **Truetrue** (**True** in Visual Basic).
 

## See Also

[CompositeCommand Class](/patterns-practices/reference/compositecommand-class-mspp-commands)

[CompositeCommand Members](/patterns-practices/reference/compositecommand-members-mspp-commands)

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)
