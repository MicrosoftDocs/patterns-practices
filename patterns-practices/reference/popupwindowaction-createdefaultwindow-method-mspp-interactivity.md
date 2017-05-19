---
TOCTitle: CreateDefaultWindow Method
Title: 'PopupWindowAction.CreateDefaultWindow Method (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Interactivity.PopupWindowAction.CreateDefaultWindow(Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683955(v=PandP.50)'
---

Prism Class Library

PopupWindowAction.CreateDefaultWindow Method
================================================

When no WindowContent is sent this method is used to create a default basic window to show the corresponding [INotification](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.inotification(v=pandp.50)) or [IConfirmation](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.iconfirmation(v=pandp.50)).

**Namespace:** [Microsoft.Practices.Prism.Interactivity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll)

**Version:** 5.0.0.0 (5.0.0.0)


## Syntax


```C#
protected Window CreateDefaultWindow(
	INotification notification
)
```
```VB
'Declaration
Protected Function CreateDefaultWindow ( 
	notification As INotification
) As
```

#### Parameters

*notification*
  
Type: [Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.inotification(v=pandp.50))

The INotification or IConfirmation parameter to show.

#### Return Value

Type: [Window](http://msdn2.microsoft.com/en-us/library/ms590112)

See Also
--------


[PopupWindowAction Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.popupwindowaction(v=pandp.50))

[PopupWindowAction Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.popupwindowaction_members(v=pandp.50))

[Microsoft.Practices.Prism.Interactivity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity(v=pandp.50))
