---
TOCTitle: 'DelegateCommand(T) Class'
Title: 'DelegateCommand(T) Class (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'T:Microsoft.Practices.Prism.Commands.DelegateCommand\`1'
ms:mtpsurl: 'delegatecommand-t-class-mspp-commands.md'
---


# DelegateCommand&lt;T&gt; Class

An [ICommand](http://msdn.microsoft.com/en-us/library/ms616869) whose delegates can be attached for [Execute(T)](/patterns-practices/reference/delegatecommand-t-execute-method-t-mspp-commands) and [CanExecute(T)](/patterns-practices/reference/delegatecommand-t-canexecute-method-t-mspp-commands).

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax
```C#
public class DelegateCommand<T> : DelegateCommandBase
```

## Type Parameters


*T*  
Parameter type.

## Remarks

 The constructor deliberately prevents the use of value types. Because ICommand takes an object, having a value type for T would cause unexpected behavior when CanExecute(null) is called during XAML initialization for command bindings. Using default(T) was considered and rejected as a solution because the implementor would not be able to distinguish between a valid and defaulted values.

Instead, callers should support a value type by using a nullable value type and checking the HasValue property before using the Value property.

## Examples

```
public MyClass()
{
    this.submitCommand = new DelegateCommand<int?>(this.Submit, this.CanSubmit);
}

private bool CanSubmit(int? customerId)
{
    return (customerId.HasValue && customers.Contains(customerId.Value));
}
```
## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  [Microsoft-Practices-Prism-Commands-DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)
    Microsoft.Practices.Prism.Commands.DelegateCommand&lt;T&gt;

## See Also

[DelegateCommand&lt;T&gt; Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)

-------------------

# DelegateCommand(Of T) Class

An [ICommand](http://msdn.microsoft.com/en-us/library/ms616869) whose delegates can be attached for [Execute(T)](/patterns-practices/reference/delegatecommand-t-execute-method-t-mspp-commands) and [CanExecute(T)](/patterns-practices/reference/delegatecommand-t-canexecute-method-t-mspp-commands).

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Class DelegateCommand(Of T)
	Inherits DelegateCommandBase
```
## Type Parameters


*T*  
Parameter type.

## Remarks

 The constructor deliberately prevents the use of value types. Because ICommand takes an object, having a value type for T would cause unexpected behavior when CanExecute(null) is called during XAML initialization for command bindings. Using default(T) was considered and rejected as a solution because the implementor would not be able to distinguish between a valid and defaulted values.

Instead, callers should support a value type by using a nullable value type and checking the HasValue property before using the Value property.

## Examples

```
public MyClass()
{
    this.submitCommand = new DelegateCommand<int?>(this.Submit, this.CanSubmit);
}

private bool CanSubmit(int? customerId)
{
    return (customerId.HasValue && customers.Contains(customerId.Value));
}
```
## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  [Microsoft-Practices-Prism-Commands-DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)
    Microsoft.Practices.Prism.Commands.DelegateCommand(Of T)

## See Also

[DelegateCommand(Of T) Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)