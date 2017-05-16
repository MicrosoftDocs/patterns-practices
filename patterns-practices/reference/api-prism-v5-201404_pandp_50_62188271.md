---
TOCTitle: Deactivate Method
Title: 'AllActiveRegion.Deactivate Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.AllActiveRegion.Deactivate(System.Object)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405932(v=PandP.50)'
---

Prism Class Library

AllActiveRegion..::.Deactivate Method
=====================================

Deactive is not valid in this Region. This method will always throw [InvalidOperationException](http://msdn2.microsoft.com/en-us/library/2asft85a).

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public override void Deactivate( Object view )Public Overrides Sub Deactivate ( view As Object )
#### Parameters

view  
Type: [System..::.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
The view to deactivate.

#### Implements

[IRegion..::.Deactivate(Object)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.deactivate(system.object))

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                                 | Condition                         |
|-------------------------------------------------------------------------------------------|-----------------------------------|
| [System..::.InvalidOperationException](http://msdn2.microsoft.com/en-us/library/2asft85a) | Every time this method is called. |

See Also
--------

<span id="seeAlsoToggle"></span>
[AllActiveRegion Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.allactiveregion)

[AllActiveRegion Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.allactiveregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
