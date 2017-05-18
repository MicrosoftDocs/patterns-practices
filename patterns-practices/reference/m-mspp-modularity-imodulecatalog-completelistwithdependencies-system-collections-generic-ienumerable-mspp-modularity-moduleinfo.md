---
TOCTitle: CompleteListWithDependencies Method
Title: 'IModuleCatalog.CompleteListWithDependencies Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.IModuleCatalog.CompleteListWithDependencies(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405857(v=PandP.50)'
---

Prism Class Library

IModuleCatalog..::.CompleteListWithDependencies Method
======================================================

Returns the collection of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s that contain both the [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s in modules, but also all the modules they depend on.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>IEnumerable&lt;ModuleInfo&gt; CompleteListWithDependencies( IEnumerable&lt;ModuleInfo&gt; modules )Function CompleteListWithDependencies ( modules As IEnumerable(Of ModuleInfo) ) As IEnumerable(Of ModuleInfo)
#### Parameters

modules  
Type: [System.Collections.Generic..::.IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)&gt;)&gt;)
The modules to get the dependencies for.

#### Return Value

Type: [IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)&gt;)&gt;)
A collection of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) that contains both all [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s in modules and also all the [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) they depend on.

See Also
--------

<span id="seeAlsoToggle"></span>
[IModuleCatalog Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog)

[IModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.imodulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
