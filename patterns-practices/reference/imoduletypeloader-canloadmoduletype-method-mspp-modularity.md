---
TOCTitle: CanLoadModuleType Method
Title: 'IModuleTypeLoader.CanLoadModuleType Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.IModuleTypeLoader.CanLoadModuleType(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'imoduletypeloader-canloadmoduletype-method-mspp-modularity.md'
---

# IModuleTypeLoader.CanLoadModuleType Method

Evaluates the [Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity) property to see if the current typeloader will be able to retrieve the *moduleInfo*.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
bool CanLoadModuleType(
	ModuleInfo moduleInfo
)
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
Module that should have it's type loaded.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
**truetrue** (**True** in Visual Basic) if the current typeloader is able to retrieve the module, otherwise **falsefalse** (**False** in Visual Basic).

## Syntax

```VB
'Declaration
Function CanLoadModuleType ( 
	moduleInfo As ModuleInfo
) As Boolean
)
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
Module that should have it's type loaded.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
**Truetrue** (**True** in Visual Basic) if the current typeloader is able to retrieve the module, otherwise **Falsefalse** (**False** in Visual Basic).

## See Also

[IModuleTypeLoader Interface](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)<br/>
[IModuleTypeLoader Members](/patterns-practices/reference/imoduletypeloader-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>