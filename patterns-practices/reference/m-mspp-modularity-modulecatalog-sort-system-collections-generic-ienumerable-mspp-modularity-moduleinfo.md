---
TOCTitle: Sort Method
Title: 'ModuleCatalog.Sort Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.Sort(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405884(v=PandP.50)'
---

Prism Class Library

ModuleCatalog..::.Sort Method
=============================

Sorts a list of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s. This method is called by [CompleteListWithDependencies(IEnumerable&lt;(Of &lt;(ModuleInfo&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.completelistwithdependencies(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d)) to return a sorted list.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected virtual IEnumerable&lt;ModuleInfo&gt; Sort( IEnumerable&lt;ModuleInfo&gt; modules )Protected Overridable Function Sort ( modules As IEnumerable(Of ModuleInfo) ) As IEnumerable(Of ModuleInfo)
#### Parameters

modules  
Type: [System.Collections.Generic..::.IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)&gt;)&gt;)
The [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s to sort.

#### Return Value

Type: [IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)&gt;)&gt;)
Sorted list of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleCatalog Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog)

[ModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
