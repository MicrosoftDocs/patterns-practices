---
TOCTitle: GetEventName Method
Title: 'InteractionRequestTrigger.GetEventName Method (Microsoft.Practices.Prism.Interactivity.InteractionRequest)'
ms:assetid: 'M:Microsoft.Practices.Prism.Interactivity.InteractionRequest.InteractionRequestTrigger.GetEventName'
ms:mtpsurl: 'interactionrequesttrigger-geteventname-method-mspp-interactivity-interactionrequest.md'
---

# InteractionRequestTrigger.GetEventName Method

Specifies the name of the Event this EventTriggerBase is listening for.

**Namespace:** [Microsoft.Practices.Prism.Interactivity.InteractionRequest](/patterns-practices/reference/mspp-interactivity-interactionrequest-namespace)  
**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected override string GetEventName()
```

```VB
'Declaration
Protected Overrides Function GetEventName As String
```
### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
This implementation always returns the Raised event name for ease of connection with [IInteractionRequest](/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest).

## See Also

[InteractionRequestTrigger Class](/patterns-practices/reference/interactionrequesttrigger-class-mspp-interactivity-interactionrequest)  
[InteractionRequestTrigger Members](/patterns-practices/reference/interactionrequesttrigger-members-mspp-interactivity-interactionrequest)  
[Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace](/patterns-practices/reference/mspp-interactivity-interactionrequest-namespace)  