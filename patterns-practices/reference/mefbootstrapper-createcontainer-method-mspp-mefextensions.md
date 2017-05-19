---
TOCTitle: CreateContainer Method
Title: 'MefBootstrapper.CreateContainer Method (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper.CreateContainer'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405825(v=PandP.50)'
---

Prism Class Library

MefBootstrapper.CreateContainer Method
==========================================

Creates the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553) that will be used as the default container.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>protected virtual CompositionContainer CreateContainer()Protected Overridable Function CreateContainer As CompositionContainer
#### Return Value

Type: [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553)
A new instance of [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553).

Remarks
-------

<span id="remarksToggle"></span> The base implementation registers a default MEF catalog of exports of key Prism types. Exporting your own types will replace these defaults.

See Also
--------


[MefBootstrapper Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.mefbootstrapper)

[MefBootstrapper Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.mefbootstrapper)

[Microsoft.Practices.Prism.MefExtensions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions)
