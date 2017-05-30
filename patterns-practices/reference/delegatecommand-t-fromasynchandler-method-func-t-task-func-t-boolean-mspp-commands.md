---
TOCTitle: 'FromAsyncHandler Method (Func(T, Task), Func(T, Boolean))'
Title: 'DelegateCommand(T).FromAsyncHandler Method (Func(T, Task), Func(T, Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.FromAsyncHandler(System.Func{\`0,System.Threading.Tasks.Task},System.Func{\`0,System.Boolean})'
ms:mtpsurl: 'delegatecommand-t-fromasynchandler-method-func-t-task-func-t-boolean-mspp-commands.md'
---

# DelegateCommand(Of T).FromAsyncHandler Method (Func(Of T, Task), Func(Of T, Boolean))

Factory method to create a new instance of [DelegateCommand(Of T)](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50)) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax
```VB
'Declaration
Public Shared Function FromAsyncHandler ( 
	executeMethod As Func(Of T, Task),
	canExecuteMethod As Func(Of T, Boolean)
) As DelegateCommand(Of T)
```

### Parameters

*executeMethod* 

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)(Of [T](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50)), [Task](http://msdn.microsoft.com/en-us/library/dd235678))

Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

*canExecuteMethod*

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)(Of [T](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50)), [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50))

Delegate to execute when CanExecute is called on the command. This can be null.

### Return Value

Type: [DelegateCommand](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50))(Of [T](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50)))

Constructed instance of [DelegateCommand(Of T)](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50))

## See Also
[DelegateCommand(Of T) Class](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50))

[DelegateCommand(Of T) Members](https://msdn.microsoft.com/en-us/library/gg430763(v=pandp.50))

[FromAsyncHandler Overload](https://msdn.microsoft.com/en-us/library/dn736124(v=pandp.50))

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)


-------------------------
# DelegateCommand&lt; T&GT;.FromAsyncHandler Method (Func&lt;T, Task&gt;, Func&lt;T, Boolean&gt;)

Factory method to create a new instance of [DelegateCommand&lt;T&GT;](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50)) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax
```C#
public static DelegateCommand<T> FromAsyncHandler(
	Func<T, Task> executeMethod,
	Func<T, bool> canExecuteMethod
)
```
### Parameters

*executeMethod* 

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;[T](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50)), [Task](http://msdn.microsoft.com/en-us/library/dd235678)&gt;

Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

*canExecuteMethod*

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;[T](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50)), [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)&gt;

Delegate to execute when CanExecute is called on the command. This can be null.

### Return Value

Type: [DelegateCommand](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50))&lt;[T](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50))&gt;

Constructed instance of [DelegateCommand&lt;T&GT;](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50))

## See Also
[DelegateCommand&lt; T&GT; Class](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50))

[DelegateCommand&lt; T&GT; Members](https://msdn.microsoft.com/en-us/library/gg430763(v=pandp.50))

[FromAsyncHandler Overload](https://msdn.microsoft.com/en-us/library/dn736124(v=pandp.50))

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)

