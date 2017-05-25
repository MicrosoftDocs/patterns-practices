---
TOCTitle: 'Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace'
Title: 'Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Interactivity.InteractionRequest'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419036(v=PandP.50)'
---

Prism Class Library

Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace
====================================================================

 

Classes
-------

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
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.confirmation(v=pandp.50)">Confirmation</a></td>
<td><div class="summary">
Basic implementation of <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.iconfirmation(v=pandp.50)">IConfirmation</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/gg431432(v=pandp.50)">InteractionRequest(Of T)</a></td>
<td><div class="summary">
Implementation of the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequest(v=pandp.50)">IInteractionRequest</a> interface.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.interactionrequestedeventargs(v=pandp.50)">InteractionRequestedEventArgs</a></td>
<td><div class="summary">
Event args for the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequest.raised(v=pandp.50)">Raised</a> event.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.interactionrequesttrigger(v=pandp.50)">InteractionRequestTrigger</a></td>
<td><div class="summary">
Custom event trigger for using with <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequest(v=pandp.50)">IInteractionRequest</a> objects.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.notification(v=pandp.50)">Notification</a></td>
<td><div class="summary">
Basic implementation of <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.inotification(v=pandp.50)">INotification</a>.
</div></td>
</tr>
</tbody>
</table>

Interfaces
----------

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
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.iconfirmation(v=pandp.50)">IConfirmation</a></td>
<td><div class="summary">
Represents an interaction request used for confirmations.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequest(v=pandp.50)">IInteractionRequest</a></td>
<td><div class="summary">
Represents a request from user interaction.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequestaware(v=pandp.50)">IInteractionRequestAware</a></td>
<td><div class="summary">
Interface used by the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.popupwindowaction(v=pandp.50)">PopupWindowAction</a>. If the DataContext object of a view that is shown with this action implements this interface it will be populated with the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.inotification(v=pandp.50)">INotification</a> data of the interaction request as well as an <a href="http://msdn.microsoft.com/en-us/library/bb534741">Action</a> to finish the request upon invocation.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.inotification(v=pandp.50)">INotification</a></td>
<td><div class="summary">
Represents an interaction request used for notifications.
</div></td>
</tr>
</tbody>
</table>
