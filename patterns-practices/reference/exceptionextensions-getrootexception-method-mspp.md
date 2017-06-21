---
TOCTitle: GetRootException Method
Title: 'ExceptionExtensions.GetRootException Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ExceptionExtensions.GetRootException(System.Exception)'
ms:mtpsurl: 'exceptionextensions-getrootexception-method-mspp.md'
---

# ExceptionExtensions.GetRootException Method

Looks at all the inner exceptions of the *exception* parameter to find the most likely root cause of the exception. This works by skipping all registered exception types.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static Exception GetRootException(
	this Exception exception
)
```

```VB
'Declaration
<ExtensionAttribute> 
Public Shared Function GetRootException ( 
	exception As Exception
) As Exception
```

### Parameters

*exception*  
Type: [System.Exception](http://msdn.microsoft.com/en-us/library/c18k6c59)  
The exception that will provide the list of inner exeptions to examine.

### Return Value

Type: [Exception](http://msdn.microsoft.com/en-us/library/c18k6c59)  
The exception that most likely caused the exception to occur. If it can't find the root exception, it will return the exception value itself.

### Usage Note

In Visual Basic and C#, you can call this method as an instance method on any object of type [Exception](http://msdn.microsoft.com/en-us/library/c18k6c59). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## Remarks

This method is not 100% accurate and should only be used to point a developer into the most likely direction. It should not be used to replace the Inner Exception stack of an exception, because this might hide required exception information.

## See Also

[ExceptionExtensions Class](/patterns-practices/reference/exceptionextensions-class-mspp)  
[ExceptionExtensions Members](/patterns-practices/reference/exceptionextensions-members-mspp)  
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)  