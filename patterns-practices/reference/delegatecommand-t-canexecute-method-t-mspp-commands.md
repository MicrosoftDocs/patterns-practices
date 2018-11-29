---
TOCTitle: 'CanExecute Method (T)'
Title: 'DelegateCommand(T).CanExecute Method (T) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.CanExecute(\`0)'
ms:mtpsurl: 'delegatecommand-t-canexecute-method-t-mspp-commands.md'
---

# DelegateCommand&lt;T&gt;.CanExecute Method (T)

Determines if the command can execute by invoked the [Func&lt;T, TResult&gt;](http://msdn.microsoft.com/en-us/library/bb549151) provided during construction.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual bool CanExecute(
	T parameter
)
```

### Parameters

*parameter*  
Type: [T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)  
Data used by the command to determine if it can execute.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
**truetrue** (**True** in Visual Basic) if this command can be executed; otherwise, **falsefalse** (**False** in Visual Basic).

## See Also

[DelegateCommand&lt;T&gt; Class](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)  
[DelegateCommand&lt;T&gt; Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)  
[CanExecute Overload](/patterns-practices/reference/delegatecommand-t-canexecute-method-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  


# DelegateCommand(Of T).CanExecute Method (T)

Determines if the command can execute by invoked the [Func(Of T, TResult)](http://msdn.microsoft.com/en-us/library/bb549151) provided during construction.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Overridable Function CanExecute ( 
	parameter As T
) As Boolean
```

### Parameters

*parameter*  
Type: [T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)  
Data used by the command to determine if it can execute.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
**Truetrue** (**True** in Visual Basic) if this command can be executed; otherwise, **Falsefalse** (**False** in Visual Basic).

## See Also

[DelegateCommand(Of T) Class](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)  
[DelegateCommand(Of T) Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)  
[CanExecute Overload](/patterns-practices/reference/delegatecommand-t-canexecute-method-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  