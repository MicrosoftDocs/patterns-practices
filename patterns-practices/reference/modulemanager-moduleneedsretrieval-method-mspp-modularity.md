---
TOCTitle: ModuleNeedsRetrieval Method
Title: 'ModuleManager.ModuleNeedsRetrieval Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleManager.ModuleNeedsRetrieval(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'modulemanager-moduleneedsretrieval-method-mspp-modularity.md'
---

# ModuleManager.ModuleNeedsRetrieval Method

Checks if the module needs to be retrieved before it's initialized.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual bool ModuleNeedsRetrieval(
	ModuleInfo moduleInfo
)
```

```VB
'Declaration
Protected Overridable Function ModuleNeedsRetrieval ( 
	moduleInfo As ModuleInfo
) As Boolean
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
Module that is being checked if needs retrieval.

### Return Value
Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

## See Also

[ModuleManager Class](/patterns-practices/reference/modulemanager-class-mspp-modularity)  
[ModuleManager Members](/patterns-practices/reference/modulemanager-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  