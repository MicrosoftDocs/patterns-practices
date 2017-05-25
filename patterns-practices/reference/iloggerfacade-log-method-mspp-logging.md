---
TOCTitle: Log Method
Title: 'ILoggerFacade.Log Method (Microsoft.Practices.Prism.Logging)'
ms:assetid: 'M:Microsoft.Practices.Prism.Logging.ILoggerFacade.Log(System.String,Microsoft.Practices.Prism.Logging.Category,Microsoft.Practices.Prism.Logging.Priority)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405815(v=PandP.50)'
---


# ILoggerFacade.Log Method

Write a new log entry with the specified category and priority.

**Namespace:** [Microsoft.Practices.Prism.Logging](https://msdn.microsoft.com/library/microsoft.practices.prism.logging)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

void Log( string message, Category category, Priority priority )Sub Log ( message As String, category As Category, priority As Priority )

### Parameters

message  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
Message body to log.

category  
Type: [Microsoft.Practices.Prism.Logging.Category](https://msdn.microsoft.com/library/microsoft.practices.prism.logging.category)
Category of the entry.

priority  
Type: [Microsoft.Practices.Prism.Logging.Priority](https://msdn.microsoft.com/library/microsoft.practices.prism.logging.priority)
The priority of the entry.

## See Also

[ILoggerFacade Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade)

[ILoggerFacade Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.logging.iloggerfacade)

[Microsoft.Practices.Prism.Logging Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.logging)
