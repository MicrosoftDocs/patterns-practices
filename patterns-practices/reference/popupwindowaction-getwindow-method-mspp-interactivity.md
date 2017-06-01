---
TOCTitle: GetWindow Method
Title: 'PopupWindowAction.GetWindow Method (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Interactivity.PopupWindowAction.GetWindow(Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification)'
ms:mtpsurl: 'popupwindowaction-getwindow-method-mspp-interactivity.md'
---

# PopupWindowAction.GetWindow Method

Returns the window to display as part of the trigger action.

**Namespace:** [Microsoft.Practices.Prism.Interactivity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll) Version: 5.0.0.0 (5.0.0.0)

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
Type: [Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.inotification(v=pandp.50))

The notification to be set as a DataContext in the window.

### Return Value

Type: [Window](http://msdn.microsoft.com/en-us/library/ms590112)

## See Also

[PopupWindowAction Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.popupwindowaction(v=pandp.50))

[PopupWindowAction Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.popupwindowaction_members(v=pandp.50))

[Microsoft.Practices.Prism.Interactivity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity(v=pandp.50))