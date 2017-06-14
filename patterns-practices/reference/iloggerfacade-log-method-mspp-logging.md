---
TOCTitle: Log Method
Title: 'ILoggerFacade.Log Method (Microsoft.Practices.Prism.Logging)'
ms:assetid: 'M:Microsoft.Practices.Prism.Logging.ILoggerFacade.Log(System.String,Microsoft.Practices.Prism.Logging.Category,Microsoft.Practices.Prism.Logging.Priority)'
ms:mtpsurl: 'iloggerfacade-log-method-mspp-logging.md'
---

# ILoggerFacade.Log Method

Write a new log entry with the specified category and priority.

**Namespace:** [Microsoft.Practices.Prism.Logging](/patterns-practices/reference/mspp-logging-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
void Log(
	string message,
	Category category,
	Priority priority
)
```

```VB
'Declaration
Sub Log ( 
	message As String,
	category As Category,
	priority As Priority
)
```
### Parameters

_message_  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>Message body to log.

_category_  
Type: [Microsoft.Practices.Prism.Logging.Category](/patterns-practices/reference/category-enumeration-mspp-logging)  
Category of the entry.

_priority_  
Type: [Microsoft.Practices.Prism.Logging.Priority](/patterns-practices/reference/priority-enumeration-mspp-logging)  
The priority of the entry

## See Also

[ILoggerFacade Interface](/patterns-practices/reference/ILoggerFacade-class-mspp-logging)<br/>
[ILoggerFacade Members](/patterns-practices/reference/ILoggerFacade-members-mspp-logging)<br/>
[Microsoft.Practices.Prism.Logging Namespace](/patterns-practices/reference/mspp-logging-namespace)<br/>