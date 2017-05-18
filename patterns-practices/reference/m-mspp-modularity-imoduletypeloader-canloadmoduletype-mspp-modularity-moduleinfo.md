---
TOCTitle: CanLoadModuleType Method
Title: 'IModuleTypeLoader.CanLoadModuleType Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.IModuleTypeLoader.CanLoadModuleType(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405863(v=PandP.50)'
---

Prism Class Library

IModuleTypeLoader..::.CanLoadModuleType Method
==============================================

Evaluates the [Ref](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.ref) property to see if the current typeloader will be able to retrieve the moduleInfo.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>bool CanLoadModuleType( ModuleInfo moduleInfo )Function CanLoadModuleType ( moduleInfo As ModuleInfo ) As Boolean
#### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity..::.ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)
Module that should have it's type loaded.

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
trueTruetruetrue (True in Visual Basic) if the current typeloader is able to retrieve the module, otherwise falseFalsefalsefalse (False in Visual Basic).

See Also
--------

<span id="seeAlsoToggle"></span>
[IModuleTypeLoader Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imoduletypeloader)

[IModuleTypeLoader Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.imoduletypeloader)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
