---
TOCTitle: 'Equals Method (Object)'
Title: 'SubscriptionToken.Equals Method (Object) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken.Equals(System.Object)'
ms:mtpsurl: 'subscriptiontoken-equals-method-mspp-pubsubevents.md'
---


# SubscriptionToken.Equals Method (Object)

Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
   public override bool Equals(
	Object obj
)
```

```VB
   'Declaration
Public Overrides Function Equals ( 
	obj As Object
) As Boolean
```

### Parameters

*obj*  

Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

The [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) to compare with the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

true if the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b); otherwise, false.

## Exceptions


| Exception                                                                              | Condition                  |
|----------------------------------------------------------------------------------------|----------------------------|
| [System.NullReferenceException](http://msdn.microsoft.com/en-us/library/8w0s4024) | The obj parameter is null. |

## See Also

[SubscriptionToken Class](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)<br/>
SubscriptionToken Members

[Equals Overload](/patterns-practices/reference/subscriptiontoken-equals-method-mspp-pubsubevents)<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)