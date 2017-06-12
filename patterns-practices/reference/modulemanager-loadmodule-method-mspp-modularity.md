---
TOCTitle: LoadModule Method
Title: 'ModuleManager.LoadModule Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleManager.LoadModule(System.String)'
ms:mtpsurl: 'modulemanager-loadmodule-method-mspp-modularity.md'
---

# ModuleManager.LoadModule Method

Loads and initializes the module on the [ModuleCatalog](/patterns-practices/reference/modulemanager-modulecatalog-property-mspp-modularity) with the name *moduleName*.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void LoadModule(
	string moduleName
)
```

```VB
'Declaration
Public Sub LoadModule ( 
	moduleName As String
)
```

### Parameters

*moduleName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
Name of the module requested for initialization.

### Implements

[IModuleManager.LoadModule(String)](/patterns-practices/reference/imodulemanager-loadmodule-method-mspp-modularity)

## See Also

[ModuleManager Class](/patterns-practices/reference/modulemanager-class-mspp-modularity)<br/>
[ModuleManager Members](/patterns-practices/reference/modulemanager-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>