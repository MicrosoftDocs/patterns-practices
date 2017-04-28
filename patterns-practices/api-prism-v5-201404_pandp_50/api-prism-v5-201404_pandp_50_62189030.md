---
TOCTitle: DelegateCommand Events
Title: 'DelegateCommand Events (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'Events.T:Microsoft.Practices.Prism.Commands.DelegateCommand'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405731(v=PandP.50)'
---

Prism Class Library

DelegateCommand Events
======================

Include Protected Members
Include Inherited Members

The [DelegateCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand) type exposes the following members.

Events
------

<span id="eventTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg405731.pubevent(en-us,PandP.50).gif "Public event")
[CanExecuteChanged](https://msdn.microsoft.com/e:microsoft.practices.prism.commands.delegatecommandbase.canexecutechanged)
Occurs when changes occur that affect whether or not the command should execute. You must keep a hard reference to the handler to avoid garbage collection and unexpected results. See remarks for more information.

(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase).)
![](https://msdn.microsoft.com/en-us/Gg405731.pubevent(en-us,PandP.50).gif "Public event")
[IsActiveChanged](https://msdn.microsoft.com/e:microsoft.practices.prism.commands.delegatecommandbase.isactivechanged)
Fired if the [IsActive](https://msdn.microsoft.com/p:microsoft.practices.prism.commands.delegatecommandbase.isactive) property changes.

(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase).)

See Also
--------

<span id="seeAlsoToggle"></span>
[DelegateCommand Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
