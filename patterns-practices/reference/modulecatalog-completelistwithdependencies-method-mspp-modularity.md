---
TOCTitle: CompleteListWithDependencies Method
Title: 'ModuleCatalog.CompleteListWithDependencies Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.CompleteListWithDependencies(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405874(v=PandP.50)'
---

Prism Class Library

ModuleCatalog.CompleteListWithDependencies Method
=====================================================

Returns a list of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s that contain both the [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s in modules, but also all the modules they depend on.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public virtual IEnumerable&lt;ModuleInfo&gt; CompleteListWithDependencies( IEnumerable&lt;ModuleInfo&gt; modules )Public Overridable Function CompleteListWithDependencies ( modules As IEnumerable(Of ModuleInfo) ) As IEnumerable(Of ModuleInfo)
#### Parameters

modules  
Type: [System.Collections.Generic.IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)&gt;)&gt;)
The modules to get the dependencies for.

#### Return Value

Type: [IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)&gt;)&gt;)
A list of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) that contains both all [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s in modules but also all the [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) they depend on.
#### Implements

[IModuleCatalog.CompleteListWithDependencies(IEnumerable&lt;(Of &lt;(ModuleInfo&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulecatalog.completelistwithdependencies(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d))

See Also
--------


[ModuleCatalog Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog)

[ModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
