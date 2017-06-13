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
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[Confirmation](/patterns-practices/reference/confirmation-class-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Basic implementation of [IConfirmation](/patterns-practices/reference/iconfirmation-interface-mspp-interactivity-interactionrequest).
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[InteractionRequest(Of T)](/patterns-practices/reference/interactionrequest-t-class-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Implementation of the [IInteractionRequest](/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest) interface.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[InteractionRequestedEventArgs](/patterns-practices/reference/interactionrequestedeventargs-class-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Event args for the [Raised](/patterns-practices/reference/iinteractionrequest-raised-event-mspp-interactivity-interactionrequest) event.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[InteractionRequestTrigger](/patterns-practices/reference/interactionrequesttrigger-class-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Custom event trigger for using with [IInteractionRequest](/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest) objects.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[Notification](/patterns-practices/reference/notification-class-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Basic implementation of [INotification](/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest).
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
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IConfirmation](/patterns-practices/reference/iconfirmation-interface-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Represents an interaction request used for confirmations.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IInteractionRequest](/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Represents a request from user interaction.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IInteractionRequestAware](/patterns-practices/reference/iinteractionrequestaware-interface-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Interface used by the [PopupWindowAction](/patterns-practices/reference/popupwindowaction-class-mspp-interactivity). If the DataContext object of a view that is shown with this action implements this interface it will be populated with the [INotification](/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest) data of the interaction request as well as an [Action](http://msdn.microsoft.com/en-us/library/bb534741) to finish the request upon invocation.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[INotification](/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Represents an interaction request used for notifications.
</div></td>
</tr>
</tbody>
</table>

