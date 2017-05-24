---
TOCTitle: 'DelegateCommand(T) Constructor (Action(T), Func(T, Boolean))'
Title: 'DelegateCommand(T) Constructor (Action(T), Func(T, Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.\#ctor(System.Action{\`0},System.Func{\`0,System.Boolean})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg406162(v=PandP.50)'
---

Prism Class Library

DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Constructor (Action&lt;(Of &lt;(T&gt;)&gt;), Func&lt;(Of &lt;(T, Boolean&gt;)&gt;))
===========================================================================================================================

Initializes a new instance of [DelegateCommand&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand%601).

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public DelegateCommand( Action&lt;T&gt; executeMethod, Func&lt;T, bool&gt; canExecuteMethod )Public Sub New ( executeMethod As Action(Of T), canExecuteMethod As Func(Of T, Boolean) )
#### Parameters

executeMethod  
Type: [System..::.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([T](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand%601)&gt;)&gt;)
Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

<!-- -->

canExecuteMethod  
Type: [System..::.Func](http://msdn2.microsoft.com/en-us/library/bb549151)&lt;(Of &lt;([T](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand%601), [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)&gt;)&gt;)
Delegate to execute when CanExecute is called on the command. This can be null.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                                                     |
|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| [System..::.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | When both executeMethod and canExecuteMethod ar nullNothingnullptra null reference (Nothing in Visual Basic). |

See Also
--------

<span id="seeAlsoToggle"></span>
[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand%601)

[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommand%601)

[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.commands.delegatecommand%601.)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
