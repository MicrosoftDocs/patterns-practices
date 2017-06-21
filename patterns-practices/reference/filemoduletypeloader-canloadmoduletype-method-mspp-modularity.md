---
TOCTitle: CanLoadModuleType Method
Title: 'FileModuleTypeLoader.CanLoadModuleType Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.FileModuleTypeLoader.CanLoadModuleType(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'filemoduletypeloader-canloadmoduletype-method-mspp-modularity.md'
---

# FileModuleTypeLoader.CanLoadModuleType Method

Evaluates the [Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity) property to see if the current typeloader will be able to retrieve the *moduleInfo*. Returns true if the [Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity) property starts with "file://", because this indicates that the file is a local file.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)   
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public bool CanLoadModuleType(
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
Public Function CanLoadModuleType ( 
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

## Exceptions

| Exception | Condition |
|---|---|
|[System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) is thrown if *moduleInfo* is null.|

## See Also

[FileModuleTypeLoader Class](/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity)  
[FileModuleTypeLoader Members](/patterns-practices/reference/filemoduletypeloader-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  

