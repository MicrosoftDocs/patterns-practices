---
TOCTitle: 'DelegateCommand(T) Events'
Title: 'DelegateCommand(T) Events (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'Events.T:Microsoft.Practices.Prism.Commands.DelegateCommand\`1'
ms:mtpsurl: 'delegatecommand-t-events-mspp-commands.md'
---

# DelegateCommand&lt;T&gt; Events

The [DelegateCommand&lt;T&gt;](/patterns-practices/reference/delegatecommand-t-class-mspp-commands) type exposes the following members.

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
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-canexecutechanged-event-mspp-commands" data-raw-source="[CanExecuteChanged](/patterns-practices/reference/delegatecommandbase-canexecutechanged-event-mspp-commands)">CanExecuteChanged</a></td>
<td><div class="summary">
Occurs when changes occur that affect whether or not the command should execute. You must keep a hard reference to the handler to avoid garbage collection and unexpected results. See remarks for more information.
</div>
(Inherited from <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">DelegateCommandBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-isactivechanged-event-mspp-commands" data-raw-source="[IsActiveChanged](/patterns-practices/reference/delegatecommandbase-isactivechanged-event-mspp-commands)">IsActiveChanged</a></td>
<td><div class="summary">
Fired if the <a href="/patterns-practices/reference/delegatecommandbase-isactive-property-mspp-commands" data-raw-source="[IsActive](/patterns-practices/reference/delegatecommandbase-isactive-property-mspp-commands)">IsActive</a> property changes.
</div>
(Inherited from <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">DelegateCommandBase</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[DelegateCommand&lt;T&gt; Class](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  