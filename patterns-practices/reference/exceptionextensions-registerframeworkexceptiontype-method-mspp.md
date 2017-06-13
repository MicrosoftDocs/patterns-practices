---
TOCTitle: RegisterFrameworkExceptionType Method
Title: 'ExceptionExtensions.RegisterFrameworkExceptionType Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ExceptionExtensions.RegisterFrameworkExceptionType(System.Type)'
ms:mtpsurl: 'exceptionextensions-registerframeworkexceptiontype-method-mspp.md'
---

# ExceptionExtensions.RegisterFrameworkExceptionType Method

Register the type of an Exception that is thrown by the framework. The [GetRootException(Exception)](/patterns-practices/reference/exceptionextensions-getrootexception-method-mspp) method uses this list of Exception types to find out if something has gone wrong.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static void RegisterFrameworkExceptionType(
	Type frameworkExceptionType
)
```
```VB
'Declaration
Public Shared Sub RegisterFrameworkExceptionType ( 
	frameworkExceptionType As Type
)
```

### Parameters

_frameworkExceptionType_  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
The type of exception to register.

## See Also

[ExceptionExtensions Class](/patterns-practices/reference/exceptionextensions-class-mspp)<br/>
[ExceptionExtensions Members](/patterns-practices/reference/exceptionextensions-members-mspp)<br/>
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)<br/>