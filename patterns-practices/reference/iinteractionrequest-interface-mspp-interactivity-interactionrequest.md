---
TOCTitle: IInteractionRequest Interface
Title: 'IInteractionRequest Interface (Microsoft.Practices.Prism.Interactivity.InteractionRequest)'
ms:assetid: 'T:Microsoft.Practices.Prism.Interactivity.InteractionRequest.IInteractionRequest'
ms:mtpsurl: 'iinteractionrequest-interface-mspp-interactivity-interactionrequest.md'
---


# IInteractionRequest Interface

Represents a request from user interaction.

**Namespace:** [Microsoft.Practices.Prism.Interactivity.InteractionRequest](/patterns-practices/reference/mspp-interactivity-interactionrequest-namespace)  
**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public interface IInteractionRequest
```
```VB
'Declaration
Public Interface IInteractionRequest
```

## Remarks

View models can expose interaction request objects through properties and raise them when user interaction is required so views associated with the view models can materialize the user interaction using an appropriate mechanism.

## See Also

[IInteractionRequest Members](/patterns-practices/reference/iinteractionrequest-members-mspp-interactivity-interactionrequest)  
[Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace](/patterns-practices/reference/mspp-interactivity-interactionrequest-namespace)  