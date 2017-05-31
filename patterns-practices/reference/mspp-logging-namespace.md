---
TOCTitle: 'Microsoft.Practices.Prism.Logging Namespace'
Title: 'Microsoft.Practices.Prism.Logging Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Logging'
ms:mtpsurl: 'mspp-logging-namespace.md'
---

# Microsoft.Practices.Prism.Logging Namespace

 

## Classes


<table>

<thead>
<tr class="header">
<th> </th>
<th>Class</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.emptylogger">EmptyLogger</a></td>
<td><div class="summary">
Implementation of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> that does nothing. This implementation is useful when the application does not need logging but there are infrastructure pieces that assume there is a logger.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.textlogger">TextLogger</a></td>
<td><div class="summary">
Implementation of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> that logs into a <a href="http://msdn.microsoft.com/en-us/library/ywxh2328">TextWriter</a>.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.tracelogger">TraceLogger</a></td>
<td><div class="summary">
Implementation of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> that logs to .NET <a href="http://msdn.microsoft.com/en-us/library/36hhw2t6">Trace</a> class.
</div></td>
</tr>
</tbody>
</table>

## Interfaces


<table>

<thead>
<tr class="header">
<th> </th>
<th>Interface</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public interface](/images/public-interface.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a></td>
<td><div class="summary">
Defines a simple logger façade to be used by the Prism Library.
</div></td>
</tr>
</tbody>
</table>

## Enumerations


<table>

<thead>
<tr class="header">
<th> </th>
<th>Enumeration</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public enumeration](/images/pubenumeration.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.category">Category</a></td>
<td><div class="summary">
Defines values for the categories used by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a>.
</div></td>
</tr>
<tr class="even">
<td>![Public enumeration](/images/pubenumeration.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.priority">Priority</a></td>
<td><div class="summary">
Defines values for the priorities used by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a>.
</div></td>
</tr>
</tbody>
</table>
