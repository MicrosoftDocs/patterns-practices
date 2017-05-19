---
TOCTitle: Log Method
Title: 'EmptyLogger.Log Method (Microsoft.Practices.Prism.Logging)'
ms:assetid: 'M:Microsoft.Practices.Prism.Logging.EmptyLogger.Log(System.String,Microsoft.Practices.Prism.Logging.Category,Microsoft.Practices.Prism.Logging.Priority)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405814(v=PandP.50)'
---

Prism Class Library

EmptyLogger.Log Method
==========================

This method does nothing.

**Namespace:** [Microsoft.Practices.Prism.Logging](https://msdn.microsoft.com/n:microsoft.practices.prism.logging)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public void Log( string message, Category category, Priority priority )Public Sub Log ( message As String, category As Category, priority As Priority )

### Parameters

message  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
Message body to log.

category  
Type: [Microsoft.Practices.Prism.Logging.Category](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.category)
Category of the entry.

priority  
Type: [Microsoft.Practices.Prism.Logging.Priority](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.priority)
The priority of the entry.

### Implements

[ILoggerFacade.Log(String, Category, Priority)](https://msdn.microsoft.com/m:microsoft.practices.prism.logging.iloggerfacade.log(system.string%2cmicrosoft.practices.prism.logging.category%2cmicrosoft.practices.prism.logging.priority))

See Also
--------


[EmptyLogger Class](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.emptylogger)

[EmptyLogger Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.logging.emptylogger)

[Microsoft.Practices.Prism.Logging Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.logging)
