---
TOCTitle: ConfigureContainer Method
Title: 'MefBootstrapper.ConfigureContainer Method (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper.ConfigureContainer'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405822(v=PandP.50)'
---

Prism Class Library

MefBootstrapper.ConfigureContainer Method
=============================================

Configures the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). May be overwritten in a derived class to add specific type mappings required by the application.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>protected virtual void ConfigureContainer()Protected Overridable Sub ConfigureContainer

Remarks
-------

<span id="remarksToggle"></span> The base implementation registers all the types direct instantiated by the bootstrapper with the container. If the method is overwritten, the new implementation should call the base class version.

See Also
--------


[MefBootstrapper Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.mefbootstrapper)

[MefBootstrapper Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.mefbootstrapper)

[Microsoft.Practices.Prism.MefExtensions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions)
