---
TOCTitle: 'DelegateCommandBase Constructor (Func(Object, Task), Func(Object, Boolean))'
Title: 'DelegateCommandBase Constructor (Func(Object, Task), Func(Object, Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.\#ctor(System.Func{System.Object,System.Threading.Tasks.Task},System.Func{System.Object,System.Boolean})'
ms:mtpsurl: 'delegatecommandbase-constructor-action-object-func-object-boolean-mspp-commands.md'
---

Prism Class Library

DelegateCommandBase Constructor (Func&lt;(Of &lt;(Object, Task&gt;)&gt;), Func&lt;(Of &lt;(Object, Boolean&gt;)&gt;))
=====================================================================================================================

Creates a new instance of a [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase), specifying both the Execute action as an awaitable Task and the CanExecute function.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


protected DelegateCommandBase( Func&lt;Object, Task&gt; executeMethod, Func&lt;Object, bool&gt; canExecuteMethod )Protected Sub New ( executeMethod As Func(Of Object, Task), canExecuteMethod As Func(Of Object, Boolean) )

### Parameters

executeMethod  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;(Of &lt;([Object](http://msdn.microsoft.com/en-us/library/e5kfa45b), [Task](http://msdn.microsoft.com/en-us/library/dd235678)&gt;)&gt;)
The [Func&lt;(Of &lt;(T, TResult&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bb549151) to execute when [Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094) is invoked.

canExecuteMethod  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;(Of &lt;([Object](http://msdn.microsoft.com/en-us/library/e5kfa45b), [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)&gt;)&gt;)
The [Func&lt;(Of &lt;(T, TResult&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bb549151) to invoked when [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) is invoked.

See Also
--------


[DelegateCommandBase Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase)

[DelegateCommandBase Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommandbase)

[DelegateCommandBase Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.commands.delegatecommandbase.)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
