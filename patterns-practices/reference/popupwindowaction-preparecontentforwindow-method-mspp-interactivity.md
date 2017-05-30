---
TOCTitle: PrepareContentForWindow Method
Title: 'PopupWindowAction.PrepareContentForWindow Method (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Interactivity.PopupWindowAction.PrepareContentForWindow(Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification,System.Windows.Window)'
ms:mtpsurl: 'popupwindowaction-preparecontentforwindow-method-mspp-interactivity.md'
---

# PopupWindowAction.PrepareContentForWindow Method

Checks if the WindowContent or its DataContext implements [IInteractionRequestAware](https://review.docs.microsoft.com/en-us/patterns-practices/reference/iinteractionrequestaware-interface-mspp-interactivity-interactionrequest). If so, it sets the corresponding value. Also, if WindowContent does not have a RegionManager attached, it creates a new scoped RegionManager for it.

**Namespace:** [Microsoft.Practices.Prism.Interactivity](https://review.docs.microsoft.com/patterns-practices/reference/mspp-interactivity-namespace
)

**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll) 

**Version:** 5.0.0.0 (5.0.0.0)

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

Type: [Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification](https://review.docs.microsoft.com/patterns-practices/reference/popupwindowaction-class-mspp-interactivity
)

The notification to be set as a DataContext in the HostWindow.

*wrapperWindow*

Type: [System.Windows.Window](http://msdn2.microsoft.com/en-us/library/ms590112)

The HostWindow

## See Also

[PopupWindowAction Class](https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.popupwindowaction)

[PopupWindowAction Members](https://review.docs.microsoft.com/en-us/patterns-practices/reference/popupwindowaction-members-mspp-interactivity)

[Microsoft.Practices.Prism.Interactivity Namespace](https://review.docs.microsoft.com/en-us/patterns-practices/reference/mspp-interactivity-namespace)
