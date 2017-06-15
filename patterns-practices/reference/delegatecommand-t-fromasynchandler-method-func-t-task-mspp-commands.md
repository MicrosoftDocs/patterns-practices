---
TOCTitle: 'FromAsyncHandler Method (Func(T, Task))'
Title: 'DelegateCommand(T).FromAsyncHandler Method (Func(T, Task)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.FromAsyncHandler(System.Func{\`0,System.Threading.Tasks.Task})'
ms:mtpsurl: 'delegatecommand-t-fromasynchandler-method-func-t-task-mspp-commands.md'
---

# DelegateCommand&lt;T&gt;.FromAsyncHandler Method (Func&lt;T, Task&gt;)

Factory method to create a new instance of [DelegateCommand&lt;T&gt;](/patterns-practices/reference/delegatecommand-t-class-mspp-commands) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public static DelegateCommand<T> FromAsyncHandler(
	Func<T, Task> executeMethod
)
```

### Parameters

*executeMethod*  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;[T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands), [Task](http://msdn.microsoft.com/en-us/library/dd235678)&gt;  
Delegate to execute when Execute is called on the command.

### Return Value

Type: [DelegateCommand](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)&lt;[T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)&gt;  
Constructed instance of [DelegateCommand&lt;T&gt;](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)

## See Also

[DelegateCommand&lt;T&gt; Class](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)  
[DelegateCommand&lt;T&gt; Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)  
[FromAsyncHandler Overload](/patterns-practices/reference/delegatecommand-t-fromasynchandler-method-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  


# DelegateCommand(Of T).FromAsyncHandler Method (Func(Of T, Task))


Factory method to create a new instance of [DelegateCommand(Of T)](/patterns-practices/reference/delegatecommand-t-class-mspp-commands) from an awaitable handler method.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Shared Function FromAsyncHandler ( 
	executeMethod As Func(Of T, Task)
) As DelegateCommand(Of T)
```

### Parameters

*executeMethod*  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)(Of [T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands), [Task](http://msdn.microsoft.com/en-us/library/dd235678))  
Delegate to execute when Execute is called on the command.

### Return Value

Type: [DelegateCommand](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)(Of [T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands))  
Constructed instance of [DelegateCommand(Of T)](/patterns-practices/reference/delegatecommand-t-class-mspp-commands))

## See Also

[DelegateCommand(Of T) Class](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)  
[DelegateCommand(Of T) Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)  
[FromAsyncHandler Overload](/patterns-practices/reference/delegatecommand-t-fromasynchandler-method-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)