---
TOCTitle: ExceptionExtensions Methods
Title: 'ExceptionExtensions Methods (Microsoft.Practices.Prism)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.ExceptionExtensions'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430992(v=PandP.50)'
---

Prism Class Library

ExceptionExtensions Methods
===========================

Include Protected Members
Include Inherited Members

The [ExceptionExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.exceptionextensions) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430992.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg430992.static(en-us,PandP.50).gif "Static member")
[GetRootException](https://msdn.microsoft.com/m:microsoft.practices.prism.exceptionextensions.getrootexception(system.exception))
Looks at all the inner exceptions of the exception parameter to find the most likely root cause of the exception. This works by skipping all registered exception types.

![](https://msdn.microsoft.com/en-us/Gg430992.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg430992.static(en-us,PandP.50).gif "Static member")
[IsFrameworkExceptionRegistered](https://msdn.microsoft.com/m:microsoft.practices.prism.exceptionextensions.isframeworkexceptionregistered(system.type))
Determines whether the exception type is already registered using the [RegisterFrameworkExceptionType(Type)](https://msdn.microsoft.com/m:microsoft.practices.prism.exceptionextensions.registerframeworkexceptiontype(system.type)) method

![](https://msdn.microsoft.com/en-us/Gg430992.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg430992.static(en-us,PandP.50).gif "Static member")
[RegisterFrameworkExceptionType](https://msdn.microsoft.com/m:microsoft.practices.prism.exceptionextensions.registerframeworkexceptiontype(system.type))
Register the type of an Exception that is thrown by the framework. The [GetRootException(Exception)](https://msdn.microsoft.com/m:microsoft.practices.prism.exceptionextensions.getrootexception(system.exception)) method uses this list of Exception types to find out if something has gone wrong.

See Also
--------

<span id="seeAlsoToggle"></span>
[ExceptionExtensions Class](https://msdn.microsoft.com/t:microsoft.practices.prism.exceptionextensions)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
