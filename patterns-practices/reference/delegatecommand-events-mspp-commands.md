---
TOCTitle: DelegateCommand Events
Title: 'DelegateCommand Events (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'Events.T:Microsoft.Practices.Prism.Commands.DelegateCommand'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405731(v=PandP.50)'
---

Prism Class Library

DelegateCommand Events
======================

The [DelegateCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand) type exposes the following members.

Events
------

<span id="eventTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg405731.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/e:microsoft.practices.prism.commands.delegatecommandbase.canexecutechanged">CanExecuteChanged</a></td>
<td><div class="summary">
Occurs when changes occur that affect whether or not the command should execute. You must keep a hard reference to the handler to avoid garbage collection and unexpected results. See remarks for more information.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase">DelegateCommandBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg405731.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/e:microsoft.practices.prism.commands.delegatecommandbase.isactivechanged">IsActiveChanged</a></td>
<td><div class="summary">
Fired if the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.commands.delegatecommandbase.isactive">IsActive</a> property changes.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase">DelegateCommandBase</a>.)</td>
</tr>
</tbody>
</table>

See Also
--------

<span id="seeAlsoToggle"></span>
[DelegateCommand Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
