---
TOCTitle: InvokeAction Method
Title: 'BackgroundEventSubscription(TPayload).InvokeAction Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription\`1.InvokeAction(System.Action{\`0},\`0)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736193(v=PandP.50)'
---

Prism Class Library

# BackgroundEventSubscription<(Of <(TPayload>)>).InvokeAction Method


Invokes the specified [Action<(Of <(T>)>)](http://msdn.microsoft.com/en-us/library/018hxwa8) in an asynchronous thread by using a [ThreadPool](http://msdn.microsoft.com/en-us/library/y5htx827).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


public override void InvokeAction( Action<TPayload> action, TPayload argument )Public Overrides Sub InvokeAction ( action As Action(Of TPayload), argument As TPayload )

### Parameters

action  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)<(Of <([TPayload](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.backgroundeventsubscription%601)>)>)
The action to execute.

argument  
Type: [TPayload](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.backgroundeventsubscription%601)
The payload to pass action while invoking it.

## See Also



[BackgroundEventSubscription<(Of <(TPayload>)>) Class](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.backgroundeventsubscription%601)

[BackgroundEventSubscription<(Of <(TPayload>)>) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.backgroundeventsubscription%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
