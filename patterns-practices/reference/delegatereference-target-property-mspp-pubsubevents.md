---
TOCTitle: Target Property
Title: 'DelegateReference.Target Property (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'P:Microsoft.Practices.Prism.PubSubEvents.DelegateReference.Target'
ms:mtpsurl: 'delegatereference-target-property-mspp-pubsubevents.md'
---

# DelegateReference.Target Property

Gets the [Delegate](http://msdn.microsoft.com/en-us/library/y22acf51) (the target) referenced by the current [DelegateReference](/patterns-practices/reference/delegatereference-class-mspp-pubsubevents) object.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public Delegate Target { get; }
```

### Property Value

Type: [Delegate](http://msdn.microsoft.com/en-us/library/y22acf51)

**null**a null reference (**Nothing** in Visual Basic) if the object referenced by the current [DelegateReference](/patterns-practices/reference/delegatereference-class-mspp-pubsubevents) object has been garbage collected; otherwise, a reference to the [Delegate](http://msdn2.microsoft.com/en-us/library/y22acf51) referenced by the current [DelegateReference](/patterns-practices/reference/delegatereference-class-mspp-pubsubevents) object.

## Syntax
 
```VB
'Declaration
Public ReadOnly Property Target As Delegate
	Get
``` 

### Property Value

Type: [Delegate](http://msdn.microsoft.com/en-us/library/y22acf51)

**Nothing**a null reference (**Nothing** in Visual Basic) if the object referenced by the current [DelegateReference](/patterns-practices/reference/delegatereference-class-mspp-pubsubevents) object has been garbage collected; otherwise, a reference to the [Delegate](http://msdn2.microsoft.com/en-us/library/y22acf51) referenced by the current [DelegateReference](/patterns-practices/reference/delegatereference-class-mspp-pubsubevents) object.

### Implements

[IDelegateReference.Target](/patterns-practices/reference/idelegatereference-target-property-mspp-pubsubevents)

## See Also

[DelegateReference Class](/patterns-practices/reference/delegatereference-class-mspp-pubsubevents)<br/>
DelegateReference Members
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>