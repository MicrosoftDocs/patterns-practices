---
TOCTitle: RemoveAt Method
Title: 'ModuleInfoGroup.RemoveAt Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.RemoveAt(System.Int32)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405914(v=PandP.50)'
---

Prism Class Library

ModuleInfoGroup..::.RemoveAt Method
===================================

Removes the [IList&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/5y536ey6) item at the specified index.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public void RemoveAt( int index )Public Sub RemoveAt ( index As Integer )
#### Parameters

index  
Type: [System..::.Int32](http://msdn2.microsoft.com/en-us/library/td2s409d)
The zero-based index of the item to remove.

#### Implements

[IList&lt;(Of &lt;(T&gt;)&gt;)..::.RemoveAt(Int32)](http://msdn2.microsoft.com/en-us/library/c93ab5c9)
[IList..::.RemoveAt(Int32)](http://msdn2.microsoft.com/en-us/library/x5zwtyhy)

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                                   | Condition                                                                                                             |
|---------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [System..::.ArgumentOutOfRangeException](http://msdn2.microsoft.com/en-us/library/8xt94y6e) | index is not a valid index in the [IList&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/5y536ey6). |
| [System..::.NotSupportedException](http://msdn2.microsoft.com/en-us/library/8a7a4e64)       | The [IList&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/5y536ey6) is read-only.                  |

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleInfoGroup Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup)

[ModuleInfoGroup Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinfogroup)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
