---
TOCTitle: DelegateReference Constructor
Title: 'DelegateReference Constructor (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.DelegateReference.\#ctor(System.Delegate,System.Boolean)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736199(v=PandP.50)'
---

Prism Class Library

DelegateReference Constructor
=============================

Initializes a new instance of [DelegateReference](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.delegatereference).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public DelegateReference( Delegate delegate, bool keepReferenceAlive )Public Sub New ( delegate As Delegate, keepReferenceAlive As Boolean )
#### Parameters

delegate  
Type: [System..::.Delegate](http://msdn2.microsoft.com/en-us/library/y22acf51)
The original [Delegate](http://msdn2.microsoft.com/en-us/library/y22acf51) to create a reference for.

keepReferenceAlive  
Type: [System..::.Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
If falseFalsefalsefalse (False in Visual Basic) the class will create a weak reference to the delegate, allowing it to be garbage collected. Otherwise it will keep a strong reference to the target.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                                                  |
|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| [System..::.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | If the passed delegate is not assignable to [Delegate](http://msdn2.microsoft.com/en-us/library/y22acf51). |

See Also
--------

<span id="seeAlsoToggle"></span>
[DelegateReference Class](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.delegatereference)

[DelegateReference Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.delegatereference)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
