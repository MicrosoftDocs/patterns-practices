---
TOCTitle: ThreadOption Enumeration
Title: 'ThreadOption Enumeration (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'T:Microsoft.Practices.Prism.PubSubEvents.ThreadOption'
ms:mtpsurl: 'threadoption-enumeration-mspp-pubsubevents.md'
---


# ThreadOption Enumeration

Specifies on which thread a [PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents) subscriber will be called.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public enum ThreadOption
```

## Members


|     | Member name      | Value | Description                                                                                                                                                                                       |
|-----|------------------|-------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     | PublisherThread  | 0     | The call is done on the same thread on which the [PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent) was published. |
|     | UIThread         | 1     | The call is done on the UI thread.                                                                                                                                                                |
|     | BackgroundThread | 2     | The call is done asynchronously on a background thread.                                                                                                                                           |

## See Also

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)  


# ThreadOption Enumeration

Specifies on which thread a [PubSubEvent(Of TPayload)](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents) subscriber will be called.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Enumeration ThreadOption
```

## Members


|     | Member name      | Value | Description                                                                                                                                                                                       |
|-----|------------------|-------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     | PublisherThread  | 0     | The call is done on the same thread on which the [PubSubEvent(Of TPayload)](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent) was published. |
|     | UIThread         | 1     | The call is done on the UI thread.                                                                                                                                                                |
|     | BackgroundThread | 2     | The call is done asynchronously on a background thread.                                                                                                                                           |

## See Also

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)