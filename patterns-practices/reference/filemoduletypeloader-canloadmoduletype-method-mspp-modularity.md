---
TOCTitle: CanLoadModuleType Method
Title: 'FileModuleTypeLoader.CanLoadModuleType Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.FileModuleTypeLoader.CanLoadModuleType(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405850(v=PandP.50)'
---


# FileModuleTypeLoader.CanLoadModuleType Method

Evaluates the [Ref](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo.ref) property to see if the current typeloader will be able to retrieve the moduleInfo. Returns true if the [Ref](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo.ref) property starts with "file://", because this indicates that the file is a local file.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public bool CanLoadModuleType( ModuleInfo moduleInfo )Public Function CanLoadModuleType ( moduleInfo As ModuleInfo ) As Boolean

### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)
Module that should have it's type loaded.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
trueTruetruetrue (True in Visual Basic) if the current typeloader is able to retrieve the module, otherwise falseFalsefalsefalse (False in Visual Basic).
### Implements

[IModuleTypeLoader.CanLoadModuleType(ModuleInfo)](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader.canloadmoduletype(microsoft.practices.prism.modularity.moduleinfo))

## Exceptions

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                                                      |
|---------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) is thrown if moduleInfo is null. |

## See Also

[FileModuleTypeLoader Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.filemoduletypeloader)

[FileModuleTypeLoader Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.filemoduletypeloader)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
