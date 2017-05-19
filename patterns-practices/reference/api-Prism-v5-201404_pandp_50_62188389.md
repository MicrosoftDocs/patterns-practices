---
TOCTitle: ExceptionExtensions Methods
Title: 'ExceptionExtensions Methods (Microsoft.Practices.Prism)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.ExceptionExtensions'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430992(v=PandP.50)'
---

Prism Class Library

ExceptionExtensions Methods
===========================



The [ExceptionExtensions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.exceptionextensions(v=pandp.50)) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430992.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg430992.static(en-us,PandP.50).gif "Static member")
[GetRootException](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.exceptionextensions.getrootexception(v=pandp.50))
Looks at all the inner exceptions of the exception parameter to find the most likely root cause of the exception. This works by skipping all registered exception types.

![](https://msdn.microsoft.com/en-us/Gg430992.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg430992.static(en-us,PandP.50).gif "Static member")
[IsFrameworkExceptionRegistered](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.exceptionextensions.isframeworkexceptionregistered(v=pandp.50))
Determines whether the exception type is already registered using the [RegisterFrameworkExceptionType(Type)](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.exceptionextensions.registerframeworkexceptiontype(v=pandp.50)) method

![](https://msdn.microsoft.com/en-us/Gg430992.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg430992.static(en-us,PandP.50).gif "Static member")
[RegisterFrameworkExceptionType](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.exceptionextensions.registerframeworkexceptiontype(v=pandp.50))
Register the type of an Exception that is thrown by the framework. The [GetRootException(Exception)](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.exceptionextensions.getrootexception(v=pandp.50)) method uses this list of Exception types to find out if something has gone wrong.

See Also
--------

<span id="seeAlsoToggle"></span>
[ExceptionExtensions Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.exceptionextensions(v=pandp.50))

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism(v=pandp.50))
