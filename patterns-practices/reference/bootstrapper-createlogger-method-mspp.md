---
TOCTitle: CreateLogger Method
Title: 'Bootstrapper.CreateLogger Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.Bootstrapper.CreateLogger'
ms:mtpsurl: 'bootstrapper-createlogger-method-mspp.md'
---


# Bootstrapper.CreateLogger Method

Create the [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) used by the bootstrapper.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual ILoggerFacade CreateLogger()
```

```VB
'Declaration
Protected Overridable Function CreateLogger As ILoggerFacade
```            

### Return Value

Type: [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)

## Remarks

 The base implementation returns a new TextLogger.

## See Also

[Bootstrapper Class](/patterns-practices/reference/bootstrapper-class-mspp)

[Bootstrapper Members](/patterns-practices/reference/bootstrapper-members-mspp)

[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)
