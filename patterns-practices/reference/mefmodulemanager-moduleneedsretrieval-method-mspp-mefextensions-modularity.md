---
TOCTitle: ModuleNeedsRetrieval Method
Title: 'MefModuleManager.ModuleNeedsRetrieval Method (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager.ModuleNeedsRetrieval(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'mefmodulemanager-moduleneedsretrieval-method-mspp-mefextensions-modularity.md'
---

# MefModuleManager.ModuleNeedsRetrieval Method

Checks if the module needs to be retrieved before it's initialized.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected override bool ModuleNeedsRetrieval(
	ModuleInfo moduleInfo
)
```

```VB
'Declaration
Protected Overrides Function ModuleNeedsRetrieval ( 
	moduleInfo As ModuleInfo
) As Boolean
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
Module that is being checked if needs retrieval.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
True if the module needs to be retrieved. Otherwise, false.

## See Also

[MefModuleManager Class](/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity)  
[MefModuleManager Members](/patterns-practices/reference/mefmodulemanager-members-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  