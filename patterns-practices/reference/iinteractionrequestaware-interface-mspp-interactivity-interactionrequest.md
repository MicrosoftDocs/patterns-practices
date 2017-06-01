---
TOCTitle: IInteractionRequestAware Interface
Title: 'IInteractionRequestAware Interface (Microsoft.Practices.Prism.Interactivity.InteractionRequest)'
ms:assetid: 'T:Microsoft.Practices.Prism.Interactivity.InteractionRequest.IInteractionRequestAware'
ms:mtpsurl: 'iinteractionrequestaware-interface-mspp-interactivity-interactionrequest.md'
---
# IInteractionRequestAware Interface

Interface used by the [PopupWindowAction](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.popupwindowaction(v=pandp.50)). If the DataContext object of a view that is shown with this action implements this interface it will be populated with the [INotification](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.inotification(v=pandp.50)) data of the interaction request as well as an [Action](http://msdn2.microsoft.com/en-us/library/bb534741) to finish the request upon invocation. 

**Namespace:** [Microsoft.Practices.Prism.Interactivity.InteractionRequest](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest(v=pandp.50))

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
[IInteractionRequestAware Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequestaware_members(v=pandp.50))

[Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.interactivity.interactionrequest(v=pandp.50))

