---
TOCTitle: CanExecute Method
Title: 'DelegateCommandBase.CanExecute Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.CanExecute(System.Object)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405754(v=PandP.50)'
---

Prism Class Library

DelegateCommandBase.CanExecute Method
=========================================

Determines if the command can execute with the provided parameter by invoking the [Func&lt;(Of &lt;(T, TResult&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/bb549151) supplied during construction.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected bool CanExecute( Object parameter )Protected Function CanExecute ( parameter As Object ) As Boolean
#### Parameters

parameter  
Type: [System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
The parameter to use when determining if this command can execute.

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
Returns trueTruetruetrue (True in Visual Basic) if the command can execute. falseFalsefalsefalse (False in Visual Basic) otherwise.

See Also
--------


[DelegateCommandBase Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase)

[DelegateCommandBase Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommandbase)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
