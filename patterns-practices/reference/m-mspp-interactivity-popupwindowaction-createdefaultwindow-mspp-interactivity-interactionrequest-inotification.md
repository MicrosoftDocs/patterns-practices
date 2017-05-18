---
TOCTitle: CreateDefaultWindow Method
Title: 'PopupWindowAction.CreateDefaultWindow Method (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Interactivity.PopupWindowAction.CreateDefaultWindow(Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683955(v=PandP.50)'
---

Prism Class Library

PopupWindowAction..::.CreateDefaultWindow Method
================================================

When no WindowContent is sent this method is used to create a default basic window to show the corresponding [INotification](https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.inotification) or [IConfirmation](https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.iconfirmation).

**Namespace:** [Microsoft.Practices.Prism.Interactivity](https://msdn.microsoft.com/n:microsoft.practices.prism.interactivity)
**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected Window CreateDefaultWindow( INotification notification )Protected Function CreateDefaultWindow ( notification As INotification ) As Window
#### Parameters

notification  
Type: [Microsoft.Practices.Prism.Interactivity.InteractionRequest..::.INotification](https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.interactionrequest.inotification)
The INotification or IConfirmation parameter to show.

#### Return Value

Type: [Window](http://msdn2.microsoft.com/en-us/library/ms590112)

See Also
--------

<span id="seeAlsoToggle"></span>
[PopupWindowAction Class](https://msdn.microsoft.com/t:microsoft.practices.prism.interactivity.popupwindowaction)

[PopupWindowAction Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.interactivity.popupwindowaction)

[Microsoft.Practices.Prism.Interactivity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.interactivity)
