---
TOCTitle: CompositeCommand Events
Title: 'CompositeCommand Events (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'Events.T:Microsoft.Practices.Prism.Commands.CompositeCommand'
ms:mtpsurl: 'compositecommand-events-mspp-commands.md'
---

# CompositeCommand Events

The [CompositeCommand](/patterns-practices/reference/compositecommand-class-mspp-commands) type exposes the following members.

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
<td>[CanExecuteChanged](/patterns-practices/reference/compositecommand-canexecutechanged-event-mspp-commands)</td>
<td><div class="summary">
Occurs when any of the registered commands raise [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106). You must keep a hard reference to the handler to avoid garbage collection and unexpected results. See remarks for more information.
</div></td>
</tr>
</tbody>
</table>

## See Also

[CompositeCommand Class](/patterns-practices/reference/compositecommand-class-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  