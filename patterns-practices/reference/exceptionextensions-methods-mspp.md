---
TOCTitle: ExceptionExtensions Methods
Title: 'ExceptionExtensions Methods (Microsoft.Practices.Prism)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.ExceptionExtensions'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.exceptionextensions_methods(v=pandp.50)'
---

Prism Class Library

ExceptionExtensions Methods
===========================

The [ExceptionExtensions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.exceptionextensions(v=pandp.50)) type exposes the following members.

Methods
-------

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg430992.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions.getrootexception(system.exception)">GetRootException</a></td>
<td><div class="summary">
Looks at all the inner exceptions of the exception parameter to find the most likely root cause of the exception. This works by skipping all registered exception types.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg430992.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions.isframeworkexceptionregistered(system.type)">IsFrameworkExceptionRegistered</a></td>
<td><div class="summary">
Determines whether the exception type is already registered using the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions.registerframeworkexceptiontype(system.type)">RegisterFrameworkExceptionType(Type)</a> method
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg430992.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions.registerframeworkexceptiontype(system.type)">RegisterFrameworkExceptionType</a></td>
<td><div class="summary">
Register the type of an Exception that is thrown by the framework. The <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions.getrootexception(system.exception)">GetRootException(Exception)</a> method uses this list of Exception types to find out if something has gone wrong.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[ExceptionExtensions Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.exceptionextensions(v=pandp.50))

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism(v=pandp.50))
