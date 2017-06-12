---
TOCTitle: CanLoadModuleType Method
Title: 'MefFileModuleTypeLoader.CanLoadModuleType Method (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefFileModuleTypeLoader.CanLoadModuleType(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'meffilemoduletypeloader-canloadmoduletype-method-mspp-mefextensions-modularity.md'
---

# MefFileModuleTypeLoader.CanLoadModuleType Method

Evaluates the [Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity) property to see if the current typeloader will be able to retrieve the moduleInfo. Returns true if the [Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity) property starts with "file://", because this indicates that the file is a local file.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public virtual bool CanLoadModuleType(
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


```VB
'Declaration
Public Overridable Function CanLoadModuleType ( 
	moduleInfo As ModuleInfo
) As Boolean
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
Module that should have it's type loaded.

### Return Value
Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
**Truetrue** (**True** in Visual Basic) if the current typeloader is able to retrieve the module, otherwise **Falsefalse** (**False** in Visual Basic).

### Implements

[IModuleTypeLoader.CanLoadModuleType(ModuleInfo)](/patterns-practices/reference/imoduletypeloader-canloadmoduletype-method-mspp-modularity)

## See Also

[MefFileModuleTypeLoader Class](/patterns-practices/reference/meffilemoduletypeloader-class-mspp-mefextensions-modularity)  
[MefFileModuleTypeLoader Members](/patterns-practices/reference/meffilemoduletypeloader-members-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)<br/>