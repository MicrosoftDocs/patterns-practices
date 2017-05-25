---
TOCTitle: CanLoadModuleType Method
Title: 'MefFileModuleTypeLoader.CanLoadModuleType Method (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefFileModuleTypeLoader.CanLoadModuleType(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader.canloadmoduletype(v=pandp.50)'
---

Prism Class Library

MefFileModuleTypeLoader.CanLoadModuleType Method
====================================================

Evaluates the [Ref](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo.ref) property to see if the current typeloader will be able to retrieve the moduleInfo. Returns true if the [Ref](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo.ref) property starts with "file://", because this indicates that the file is a local file.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public virtual bool CanLoadModuleType( ModuleInfo moduleInfo )Public Overridable Function CanLoadModuleType ( moduleInfo As ModuleInfo ) As Boolean

### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)
Module that should have it's type loaded.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
trueTruetruetrue (True in Visual Basic) if the current typeloader is able to retrieve the module, otherwise falseFalsefalsefalse (False in Visual Basic).
### Implements

[IModuleTypeLoader.CanLoadModuleType(ModuleInfo)](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader.canloadmoduletype(microsoft.practices.prism.modularity.moduleinfo))

See Also
--------


[MefFileModuleTypeLoader Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader)

[MefFileModuleTypeLoader Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity)
