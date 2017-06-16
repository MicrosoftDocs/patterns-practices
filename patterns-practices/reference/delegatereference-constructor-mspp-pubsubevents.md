---
TOCTitle: DelegateReference Constructor
Title: 'DelegateReference Constructor (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.DelegateReference.\#ctor(System.Delegate,System.Boolean)'
ms:mtpsurl: 'delegatereference-constructor-mspp-pubsubevents.md'
---

# DelegateReference Constructor

Initializes a new instance of [DelegateReference](/patterns-practices/reference/mspp-mvvm-namespace.delegatereference).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public DelegateReference(
	Delegate delegate,
	bool keepReferenceAlive
)
```

```VB
'Declaration
Public Sub New ( 
	delegate As Delegate,
	keepReferenceAlive As Boolean
)
```

### Parameters

*delegate*  

Type: [System.Delegate](http://msdn.microsoft.com/en-us/library/y22acf51)

The original [Delegate](http://msdn.microsoft.com/en-us/library/y22acf51) to create a reference for.

*keepReferenceAlive*  

Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

If **falsefalse** (**False** in Visual Basic) the class will create a weak reference to the delegate, allowing it to be garbage collected. Otherwise it will keep a strong reference to the target.

## Exceptions


| Exception                                                                             | Condition                                                                                                  |
|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | If the passed delegate is not assignable to [Delegate](http://msdn.microsoft.com/en-us/library/y22acf51). |

## See Also

[DelegateReference Class](/patterns-practices/reference/delegatereference-class-mspp-pubsubevents)  
DelegateReference Members  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)  