---
TOCTitle: 'Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace'
Title: 'Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Interactivity.InteractionRequest'
ms:mtpsurl: 'mspp-interactivity-interactionrequest-namespace.md'
---

# Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace

 

## Classes

<span id="classToggle"></span>
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
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="confirmation-class-mspp-interactivity-interactionrequest.md">Confirmation</a></td>
<td><div class="summary">
Basic implementation of <a href="iconfirmation-interface-mspp-interactivity-interactionrequest.md">IConfirmation</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="interactionrequest-t-class-mspp-interactivity-interactionrequest.md">InteractionRequest(Of T)</a></td>
<td><div class="summary">
Implementation of the <a href="iinteractionrequest-interface-mspp-interactivity-interactionrequest.md">IInteractionRequest</a> interface.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="interactionrequestedeventargs-class-mspp-interactivity-interactionrequest.md">InteractionRequestedEventArgs</a></td>
<td><div class="summary">
Event args for the <a href="iinteractionrequest-raised-event-mspp-interactivity-interactionrequest.md">Raised</a> event.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="interactionrequesttrigger-class-mspp-interactivity-interactionrequest.md">InteractionRequestTrigger</a></td>
<td><div class="summary">
Custom event trigger for using with <a href="iinteractionrequest-interface-mspp-interactivity-interactionrequest.md">IInteractionRequest</a> objects.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="notification-class-mspp-interactivity-interactionrequest.md">Notification</a></td>
<td><div class="summary">
Basic implementation of <a href="inotification-interface-mspp-interactivity-interactionrequest.md">INotification</a>.
</div></td>
</tr>
</tbody>
</table>

## Interfaces

<span id="interfaceToggle"></span>
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
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="iconfirmation-interface-mspp-interactivity-interactionrequest.md">IConfirmation</a></td>
<td><div class="summary">
Represents an interaction request used for confirmations.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="iinteractionrequest-interface-mspp-interactivity-interactionrequest.md">IInteractionRequest</a></td>
<td><div class="summary">
Represents a request from user interaction.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="iinteractionrequestaware-interface-mspp-interactivity-interactionrequest.md">IInteractionRequestAware</a></td>
<td><div class="summary">
Interface used by the <a href="popupwindowaction-class-mspp-interactivity.md">PopupWindowAction</a>. If the DataContext object of a view that is shown with this action implements this interface it will be populated with the <a href="inotification-interface-mspp-interactivity-interactionrequest.md">INotification</a> data of the interaction request as well as an <a href="http://msdn.microsoft.com/en-us/library/bb534741">Action</a> to finish the request upon invocation.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="inotification-interface-mspp-interactivity-interactionrequest.md">INotification</a></td>
<td><div class="summary">
Represents an interaction request used for notifications.
</div></td>
</tr>
</tbody>
</table>
