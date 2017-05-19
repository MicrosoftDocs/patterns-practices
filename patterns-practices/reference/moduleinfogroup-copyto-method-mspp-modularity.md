---
TOCTitle: CopyTo Method
Title: 'ModuleInfoGroup.CopyTo Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.CopyTo(Microsoft.Practices.Prism.Modularity.ModuleInfo[],System.Int32)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405907(v=PandP.50)'
---

Prism Class Library

ModuleInfoGroup.CopyTo Method
=================================

Copies the elements of the [ModuleInfoGroup](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup) to an [Array](http://msdn2.microsoft.com/en-us/library/czz5hkty), starting at a particular [Array](http://msdn2.microsoft.com/en-us/library/czz5hkty) index.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public void CopyTo( ModuleInfo[] array, int arrayIndex )Public Sub CopyTo ( array As ModuleInfo(), arrayIndex As Integer )
#### Parameters

array  
Type: array&lt;[Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)&gt;
The one-dimensional [Array](http://msdn2.microsoft.com/en-us/library/czz5hkty) that is the destination of the elements copied from [ModuleInfoGroup](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup). The [Array](http://msdn2.microsoft.com/en-us/library/czz5hkty) must have zero-based indexing.

arrayIndex  
Type: [System.Int32](http://msdn2.microsoft.com/en-us/library/td2s409d)
The zero-based index in array at which copying begins.

#### Implements

[ICollection&lt;(Of &lt;(T&gt;)&gt;).CopyTo(array&lt;T&gt;, Int32)](http://msdn2.microsoft.com/en-us/library/0efx51xw)

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                                   | Condition                                                                                                                                                                                                                                                                                                                           |
|---------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy)       | array is null.                                                                                                                                                                                                                                                                                                                      |
| [System.ArgumentOutOfRangeException](http://msdn2.microsoft.com/en-us/library/8xt94y6e) | arrayIndex is less than 0.                                                                                                                                                                                                                                                                                                          |
| [System.ArgumentException](http://msdn2.microsoft.com/en-us/library/3w1b3114)           | array is multidimensional. -or- arrayIndex is equal to or greater than the length of array. -or- The number of elements in the source [ModuleInfoGroup](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup) is greater than the available space from arrayIndex to the end of the destination array. |

See Also
--------


[ModuleInfoGroup Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup)

[ModuleInfoGroup Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinfogroup)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
