---
TOCTitle: ModuleInfoGroup Class
Title: 'ModuleInfoGroup Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431499(v=PandP.50)'
---

Prism Class Library

ModuleInfoGroup Class
=====================

Represents a group of [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) instances that are usually deployed together. ModuleInfoGroups are also used by the [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog) to prevent common deployment problems such as having a module that's required at startup that depends on modules that will only be downloaded on demand. The group also forwards [Ref](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup.ref) and [InitializationMode](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup.initializationmode) values to the [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)s that it contains.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public class ModuleInfoGroup : IModuleCatalogItem, IList&lt;ModuleInfo&gt;, ICollection&lt;ModuleInfo&gt;, IEnumerable&lt;ModuleInfo&gt;, IList, ICollection, IEnumerablePublic Class ModuleInfoGroup Implements IModuleCatalogItem, IList(Of ModuleInfo), ICollection(Of ModuleInfo), IEnumerable(Of ModuleInfo), IList, ICollection, IEnumerable

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  Microsoft.Practices.Prism.Modularity.ModuleInfoGroup

See Also
--------


[ModuleInfoGroup Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinfogroup)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
