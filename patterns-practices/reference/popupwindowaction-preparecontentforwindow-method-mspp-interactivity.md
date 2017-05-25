---
TOCTitle: PrepareContentForWindow Method
Title: 'PopupWindowAction.PrepareContentForWindow Method (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Interactivity.PopupWindowAction.PrepareContentForWindow(Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification,System.Windows.Window)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736195(v=PandP.50)'
---

# PopupWindowAction.PrepareContentForWindow Method

# Checks if the WindowContent or its DataContext implements [IInteractionRequestAware](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequestaware(v=pandp.50)). If so, it sets the corresponding value. Also, if WindowContent does not have a RegionManager attached, it creates a new scoped RegionManager for it.
# PopupWindowAction.PrepareContentForWindow Method


**Namespace:** [Microsoft.Practices.Prism.Interactivity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity(v=pandp.50))


**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual void PrepareContentForWindow(
	INotification notification,
	Window wrapperWindow
)
```
```VB
'Declaration
Protected Overridable Sub PrepareContentForWindow ( 
	notification As INotification,
	wrapperWindow As Window
)
```

### Parameters

*notification*

Type: [Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.popupwindowaction(v=pandp.50))

The notification to be set as a DataContext in the HostWindow.

*wrapperWindow*

Type: [System.Windows.Window](http://msdn2.microsoft.com/en-us/library/ms590112)
# 
**Namespace:** [Microsoft.Practices.Prism.Interactivity](https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity)
**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

protected virtual void PrepareContentForWindow( INotification notification, Window wrapperWindow )Protected Overridable Sub PrepareContentForWindow ( notification As INotification, wrapperWindow As Window )

### Parameters

notification  
Type: [Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification](https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.interactionrequest.inotification)
The notification to be set as a DataContext in the HostWindow.

wrapperWindow  
Type: [System.Windows.Window](http://msdn.microsoft.com/en-us/library/ms590112)

The HostWindow

## See Also

# [PopupWindowAction Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.popupwindowaction(v=pandp.50))

[PopupWindowAction Class](https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.popupwindowaction)

[PopupWindowAction Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.popupwindowaction_members(v=pandp.50))

[Microsoft.Practices.Prism.Interactivity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity(v=pandp.50))
