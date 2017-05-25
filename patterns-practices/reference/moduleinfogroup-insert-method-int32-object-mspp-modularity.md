---
TOCTitle: 'Insert Method (Int32, Object)'
Title: 'ModuleInfoGroup.Insert Method (Int32, Object) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.Insert(System.Int32,System.Object)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405912(v=PandP.50)'
---

Prism Class Library

ModuleInfoGroup.Insert Method (Int32, Object)
=================================================

Inserts an item to the [ModuleInfoGroup](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup) at the specified index.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public void Insert( int index, Object value )Public Sub Insert ( index As Integer, value As Object )

### Parameters

index  
Type: [System.Int32](http://msdn.microsoft.com/en-us/library/td2s409d)
The zero-based index at which value should be inserted.

value  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
The [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) to insert into the [ModuleInfoGroup](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup). Must be of type [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)

### Implements

[IList.Insert(Int32, Object)](http://msdn.microsoft.com/en-us/library/zkf4388a)

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                                   | Condition                                                                                                                               |
|---------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentOutOfRangeException](http://msdn.microsoft.com/en-us/library/8xt94y6e) | index is not a valid index in the [ModuleInfoGroup](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup). |
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)       | If value is null.                                                                                                                       |
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)           | If value is not of type [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)                      |

See Also
--------


[ModuleInfoGroup Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup)

[ModuleInfoGroup Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinfogroup)

[Insert Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.modularity.moduleinfogroup.insert)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
