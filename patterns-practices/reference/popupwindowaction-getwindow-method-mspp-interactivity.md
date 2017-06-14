---
TOCTitle: GetWindow Method
Title: 'PopupWindowAction.GetWindow Method (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Interactivity.PopupWindowAction.GetWindow(Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification)'
ms:mtpsurl: 'popupwindowaction-getwindow-method-mspp-interactivity.md'
---

# PopupWindowAction.GetWindow Method

Returns the window to display as part of the trigger action.

**Namespace:** [Microsoft.Practices.Prism.Interactivity](/patterns-practices/reference/mspp-interactivity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```c#
protected virtual Window GetWindow(
	INotification notification
)
```
```VB
'Declaration
Protected Overridable Function GetWindow ( 
	notification As INotification
) As Window
```

### Parameters

*notification*  
Type: [Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification](/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest)

The notification to be set as a DataContext in the window.

### Return Value

Type: [Window](http://msdn.microsoft.com/en-us/library/ms590112)

## See Also

[PopupWindowAction Class](/patterns-practices/reference/popupwindowaction-class-mspp-interactivity)  
[PopupWindowAction Members](/patterns-practices/reference/popupwindowaction-members-mspp-interactivity)  
[Microsoft.Practices.Prism.Interactivity Namespace](/patterns-practices/reference/mspp-interactivity-namespace)