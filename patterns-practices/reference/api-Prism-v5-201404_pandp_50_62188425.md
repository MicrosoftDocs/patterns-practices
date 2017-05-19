---
TOCTitle: CanLoadModuleType Method
Title: 'IModuleTypeLoader.CanLoadModuleType Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.IModuleTypeLoader.CanLoadModuleType(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405863(v=PandP.50)'
---

# IModuleTypeLoader.CanLoadModuleType Method

Evaluates the [Ref](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo.ref(v=pandp.50)) property to see if the current typeloader will be able to retrieve the *moduleInfo*.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax
```C#
bool CanLoadModuleType(
	ModuleInfo moduleInfo
)
```

#### Parameters

*moduleInfo*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Module that should have it's type loaded.

#### Return Value

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**truetrue** (**True** in Visual Basic) if the current typeloader is able to retrieve the module, otherwise **falsefalse** (**False** in Visual Basic).

## Syntax
```VB
'Declaration
Function CanLoadModuleType ( 
	moduleInfo As ModuleInfo
) As Boolean
)
```

#### Parameters

*moduleInfo*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Module that should have it's type loaded.

#### Return Value

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Truetrue** (**True** in Visual Basic) if the current typeloader is able to retrieve the module, otherwise **Falsefalse** (**False** in Visual Basic).

## See Also

[IModuleTypeLoader Interface](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduletypeloader(v=pandp.50))

[IModuleTypeLoader Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduletypeloader_members(v=pandp.50))

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))
