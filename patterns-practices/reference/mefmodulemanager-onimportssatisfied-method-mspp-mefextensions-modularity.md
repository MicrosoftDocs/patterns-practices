---
TOCTitle: OnImportsSatisfied Method
Title: 'MefModuleManager.OnImportsSatisfied Method (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager.OnImportsSatisfied'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405842(v=PandP.50)'
---

Prism Class Library

MefModuleManager.OnImportsSatisfied Method
==============================================

Called when a part's imports have been satisfied and it is safe to use.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public virtual void OnImportsSatisfied()Public Overridable Sub OnImportsSatisfied
### Implements

[IPartImportsSatisfiedNotification.OnImportsSatisfied()()()](http://msdn.microsoft.com/en-us/library/dd833579)

Remarks
-------

<span id="remarksToggle"></span> Whenever the MEF container loads new types that cause ImportedModules to be recomposed, this is called. This method ensures that as the MEF container discovered new modules, the ModuleCatalog is updated.

See Also
--------


[MefModuleManager Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity.mefmodulemanager)

[MefModuleManager Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.modularity.mefmodulemanager)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity)
