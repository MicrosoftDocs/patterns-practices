---
TOCTitle: Log Method
Title: 'EmptyLogger.Log Method (Microsoft.Practices.Prism.Logging)'
ms:assetid: 'M:Microsoft.Practices.Prism.Logging.EmptyLogger.Log(System.String,Microsoft.Practices.Prism.Logging.Category,Microsoft.Practices.Prism.Logging.Priority)'
ms:mtpsurl: 'emptylogger-log-method-mspp-logging.md'
---

# EmptyLogger.Log Method

This method does nothing.

**Namespace:** [Microsoft.Practices.Prism.Logging](/patterns-practices/reference/mspp-logging-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void Log(
	string message,
	Category category,
	Priority priority
)
```

```VB
'Declaration
Public Sub Log ( 
	message As String,
	category As Category,
	priority As Priority
)
```

### Parameters

_message_  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
Message body to log.

_category_  
Type: [Microsoft.Practices.Prism.Logging.Category](/patterns-practices/reference/category-enumeration-mspp-logging)  
Category of the entry.

_priority_  
Type: [Microsoft.Practices.Prism.Logging.Priority](/patterns-practices/reference/priority-enumeration-mspp-logging)  
The priority of the entry.

### Implements

[ILoggerFacade.Log(String, Category, Priority)](/patterns-practices/reference/iloggerfacade-log-method-mspp-logging)

## See Also

[EmptyLogger Class](/patterns-practices/reference/emptylogger-class-mspp-logging)

[EmptyLogger Members](/patterns-practices/reference/emptylogger-members-mspp-logging)

[Microsoft.Practices.Prism.Logging Namespace](/patterns-practices/reference/mspp-logging-namespace)
