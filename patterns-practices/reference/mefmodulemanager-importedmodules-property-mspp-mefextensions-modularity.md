---
TOCTitle: ImportedModules Property
Title: 'MefModuleManager.ImportedModules Property (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager.ImportedModules'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431267(v=PandP.50)'
---

Prism Class Library

MefModuleManager.ImportedModules Property
=============================================

Gets or sets the modules to be imported.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


protected IEnumerable&lt;Lazy&lt;IModule, IModuleExport&gt;&gt; ImportedModules { get; set; }Protected Property ImportedModules As IEnumerable(Of Lazy(Of IModule, IModuleExport)) Get Set
### Property Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([Lazy](http://msdn.microsoft.com/en-us/library/dd986615)&lt;(Of &lt;([IModule](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodule), [IModuleExport](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity.imoduleexport)&gt;)&gt;)&gt;)&gt;)

Remarks
-------

<span id="remarksToggle"></span>Import the available modules from the MEF container

See Also
--------


[MefModuleManager Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity.mefmodulemanager)

[MefModuleManager Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.modularity.mefmodulemanager)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity)
