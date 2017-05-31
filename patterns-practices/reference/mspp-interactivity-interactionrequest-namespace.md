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
<td>![Public class](/images/public-class.gif)</td>
<td><a href="/patterns-practices/reference/confirmation-class-mspp-interactivity-interactionrequest">Confirmation</a></td>
<td><div class="summary">
Basic implementation of <a href="/patterns-practices/reference/iconfirmation-interface-mspp-interactivity-interactionrequest">IConfirmation</a>.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="/patterns-practices/reference/interactionrequest-t-class-mspp-interactivity-interactionrequest">InteractionRequest(Of T)</a></td>
<td><div class="summary">
Implementation of the <a href="/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest">IInteractionRequest</a> interface.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="/patterns-practices/reference/interactionrequestedeventargs-class-mspp-interactivity-interactionrequest">InteractionRequestedEventArgs</a></td>
<td><div class="summary">
Event args for the <a href="/patterns-practices/reference/iinteractionrequest-raised-event-mspp-interactivity-interactionrequest">Raised</a> event.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="/patterns-practices/reference/interactionrequesttrigger-class-mspp-interactivity-interactionrequest">InteractionRequestTrigger</a></td>
<td><div class="summary">
Custom event trigger for using with <a href="/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest">IInteractionRequest</a> objects.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="/patterns-practices/reference/notification-class-mspp-interactivity-interactionrequest">Notification</a></td>
<td><div class="summary">
Basic implementation of <a href="/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest">INotification</a>.
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
<td>![Public interface](/images/public-interface.gif)</td>
<td><a href="/patterns-practices/reference/iconfirmation-interface-mspp-interactivity-interactionrequest">IConfirmation</a></td>
<td><div class="summary">
Represents an interaction request used for confirmations.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/images/public-interface.gif)</td>
<td><a href="/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest">IInteractionRequest</a></td>
<td><div class="summary">
Represents a request from user interaction.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/images/public-interface.gif)</td>
<td><a href="/patterns-practices/reference/iinteractionrequestaware-interface-mspp-interactivity-interactionrequest">IInteractionRequestAware</a></td>
<td><div class="summary">
Interface used by the <a href="/patterns-practices/reference/popupwindowaction-class-mspp-interactivity">PopupWindowAction</a>. If the DataContext object of a view that is shown with this action implements this interface it will be populated with the <a href="/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest">INotification</a> data of the interaction request as well as an [Action](http://msdn.microsoft.com/en-us/library/bb534741) to finish the request upon invocation.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/images/public-interface.gif)</td>
<td>[INotification](/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Represents an interaction request used for notifications.
</div></td>
</tr>
</tbody>
</table>
