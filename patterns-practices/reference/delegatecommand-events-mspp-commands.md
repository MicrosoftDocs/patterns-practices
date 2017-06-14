---
TOCTitle: DelegateCommand Events
Title: 'DelegateCommand Events (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'Events.T:Microsoft.Practices.Prism.Commands.DelegateCommand'
ms:mtpsurl: 'delegatecommand-events-mspp-commands.md'
---

# DelegateCommand Events

The [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands) type exposes the following members.

## Events

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
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[CanExecuteChanged](/patterns-practices/reference/delegatecommandbase-canexecutechanged-event-mspp-commands)</td>
<td><div class="summary">
Occurs when changes occur that affect whether or not the command should execute. You must keep a hard reference to the handler to avoid garbage collection and unexpected results. See remarks for more information.
</div>
(Inherited from [DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands).)</td>
</tr>
<tr class="even">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[IsActiveChanged](/patterns-practices/reference/delegatecommandbase-isactivechanged-event-mspp-commands)</td>
<td><div class="summary">
Fired if the [IsActive](/patterns-practices/reference/delegatecommandbase-isactive-property-mspp-commands) property changes.
</div>
(Inherited from [DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands).)</td>
</tr>
</tbody>
</table>

## See Also

[DelegateCommand Class](/patterns-practices/reference/delegatecommand-class-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  