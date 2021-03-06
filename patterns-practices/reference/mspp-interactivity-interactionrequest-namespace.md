---
TOCTitle: 'Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace'
Title: 'Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Interactivity.InteractionRequest'
ms:mtpsurl: 'mspp-interactivity-interactionrequest-namespace.md'
---

# Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace

## Classes

<table>
<thead>
<tr class="header">
<th> </th>
<th>Class</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/confirmation-class-mspp-interactivity-interactionrequest" data-raw-source="[Confirmation](/patterns-practices/reference/confirmation-class-mspp-interactivity-interactionrequest)">Confirmation</a></td>
<td><div class="summary">
Basic implementation of <a href="/patterns-practices/reference/iconfirmation-interface-mspp-interactivity-interactionrequest" data-raw-source="[IConfirmation](/patterns-practices/reference/iconfirmation-interface-mspp-interactivity-interactionrequest)">IConfirmation</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/interactionrequest-t-class-mspp-interactivity-interactionrequest" data-raw-source="[InteractionRequest(Of T)](/patterns-practices/reference/interactionrequest-t-class-mspp-interactivity-interactionrequest)">InteractionRequest(Of T)</a></td>
<td><div class="summary">
Implementation of the <a href="/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest" data-raw-source="[IInteractionRequest](/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest)">IInteractionRequest</a> interface.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/interactionrequestedeventargs-class-mspp-interactivity-interactionrequest" data-raw-source="[InteractionRequestedEventArgs](/patterns-practices/reference/interactionrequestedeventargs-class-mspp-interactivity-interactionrequest)">InteractionRequestedEventArgs</a></td>
<td><div class="summary">
Event args for the <a href="/patterns-practices/reference/iinteractionrequest-raised-event-mspp-interactivity-interactionrequest" data-raw-source="[Raised](/patterns-practices/reference/iinteractionrequest-raised-event-mspp-interactivity-interactionrequest)">Raised</a> event.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/interactionrequesttrigger-class-mspp-interactivity-interactionrequest" data-raw-source="[InteractionRequestTrigger](/patterns-practices/reference/interactionrequesttrigger-class-mspp-interactivity-interactionrequest)">InteractionRequestTrigger</a></td>
<td><div class="summary">
Custom event trigger for using with <a href="/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest" data-raw-source="[IInteractionRequest](/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest)">IInteractionRequest</a> objects.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/notification-class-mspp-interactivity-interactionrequest" data-raw-source="[Notification](/patterns-practices/reference/notification-class-mspp-interactivity-interactionrequest)">Notification</a></td>
<td><div class="summary">
Basic implementation of <a href="/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest" data-raw-source="[INotification](/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest)">INotification</a>.
</div></td>
</tr>
</tbody>
</table>

## Interfaces

<table>
<thead>
<tr class="header">
<th> </th>
<th>Interface</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iconfirmation-interface-mspp-interactivity-interactionrequest" data-raw-source="[IConfirmation](/patterns-practices/reference/iconfirmation-interface-mspp-interactivity-interactionrequest)">IConfirmation</a></td>
<td><div class="summary">
Represents an interaction request used for confirmations.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest" data-raw-source="[IInteractionRequest](/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest)">IInteractionRequest</a></td>
<td><div class="summary">
Represents a request from user interaction.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iinteractionrequestaware-interface-mspp-interactivity-interactionrequest" data-raw-source="[IInteractionRequestAware](/patterns-practices/reference/iinteractionrequestaware-interface-mspp-interactivity-interactionrequest)">IInteractionRequestAware</a></td>
<td><div class="summary">
Interface used by the <a href="/patterns-practices/reference/popupwindowaction-class-mspp-interactivity" data-raw-source="[PopupWindowAction](/patterns-practices/reference/popupwindowaction-class-mspp-interactivity)">PopupWindowAction</a>. If the DataContext object of a view that is shown with this action implements this interface it will be populated with the <a href="/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest" data-raw-source="[INotification](/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest)">INotification</a> data of the interaction request as well as an <a href="http://msdn.microsoft.com/en-us/library/bb534741" data-raw-source="[Action](http://msdn.microsoft.com/en-us/library/bb534741)">Action</a> to finish the request upon invocation.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest" data-raw-source="[INotification](/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest)">INotification</a></td>
<td><div class="summary">
Represents an interaction request used for notifications.
</div></td>
</tr>
</tbody>
</table>

