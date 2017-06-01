---
TOCTitle: 'DelegateCommandBase Constructor (Func(Object, Task), Func(Object, Boolean))'
Title: 'DelegateCommandBase Constructor (Func(Object, Task), Func(Object, Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.\#ctor(System.Func{System.Object,System.Threading.Tasks.Task},System.Func{System.Object,System.Boolean})'
ms:mtpsurl: 'delegatecommandbase-constructor-action-object-func-object-boolean-mspp-commands.md'
---


# DelegateCommandBase Constructor (Func&lt;Object, Task&gt;, Func&lt;Object, Boolean&gt;)

Creates a new instance of a [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase), specifying both the Execute action as an awaitable Task and the CanExecute function.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
protected DelegateCommandBase(
	Func<Object, Task> executeMethod,
	Func<Object, bool> canExecuteMethod
)
```

### Parameters

*executeMethod*  

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b), [Task](http://msdn.microsoft.com/en-us/library/dd235678)&gt;

The [Func&lt;T, TResult&gt;](http://msdn.microsoft.com/en-us/library/bb549151) to execute when [Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094) is invoked.

*canExecuteMethod*

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b), [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)&gt;

The [Func&lt;T, TResult&gt;](http://msdn.microsoft.com/en-us/library/bb549151) to invoked when [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) is invoked.

## See Also

[DelegateCommandBase Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase)

[DelegateCommandBase Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommandbase_members)

DelegateCommandBase Overload

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)



# DelegateCommandBase Constructor (Func(Of Object, Task), Func(Of Object, Boolean))

Creates a new instance of a [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase), specifying both the Execute action as an awaitable Task and the CanExecute function.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Protected Sub New ( 
	executeMethod As Func(Of Object, Task),
	canExecuteMethod As Func(Of Object, Boolean)
)
```

### Parameters

*executeMethod*  

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b), [Task](http://msdn.microsoft.com/en-us/library/dd235678))

The [Func(Of T, TResult)](http://msdn.microsoft.com/en-us/library/bb549151) to execute when [Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094) is invoked.

*canExecuteMethod*  

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b), [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50))

The [Func(Of T, TResult)](http://msdn.microsoft.com/en-us/library/bb549151) to invoked when [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) is invoked.

## See Also

[DelegateCommandBase Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase)

[DelegateCommandBase Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.delegatecommandbase_members)

DelegateCommandBase Overload

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
