---
TOCTitle: DelegateCommand Events
Title: 'DelegateCommand Events (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'Events.T:Microsoft.Practices.Prism.Commands.DelegateCommand'
ms:mtpsurl: 'delegatecommand-events-mspp-commands.md'
---

# DelegateCommand Events

The [DelegateCommand](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand) type exposes the following members.

## Events


<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.canexecutechanged">CanExecuteChanged</a></td>
<td><div class="summary">
Occurs when changes occur that affect whether or not the command should execute. You must keep a hard reference to the handler to avoid garbage collection and unexpected results. See remarks for more information.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase">DelegateCommandBase</a>.)</td>
</tr>
<tr class="even">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.isactivechanged">IsActiveChanged</a></td>
<td><div class="summary">
Fired if the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.isactive">IsActive</a> property changes.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase">DelegateCommandBase</a>.)</td>
</tr>
</tbody>
</table>

## See Also
[DelegateCommand Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
