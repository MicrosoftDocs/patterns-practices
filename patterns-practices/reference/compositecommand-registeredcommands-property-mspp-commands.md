---
TOCTitle: RegisteredCommands Property
Title: 'CompositeCommand.RegisteredCommands Property (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'P:Microsoft.Practices.Prism.Commands.CompositeCommand.RegisteredCommands'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431239(v=PandP.50)'
---

Prism Class Library

CompositeCommand.RegisteredCommands Property
================================================

Gets the list of all the registered commands.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public IList&lt;ICommand&gt; RegisteredCommands { get; }Public ReadOnly Property RegisteredCommands As IList(Of ICommand) Get
#### Property Value

Type: [IList](http://msdn2.microsoft.com/en-us/library/5y536ey6)&lt;(Of &lt;([ICommand](http://msdn2.microsoft.com/en-us/library/ms616869)&gt;)&gt;)
A list of registered commands.

Remarks
-------

<span id="remarksToggle"></span>This returns a copy of the commands subscribed to the CompositeCommand.

See Also
--------


[CompositeCommand Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.compositecommand)

[CompositeCommand Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.compositecommand)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
