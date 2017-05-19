---
TOCTitle: 'Insert Method (Int32, ModuleInfo)'
Title: 'ModuleInfoGroup.Insert Method (Int32, ModuleInfo) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.Insert(System.Int32,Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405913(v=PandP.50)'
---

Prism Class Library

ModuleInfoGroup..::.Insert Method (Int32, ModuleInfo)
=====================================================

Inserts an item to the [IList&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/5y536ey6) at the specified index.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public void Insert( int index, ModuleInfo item )Public Sub Insert ( index As Integer, item As ModuleInfo )
#### Parameters

index  
Type: [System..::.Int32](http://msdn2.microsoft.com/en-us/library/td2s409d)
The zero-based index at which item should be inserted.

item  
Type: [Microsoft.Practices.Prism.Modularity..::.ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)
The object to insert into the [IList&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/5y536ey6).

#### Implements

[IList&lt;(Of &lt;(T&gt;)&gt;)..::.Insert(Int32, T)](http://msdn2.microsoft.com/en-us/library/8zsfbxz8)

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                                   | Condition                                                                                                             |
|---------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [System..::.ArgumentOutOfRangeException](http://msdn2.microsoft.com/en-us/library/8xt94y6e) | index is not a valid index in the [IList&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/5y536ey6). |

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleInfoGroup Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup)

[ModuleInfoGroup Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinfogroup)

[Insert Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.modularity.moduleinfogroup.insert)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
