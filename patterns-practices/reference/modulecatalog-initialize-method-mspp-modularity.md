---
TOCTitle: Initialize Method
Title: 'ModuleCatalog.Initialize Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.Initialize'
ms:mtpsurl: 'modulecatalog-initialize-method-mspp-modularity.md'
---


# ModuleCatalog.Initialize Method

Initializes the catalog, which may load and validate the modules.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


```C#
public virtual void Initialize()
```
### Implements

[IModuleCatalog.Initialize()](/patterns-practices/reference/imodulecatalog-initialize-method-mspp-modularity)

## Exceptions


| Exception                                                                                                                                             | Condition                                                                                                                                                                                                                                                            |
|-------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Microsoft.Practices.Prism.Modularity.ModularityException](/patterns-practices/reference/modularityexception-class-mspp-modularity) | When validation of the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) fails, because this method calls [Validate()](/patterns-practices/reference/modulecatalog-validate-method-mspp-modularity). |



```VB
'Declaration
Public Overridable Sub Initialize
```
### Implements

[IModuleCatalog.Initialize](/patterns-practices/reference/imodulecatalog-initialize-method-mspp-modularity)

## Exceptions


| Exception                                                                                                                                             | Condition                                                                                                                                                                                                                                                            |
|-------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Microsoft.Practices.Prism.Modularity.ModularityException](/patterns-practices/reference/modularityexception-class-mspp-modularity) | When validation of the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) fails, because this method calls [Validate](/patterns-practices/reference/modulecatalog-validate-method-mspp-modularity). |

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)<br/>
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>