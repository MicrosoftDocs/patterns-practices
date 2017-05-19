---
TOCTitle: IsFrameworkExceptionRegistered Method
Title: 'ExceptionExtensions.IsFrameworkExceptionRegistered Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ExceptionExtensions.IsFrameworkExceptionRegistered(System.Type)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405791(v=PandP.50)'
---

Prism Class Library

ExceptionExtensions.IsFrameworkExceptionRegistered Method
=============================================================

Determines whether the exception type is already registered using the [RegisterFrameworkExceptionType(Type)](https://msdn.microsoft.com/m:microsoft.practices.prism.exceptionextensions.registerframeworkexceptiontype(system.type)) method

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/n:microsoft.practices.prism)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public static bool IsFrameworkExceptionRegistered( Type frameworkExceptionType )Public Shared Function IsFrameworkExceptionRegistered ( frameworkExceptionType As Type ) As Boolean

### Parameters

frameworkExceptionType  
Type: [System.Type](http://msdn2.microsoft.com/en-us/library/42892f65)
The type of framework exception to find.

### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
true if the exception type is already registered; otherwise, false.

See Also
--------


[ExceptionExtensions Class](https://msdn.microsoft.com/t:microsoft.practices.prism.exceptionextensions)

[ExceptionExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.exceptionextensions)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
