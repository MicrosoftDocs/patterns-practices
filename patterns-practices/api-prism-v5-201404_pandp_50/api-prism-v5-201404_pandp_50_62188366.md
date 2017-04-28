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
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Class</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419036.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.confirmation">Confirmation</a></td>
<td><div class="summary">
Basic implementation of <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.iconfirmation">IConfirmation</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419036.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.interactionrequest%601">InteractionRequest&lt;(Of &lt;(T&gt;)&gt;)</a></td>
<td><div class="summary">
Implementation of the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequest">IInteractionRequest</a> interface.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419036.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.interactionrequestedeventargs">InteractionRequestedEventArgs</a></td>
<td><div class="summary">
Event args for the <a href="https://msdn.microsoft.com/e:microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequest.raised">Raised</a> event.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419036.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.interactionrequesttrigger">InteractionRequestTrigger</a></td>
<td><div class="summary">
Custom event trigger for using with <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequest">IInteractionRequest</a> objects.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419036.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.notification">Notification</a></td>
<td><div class="summary">
Basic implementation of <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.inotification">INotification</a>.
</div></td>
</tr>
</tbody>
</table>

Interfaces
----------

<span id="interfaceToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Interface</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419036.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.iconfirmation">IConfirmation</a></td>
<td><div class="summary">
Represents an interaction request used for confirmations.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419036.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequest">IInteractionRequest</a></td>
<td><div class="summary">
Represents a request from user interaction.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419036.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequestaware">IInteractionRequestAware</a></td>
<td><div class="summary">
Interface used by the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.popupwindowaction">PopupWindowAction</a>. If the DataContext object of a view that is shown with this action implements this interface it will be populated with the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.inotification">INotification</a> data of the interaction request as well as an <a href="http://msdn2.microsoft.com/en-us/library/bb534741">Action</a> to finish the request upon invocation.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419036.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.inotification">INotification</a></td>
<td><div class="summary">
Represents an interaction request used for notifications.
</div></td>
</tr>
</tbody>
</table>
