---
TOCTitle: CreateModuleCatalog Method
Title: 'Bootstrapper.CreateModuleCatalog Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.Bootstrapper.CreateModuleCatalog'
ms:mtpsurl: 'bootstrapper-createmodulecatalog-method-mspp.md'
---

# Bootstrapper.CreateModuleCatalog Method

Creates the [IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity) used by Prism.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual IModuleCatalog CreateModuleCatalog()
```
```VB
'Declaration
Protected Overridable Function CreateModuleCatalog As IModuleCatalog
```

### Return Value

Type: [IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity)

## Remarks

 The base implementation returns a new ModuleCatalog.

## See Also

[Bootstrapper Class](/patterns-practices/reference/bootstrapper-class-mspp)  
[Bootstrapper Members](/patterns-practices/reference/bootstrapper-members-mspp)  
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)  