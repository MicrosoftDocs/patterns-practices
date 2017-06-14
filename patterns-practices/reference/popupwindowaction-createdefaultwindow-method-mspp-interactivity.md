---
TOCTitle: CreateDefaultWindow Method
Title: 'PopupWindowAction.CreateDefaultWindow Method (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Interactivity.PopupWindowAction.CreateDefaultWindow(Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification)'
ms:mtpsurl: 'popupwindowaction-createdefaultwindow-method-mspp-interactivity.md'
---


# PopupWindowAction.CreateDefaultWindow Method

When no WindowContent is sent this method is used to create a default basic window to show the corresponding [INotification](/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest) or [IConfirmation](/patterns-practices/reference/iconfirmation-interface-mspp-interactivity-interactionrequest).

**Namespace:** [Microsoft.Practices.Prism.Interactivity](/patterns-practices/reference/mspp-interactivity-namespace)  
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


### Parameters

*notification*
  
Type: [Microsoft.Practices.Prism.Interactivity.InteractionRequest.INotification](/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest)

The INotification or IConfirmation parameter to show.

### Return Value

Type: [Window](http://msdn.microsoft.com/en-us/library/ms590112)

## See Also

[PopupWindowAction Class](/patterns-practices/reference/popupwindowaction-class-mspp-interactivity)  
[PopupWindowAction Members](/patterns-practices/reference/popupwindowaction-members-mspp-interactivity)  
[Microsoft.Practices.Prism.Interactivity Namespace](/patterns-practices/reference/mspp-interactivity-namespace)