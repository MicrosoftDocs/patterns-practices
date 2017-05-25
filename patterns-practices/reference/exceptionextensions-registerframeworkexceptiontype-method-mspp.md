---
TOCTitle: RegisterFrameworkExceptionType Method
Title: 'ExceptionExtensions.RegisterFrameworkExceptionType Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ExceptionExtensions.RegisterFrameworkExceptionType(System.Type)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405792(v=PandP.50)'
---


# ExceptionExtensions.RegisterFrameworkExceptionType Method

Register the type of an Exception that is thrown by the framework. The [GetRootException(Exception)](https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions.getrootexception(system.exception)) method uses this list of Exception types to find out if something has gone wrong.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/library/microsoft.practices.prism)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public static void RegisterFrameworkExceptionType( Type frameworkExceptionType )Public Shared Sub RegisterFrameworkExceptionType ( frameworkExceptionType As Type )

### Parameters

frameworkExceptionType  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
The type of exception to register.

## See Also

[ExceptionExtensions Class](https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions)

[ExceptionExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.exceptionextensions)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism)
