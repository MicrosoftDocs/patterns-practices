---
TOCTitle: ModuleTypeLoaders Property
Title: 'ModuleManager.ModuleTypeLoaders Property (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.Modularity.ModuleManager.ModuleTypeLoaders'
ms:mtpsurl: 'modulemanager-moduletypeloaders-property-mspp-modularity.md'
---
# ModuleManager.ModuleTypeLoaders Property

Returns the list of registered [IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity) instances that will be used to load the types of modules.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public virtual IEnumerable<IModuleTypeLoader> ModuleTypeLoaders { get; set; }
```

### Property Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)&gt;  
The module type loaders.

```VB
'Declaration
Public Overridable Property ModuleTypeLoaders As IEnumerable(Of IModuleTypeLoader)
	Get
	Set
```

### Property Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity))  
The module type loaders.

## See Also

[ModuleManager Class](/patterns-practices/reference/modulemanager-class-mspp-modularity)  
[ModuleManager Members](/patterns-practices/reference/modulemanager-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>

