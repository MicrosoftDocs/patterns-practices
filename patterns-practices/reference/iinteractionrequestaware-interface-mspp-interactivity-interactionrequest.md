---
TOCTitle: IInteractionRequestAware Interface
Title: 'IInteractionRequestAware Interface (Microsoft.Practices.Prism.Interactivity.InteractionRequest)'
ms:assetid: 'T:Microsoft.Practices.Prism.Interactivity.InteractionRequest.IInteractionRequestAware'
ms:mtpsurl: 'iinteractionrequestaware-interface-mspp-interactivity-interactionrequest.md'
---
# IInteractionRequestAware Interface

Interface used by the [PopupWindowAction](/patterns-practices/reference/popupwindowaction-class-mspp-interactivity). If the DataContext object of a view that is shown with this action implements this interface it will be populated with the [INotification](/patterns-practices/reference/inotification-interface-mspp-interactivity-interactionrequest) data of the interaction request as well as an [Action](http://msdn.microsoft.com/en-us/library/bb534741) to finish the request upon invocation. 

**Namespace:** [Microsoft.Practices.Prism.Interactivity.InteractionRequest](/patterns-practices/reference/mspp-interactivity-interactionrequest-namespace)

**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public interface IInteractionRequestAware
```

```VB
'Declaration
Public Interface IInteractionRequestAware
```

## See Also
[IInteractionRequestAware Members](/patterns-practices/reference/iinteractionrequestaware-members-mspp-interactivity-interactionrequest)

[Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace](/patterns-practices/reference/mspp-interactivity-interactionrequest-namespace)

