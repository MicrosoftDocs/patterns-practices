---
TOCTitle: PrepareContentForWindow Method
Title: 'PopupWindowAction.PrepareContentForWindow Method (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Interactivity.PopupWindowAction.PrepareContentForWindow(Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification,System.Windows.Window)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736195(v=PandP.50)'
---

Prism Class Library

PopupWindowAction.PrepareContentForWindow Method
====================================================

Checks if the WindowContent or its DataContext implements [IInteractionRequestAware](https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequestaware). If so, it sets the corresponding value. Also, if WindowContent does not have a RegionManager attached, it creates a new scoped RegionManager for it.

**Namespace:** [Microsoft.Practices.Prism.Interactivity](https://msdn.microsoft.com/n:microsoft.practices.prism.interactivity)
**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected virtual void PrepareContentForWindow( INotification notification, Window wrapperWindow )Protected Overridable Sub PrepareContentForWindow ( notification As INotification, wrapperWindow As Window )
#### Parameters

notification  
Type: [Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification](https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.inotification)
The notification to be set as a DataContext in the HostWindow.

wrapperWindow  
Type: [System.Windows.Window](http://msdn2.microsoft.com/en-us/library/ms590112)
The HostWindow

See Also
--------

<span id="seeAlsoToggle"></span>
[PopupWindowAction Class](https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.popupwindowaction)

[PopupWindowAction Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.interactivity.popupwindowaction)

[Microsoft.Practices.Prism.Interactivity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.interactivity)
