---
TOCTitle: CreateContainer Method
Title: 'MefBootstrapper.CreateContainer Method (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper.CreateContainer'
ms:mtpsurl: 'mefbootstrapper-createcontainer-method-mspp-mefextensions.md'
---

# MefBootstrapper.CreateContainer Method

Creates the [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553) that will be used as the default container.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions](/patterns-practices/reference/mspp-mefextensions-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual CompositionContainer CreateContainer()
```
```VB
'Declaration
Protected Overridable Function CreateContainer As CompositionContainer
```

### Return Value

Type: [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553)  
A new instance of [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553).

## Remarks

 The base implementation registers a default MEF catalog of exports of key Prism types. Exporting your own types will replace these defaults.

## See Also

[MefBootstrapper Class](/patterns-practices/reference/mefbootstrapper-class-mspp-mefextensions)  
[MefBootstrapper Members](/patterns-practices/reference/mefbootstrapper-members-mspp-mefextensions)  
[Microsoft.Practices.Prism.MefExtensions Namespace](/patterns-practices/reference/mspp-mefextensions-namespace)  