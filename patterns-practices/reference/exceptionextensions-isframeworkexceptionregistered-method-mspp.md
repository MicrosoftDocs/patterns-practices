---
TOCTitle: IsFrameworkExceptionRegistered Method
Title: 'ExceptionExtensions.IsFrameworkExceptionRegistered Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ExceptionExtensions.IsFrameworkExceptionRegistered(System.Type)'
ms:mtpsurl: 'exceptionextensions-isframeworkexceptionregistered-method-mspp.md'
---

# ExceptionExtensions.IsFrameworkExceptionRegistered Method

Determines whether the exception type is already registered using the [RegisterFrameworkExceptionType(Type)](/patterns-practices/reference/exceptionextensions-registerframeworkexceptiontype-method-mspp) method

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static bool IsFrameworkExceptionRegistered(
	Type frameworkExceptionType
)
```

```VB
'Declaration
Public Shared Function IsFrameworkExceptionRegistered ( 
	frameworkExceptionType As Type
) As Boolean
```

### Parameters

_frameworkExceptionType_  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
The type of framework exception to find.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
true if the exception type is already registered; otherwise, false.

## See Also

[ExceptionExtensions Class](/patterns-practices/reference/exceptionextensions-class-mspp)  
[ExceptionExtensions Members](/patterns-practices/reference/exceptionextensions-members-mspp)  
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)  
