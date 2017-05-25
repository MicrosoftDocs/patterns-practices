---
TOCTitle: 'DelegateCommand(T) Constructor (Action(T))'
Title: 'DelegateCommand(T) Constructor (Action(T)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.\#ctor(System.Action{\`0})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/gg405544(v=pandp.50)'
---

Prism Class Library

DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Constructor (Action&lt;(Of &lt;(T&gt;)&gt;))
====================================================================================

Initializes a new instance of [DelegateCommand&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601).

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


public DelegateCommand( Action&lt;T&gt; executeMethod )Public Sub New ( executeMethod As Action(Of T) )

### Parameters

executeMethod  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([T](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601)&gt;)&gt;)
Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

Remarks
-------

[CanExecute(T)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601.canexecute(%600)) will always return true.

See Also
--------


[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601)

[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.delegatecommand%601)

[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.commands.delegatecommand%601.)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
