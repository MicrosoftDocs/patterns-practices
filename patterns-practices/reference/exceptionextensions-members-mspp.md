---
TOCTitle: ExceptionExtensions Members
Title: 'ExceptionExtensions Members (Microsoft.Practices.Prism)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.ExceptionExtensions'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430779(v=PandP.50)'
---

Prism Class Library

ExceptionExtensions Members
===========================

The [ExceptionExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.exceptionextensions) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430779.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg430779.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.exceptionextensions.getrootexception(system.exception)">GetRootException</a></td>
<td><div class="summary">
Looks at all the inner exceptions of the exception parameter to find the most likely root cause of the exception. This works by skipping all registered exception types.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430779.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg430779.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.exceptionextensions.isframeworkexceptionregistered(system.type)">IsFrameworkExceptionRegistered</a></td>
<td><div class="summary">
Determines whether the exception type is already registered using the <a href="https://msdn.microsoft.com/m:microsoft.practices.prism.exceptionextensions.registerframeworkexceptiontype(system.type)">RegisterFrameworkExceptionType(Type)</a> method
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430779.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg430779.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.exceptionextensions.registerframeworkexceptiontype(system.type)">RegisterFrameworkExceptionType</a></td>
<td><div class="summary">
Register the type of an Exception that is thrown by the framework. The <a href="https://msdn.microsoft.com/m:microsoft.practices.prism.exceptionextensions.getrootexception(system.exception)">GetRootException(Exception)</a> method uses this list of Exception types to find out if something has gone wrong.
</div></td>
</tr>
</tbody>
</table>

See Also
--------

<span id="seeAlsoToggle"></span>
[ExceptionExtensions Class](https://msdn.microsoft.com/t:microsoft.practices.prism.exceptionextensions)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
