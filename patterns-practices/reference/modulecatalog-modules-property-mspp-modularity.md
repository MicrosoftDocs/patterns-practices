---
TOCTitle: Modules Property
Title: 'ModuleCatalog.Modules Property (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.Modularity.ModuleCatalog.Modules'
ms:mtpsurl: 'modulecatalog-modules-property-mspp-modularity.md'
---

# ModuleCatalog.Modules Property

Gets all the [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) classes that are in the [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog), regardless if they are within a [ModuleInfoGroup](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup) or not.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
public virtual IEnumerable&lt;ModuleInfo&gt; Modules { get; }Public Overridable ReadOnly Property Modules As IEnumerable(Of ModuleInfo) Get
### Property Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)&gt;)&gt;)
The modules.
### Implements

[IModuleCatalog.Modules](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog.modules)

## See Also
[ModuleCatalog Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)

[ModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
