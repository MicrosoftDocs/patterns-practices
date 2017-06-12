---
TOCTitle: ConfigureContainer Method
Title: 'MefBootstrapper.ConfigureContainer Method (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper.ConfigureContainer'
ms:mtpsurl: 'mefbootstrapper-configurecontainer-method-mspp-mefextensions.md'
---

# MefBootstrapper.ConfigureContainer Method

Configures the [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553). May be overwritten in a derived class to add specific type mappings required by the application.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions](/patterns-practices/reference/mspp-mefextensions-namespace)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual void ConfigureContainer()
```

```VB
'Declaration
Protected Overridable Sub ConfigureContainer
```

## Remarks

The base implementation registers all the types direct instantiated by the bootstrapper with the container. If the method is overwritten, the new implementation should call the base class version.

## See Also

[MefBootstrapper Class](/patterns-practices/reference/mefbootstrapper-class-mspp-mefextensions)<br/>
[MefBootstrapper Members](/patterns-practices/reference/mefbootstrapper-members-mspp-mefextensions)<br/>
[Microsoft.Practices.Prism.MefExtensions Namespace](/patterns-practices/reference/mspp-mefextensions-namespace)<br/>