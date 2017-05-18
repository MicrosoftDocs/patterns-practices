---
TOCTitle: ForwardValues Method
Title: 'ModuleInfoGroup.ForwardValues Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.ForwardValues(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405908(v=PandP.50)'
---

Prism Class Library

ModuleInfoGroup..::.ForwardValues Method
========================================

Forwards [InitializationMode](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.initializationmode) and [Ref](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.ref) properties from this [ModuleInfoGroup](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup) to moduleInfo.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected void ForwardValues( ModuleInfo moduleInfo )Protected Sub ForwardValues ( moduleInfo As ModuleInfo )
#### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity..::.ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)
The module info to forward values to.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                                                                                                              |
|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System..::.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) is thrown if moduleInfo is nullNothingnullptra null reference (Nothing in Visual Basic). |

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleInfoGroup Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup)

[ModuleInfoGroup Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinfogroup)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
