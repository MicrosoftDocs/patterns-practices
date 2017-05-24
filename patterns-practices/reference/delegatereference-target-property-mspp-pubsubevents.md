---
TOCTitle: Target Property
Title: 'DelegateReference.Target Property (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'P:Microsoft.Practices.Prism.PubSubEvents.DelegateReference.Target'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736223(v=PandP.50)'
---


DelegateReference.Target Property
=====================================

Gets the [Delegate](http://msdn.microsoft.com/en-us/library/y22acf51) (the target) referenced by the current [DelegateReference](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.delegatereference(v=pandp.50)) object.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public Delegate Target { get; }
```
 
```VB
'Declaration
Public ReadOnly Property Target As Delegate
	Get
``` 

### Property Value

Type: [Delegate](http://msdn.microsoft.com/en-us/library/y22acf51)
nullNothingnullptra null reference (Nothing in Visual Basic) if the object referenced by the current [DelegateReference](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.delegatereference(v=pandp.50)) object has been garbage collected; otherwise, a reference to the [Delegate](http://msdn.microsoft.com/en-us/library/y22acf51) referenced by the current [DelegateReference](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.delegatereference(v=pandp.50)) object.
### Implements

[IDelegateReference.Target](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.idelegatereference.target(v=pandp.50))

## See Also

[DelegateReference Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.delegatereference(v=pandp.50))

DelegateReference Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))
