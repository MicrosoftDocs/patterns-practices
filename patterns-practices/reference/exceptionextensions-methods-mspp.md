---
TOCTitle: ExceptionExtensions Methods
Title: 'ExceptionExtensions Methods (Microsoft.Practices.Prism)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.ExceptionExtensions'
ms:mtpsurl: 'exceptionextensions-methods-mspp.md'
---

# ExceptionExtensions Methods

The [ExceptionExtensions](/patterns-practices/reference/exceptionextensions-class-mspp) type exposes the following members.

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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[GetRootException](/patterns-practices/reference/exceptionextensions-getrootexception-method-mspp)</td>
<td><div class="summary">
Looks at all the inner exceptions of the exception parameter to find the most likely root cause of the exception. This works by skipping all registered exception types.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[IsFrameworkExceptionRegistered](/patterns-practices/reference/exceptionextensions-isframeworkexceptionregistered-method-mspp)</td>
<td><div class="summary">
Determines whether the exception type is already registered using the [RegisterFrameworkExceptionType(Type)](/patterns-practices/reference/exceptionextensions-registerframeworkexceptiontype-method-mspp) method
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RegisterFrameworkExceptionType](/patterns-practices/reference/exceptionextensions-registerframeworkexceptiontype-method-mspp)</td>
<td><div class="summary">
Register the type of an Exception that is thrown by the framework. The [GetRootException(Exception)](/patterns-practices/reference/exceptionextensions-getrootexception-method-mspp) method uses this list of Exception types to find out if something has gone wrong.
</div></td>
</tr>
</tbody>
</table>

## See Also

[ExceptionExtensions Class](/patterns-practices/reference/exceptionextensions-class-mspp)  
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)  