---
TOCTitle: MefBootstrapper Class
Title: 'MefBootstrapper Class (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper'
ms:mtpsurl: 'mefbootstrapper-class-mspp-mefextensions.md'
---

# MefBootstrapper Class

Base class that provides a basic bootstrapping sequence that registers most of the Prism Library assets in a MEF [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions](/patterns-practices/reference/mspp-mefextensions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public abstract class MefBootstrapper : Bootstrapper
```

```VB
'Declaration
Public MustInherit Class MefBootstrapper
	Inherits Bootstrapper
```

## Remarks

 This class must be overridden to provide application specific configuration.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [Microsoft.Practices.Prism.Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp)  
    Microsoft.Practices.Prism.MefExtensions.MefBootstrapper

## See Also

[MefBootstrapper Members](/patterns-practices/reference/mefbootstrapper-members-mspp-mefextensions)<br/>
[Microsoft.Practices.Prism.MefExtensions Namespace](/patterns-practices/reference/mspp-mefextensions-namespace)<br/>