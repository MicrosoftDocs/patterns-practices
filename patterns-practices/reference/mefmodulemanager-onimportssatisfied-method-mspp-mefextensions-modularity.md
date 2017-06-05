---
TOCTitle: OnImportsSatisfied Method
Title: 'MefModuleManager.OnImportsSatisfied Method (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager.OnImportsSatisfied'
ms:mtpsurl: 'mefmodulemanager-onimportssatisfied-method-mspp-mefextensions-modularity.md'
---

# MefModuleManager.OnImportsSatisfied Method

Called when a part's imports have been satisfied and it is safe to use.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public virtual void OnImportsSatisfied()
```
```VB
'Declaration
Public Overridable Sub OnImportsSatisfied
```

### Implements

[IPartImportsSatisfiedNotification.OnImportsSatisfied()](http://msdn.microsoft.com/en-us/library/dd833579)

## Remarks

 Whenever the MEF container loads new types that cause ImportedModules to be recomposed, this is called. This method ensures that as the MEF container discovered new modules, the ModuleCatalog is updated.

## See Also

[MefModuleManager Class](/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity)  
[MefModuleManager Members](/patterns-practices/reference/mefmodulemanager-members-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)
