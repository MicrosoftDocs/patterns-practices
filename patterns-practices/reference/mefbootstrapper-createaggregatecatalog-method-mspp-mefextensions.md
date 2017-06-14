---
TOCTitle: CreateAggregateCatalog Method
Title: 'MefBootstrapper.CreateAggregateCatalog Method (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper.CreateAggregateCatalog'
ms:mtpsurl: 'mefbootstrapper-createaggregatecatalog-method-mspp-mefextensions.md'
---

# MefBootstrapper.CreateAggregateCatalog Method

Configures the [AggregateCatalog](/patterns-practices/reference/mefbootstrapper-aggregatecatalog-property-mspp-mefextensions) used by MEF.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions](/patterns-practices/reference/mspp-mefextensions-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual AggregateCatalog CreateAggregateCatalog()
```
```VB
'Declaration
Protected Overridable Function CreateAggregateCatalog As AggregateCatalog
```

### Return Value

Type: [AggregateCatalog](http://msdn.microsoft.com/en-us/library/dd833165)  
An [AggregateCatalog](/patterns-practices/reference/mefbootstrapper-aggregatecatalog-property-mspp-mefextensions) to be used by the bootstrapper.

## Remarks

 The base implementation returns a new AggregateCatalog.

## See Also
[MefBootstrapper Class](/patterns-practices/reference/mefbootstrapper-class-mspp-mefextensions)  
[MefBootstrapper Members](/patterns-practices/reference/mefbootstrapper-members-mspp-mefextensions)  
[Microsoft.Practices.Prism.MefExtensions Namespace](/patterns-practices/reference/mspp-mefextensions-namespace)  