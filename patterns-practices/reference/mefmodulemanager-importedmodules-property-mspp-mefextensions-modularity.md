---
TOCTitle: ImportedModules Property
Title: 'MefModuleManager.ImportedModules Property (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager.ImportedModules'
ms:mtpsurl: 'mefmodulemanager-importedmodules-property-mspp-mefextensions-modularity.md'
---

# MefModuleManager.ImportedModules Property

Gets or sets the modules to be imported.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected IEnumerable<Lazy<IModule, IModuleExport>> ImportedModules { get; set; }
```

### Property Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[Lazy](http://msdn.microsoft.com/en-us/library/dd986615)&lt;[IModule](/patterns-practices/reference/imodule-interface-mspp-modularity), [IModuleExport](/patterns-practices/reference/imoduleexport-interface-mspp-mefextensions-modularity)&gt;&gt;

```VB
'Declaration
Protected Property ImportedModules As IEnumerable(Of Lazy(Of IModule, IModuleExport))
	Get
	Set
```

### Property Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [Lazy](http://msdn.microsoft.com/en-us/library/dd986615)(Of [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity), [IModuleExport](/patterns-practices/reference/imoduleexport-interface-mspp-mefextensions-modularity)))

## Remarks

Import the available modules from the MEF container

## See Also

[MefModuleManager Class](/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity)  
[MefModuleManager Members](/patterns-practices/reference/mefmodulemanager-members-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  