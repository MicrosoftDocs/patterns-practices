---
TOCTitle: CreateLogger Method
Title: 'Bootstrapper.CreateLogger Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.Bootstrapper.CreateLogger'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431150(v=PandP.50)'
---

Prism Class Library

Bootstrapper.CreateLogger Method
====================================

Create the [ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade) used by the bootstrapper.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/n:microsoft.practices.prism)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


protected virtual ILoggerFacade CreateLogger()Protected Overridable Function CreateLogger As ILoggerFacade
### Return Value

Type: [ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade)

Remarks
-------

<span id="remarksToggle"></span> The base implementation returns a new TextLogger.

See Also
--------


[Bootstrapper Class](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper)

[Bootstrapper Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.bootstrapper)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
