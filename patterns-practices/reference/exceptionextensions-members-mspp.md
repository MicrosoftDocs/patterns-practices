---
TOCTitle: ExceptionExtensions Members
Title: 'ExceptionExtensions Members (Microsoft.Practices.Prism)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.ExceptionExtensions'
ms:mtpsurl: 'exceptionextensions-members-mspp.md'
---

# ExceptionExtensions Members

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
<td><a href="/patterns-practices/reference/exceptionextensions-getrootexception-method-mspp">GetRootException</a></td>
<td><div class="summary">
Looks at all the inner exceptions of the exception parameter to find the most likely root cause of the exception. This works by skipping all registered exception types.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td><a href="/patterns-practices/reference/exceptionextensions-isframeworkexceptionregistered-method-mspp">IsFrameworkExceptionRegistered</a></td>
<td><div class="summary">
Determines whether the exception type is already registered using the <a href="/patterns-practices/reference/exceptionextensions-registerframeworkexceptiontype-method-mspp">RegisterFrameworkExceptionType(Type)</a> method
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td><a href="/patterns-practices/reference/exceptionextensions-registerframeworkexceptiontype-method-mspp">RegisterFrameworkExceptionType</a></td>
<td><div class="summary">
Register the type of an Exception that is thrown by the framework. The <a href="/patterns-practices/reference/exceptionextensions-getrootexception-method-mspp">GetRootException(Exception)</a> method uses this list of Exception types to find out if something has gone wrong.
</div></td>
</tr>
</tbody>
</table>

## See Also

[ExceptionExtensions Class](/patterns-practices/reference/exceptionextensions-class-mspp)<br/>
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)<br/>
