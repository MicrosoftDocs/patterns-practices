---
TOCTitle: ExceptionExtensions Methods
Title: 'ExceptionExtensions Methods (Microsoft.Practices.Prism)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.ExceptionExtensions'
ms:mtpsurl: 'exceptionextensions-methods-mspp.md'
---

# ExceptionExtensions Methods

The [ExceptionExtensions](exceptionextensions-class-mspp) type exposes the following members.

## Methods

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
<td>![Public method](/images/public-method.gif)![Static member](/images/static.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions.getrootexception(system.exception)">GetRootException</a></td>
<td><div class="summary">
Looks at all the inner exceptions of the exception parameter to find the most likely root cause of the exception. This works by skipping all registered exception types.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)![Static member](/images/static.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions.isframeworkexceptionregistered(system.type)">IsFrameworkExceptionRegistered</a></td>
<td><div class="summary">
Determines whether the exception type is already registered using the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions.registerframeworkexceptiontype(system.type)">RegisterFrameworkExceptionType(Type)</a> method
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)![Static member](/images/static.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions.registerframeworkexceptiontype(system.type)">RegisterFrameworkExceptionType</a></td>
<td><div class="summary">
Register the type of an Exception that is thrown by the framework. The <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions.getrootexception(system.exception)">GetRootException(Exception)</a> method uses this list of Exception types to find out if something has gone wrong.
</div></td>
</tr>
</tbody>
</table>

## See Also
[ExceptionExtensions Class](exceptionextensions-class-mspp)

[Microsoft.Practices.Prism Namespace](mspp-namespace)
