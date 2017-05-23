---
TOCTitle: SolveDependencies Method
Title: 'ModuleCatalog.SolveDependencies Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.SolveDependencies(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405883(v=PandP.50)'
---

Prism Class Library

ModuleCatalog.SolveDependencies Method
==========================================

Checks for cyclic dependencies, by calling the dependencysolver.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


protected static string[] SolveDependencies( IEnumerable&lt;ModuleInfo&gt; modules )Protected Shared Function SolveDependencies ( modules As IEnumerable(Of ModuleInfo) ) As String()

### Parameters

modules  
Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)&gt;)&gt;)
the.

### Return Value

Type: array&lt;[String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)&gt;

See Also
--------


[ModuleCatalog Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog)

[ModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
