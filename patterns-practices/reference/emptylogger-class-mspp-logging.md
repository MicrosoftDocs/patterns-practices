---
TOCTitle: EmptyLogger Class
Title: 'EmptyLogger Class (Microsoft.Practices.Prism.Logging)'
ms:assetid: 'T:Microsoft.Practices.Prism.Logging.EmptyLogger'
ms:mtpsurl: 'emptylogger-class-mspp-logging.md'
---

# EmptyLogger Class

Implementation of [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) that does nothing. This implementation is useful when the application does not need logging but there are infrastructure pieces that assume there is a logger.

**Namespace:** [Microsoft.Practices.Prism.Logging](/patterns-practices/reference/mspp-logging-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class EmptyLogger : ILoggerFacade
```
```VB
'Declaration
Public Class EmptyLogger
	Implements ILoggerFacade
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  Microsoft.Practices.Prism.Logging.EmptyLogger

## See Also

[EmptyLogger Members](/patterns-practices/reference/emptylogger-members-mspp-logging)  
[Microsoft.Practices.Prism.Logging Namespace](/patterns-practices/reference/mspp-logging-namespace)