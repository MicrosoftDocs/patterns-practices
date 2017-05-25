---
TOCTitle: AddGroup Method
Title: 'ModuleCatalog.AddGroup Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.AddGroup(Microsoft.Practices.Prism.Modularity.InitializationMode,System.String,Microsoft.Practices.Prism.Modularity.ModuleInfo[])'
ms:mtpsurl: 'modulecatalog-addgroup-method-mspp-modularity.md'
---

Prism Class Library

ModuleCatalog.AddGroup Method
=================================

Creates and adds a [ModuleInfoGroup](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup) to the catalog.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public virtual ModuleCatalog AddGroup( InitializationMode initializationMode, string refValue, params ModuleInfo[] moduleInfos )Public Overridable Function AddGroup ( initializationMode As InitializationMode, refValue As String, ParamArray moduleInfos As ModuleInfo() ) As ModuleCatalog

### Parameters

initializationMode  
Type: [Microsoft.Practices.Prism.Modularity.InitializationMode](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.initializationmode)
Stage on which the module group to be added will be initialized.

refValue  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
Reference to the location of the module group to be added.

moduleInfos  
Type: array&lt;[Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)&gt;
Collection of [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) included in the group.

### Return Value

Type: [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)
[ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog) with the added module group.

See Also
--------


[ModuleCatalog Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)

[ModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
