---
TOCTitle: 'DelegateCommandBase Constructor (Action(Object), Func(Object, Boolean))'
Title: 'DelegateCommandBase Constructor (Action(Object), Func(Object, Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.\#ctor(System.Action{System.Object},System.Func{System.Object,System.Boolean})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg406160(v=PandP.50)'
---

Prism Class Library

DelegateCommandBase Constructor (Action&lt;(Of &lt;(Object&gt;)&gt;), Func&lt;(Of &lt;(Object, Boolean&gt;)&gt;))
=================================================================================================================

Creates a new instance of a [DelegateCommandBase](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase), specifying both the execute action and the can execute function.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected DelegateCommandBase( Action&lt;Object&gt; executeMethod, Func&lt;Object, bool&gt; canExecuteMethod )Protected Sub New ( executeMethod As Action(Of Object), canExecuteMethod As Func(Of Object, Boolean) )
#### Parameters

executeMethod  
Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)&gt;)&gt;)
The [Action](http://msdn2.microsoft.com/en-us/library/bb534741) to execute when [Execute(Object)](http://msdn2.microsoft.com/en-us/library/ms604094) is invoked.

canExecuteMethod  
Type: [System.Func](http://msdn2.microsoft.com/en-us/library/bb549151)&lt;(Of &lt;([Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b), [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)&gt;)&gt;)
The [Func&lt;(Of &lt;(T, TResult&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/bb549151) to invoked when [CanExecute(Object)](http://msdn2.microsoft.com/en-us/library/ms604093) is invoked.

See Also
--------


[DelegateCommandBase Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase)

[DelegateCommandBase Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommandbase)

[DelegateCommandBase Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.commands.delegatecommandbase.)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
