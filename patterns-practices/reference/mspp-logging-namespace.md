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
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/emptylogger-class-mspp-logging" data-raw-source="[EmptyLogger](/patterns-practices/reference/emptylogger-class-mspp-logging)">EmptyLogger</a></td>
<td><div class="summary">
Implementation of <a href="/patterns-practices/reference/iloggerfacade-interface-mspp-logging" data-raw-source="[ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)">ILoggerFacade</a> that does nothing. This implementation is useful when the application does not need logging but there are infrastructure pieces that assume there is a logger.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/textlogger-class-mspp-logging" data-raw-source="[TextLogger](/patterns-practices/reference/textlogger-class-mspp-logging)">TextLogger</a></td>
<td><div class="summary">
Implementation of <a href="/patterns-practices/reference/iloggerfacade-interface-mspp-logging" data-raw-source="[ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)">ILoggerFacade</a> that logs into a <a href="http://msdn.microsoft.com/en-us/library/ywxh2328" data-raw-source="[TextWriter](http://msdn.microsoft.com/en-us/library/ywxh2328)">TextWriter</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/tracelogger-class-mspp-logging" data-raw-source="[TraceLogger](/patterns-practices/reference/tracelogger-class-mspp-logging)">TraceLogger</a></td>
<td><div class="summary">
Implementation of <a href="/patterns-practices/reference/iloggerfacade-interface-mspp-logging" data-raw-source="[ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)">ILoggerFacade</a> that logs to .NET <a href="http://msdn.microsoft.com/en-us/library/36hhw2t6" data-raw-source="[Trace](http://msdn.microsoft.com/en-us/library/36hhw2t6)">Trace</a> class.
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
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iloggerfacade-interface-mspp-logging" data-raw-source="[ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)">ILoggerFacade</a></td>
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
<td><img src="/patterns-practices/reference/images/pubenumeration.gif" alt="Public enumeration"/></td>
<td><a href="/patterns-practices/reference/category-enumeration-mspp-logging" data-raw-source="[Category](/patterns-practices/reference/category-enumeration-mspp-logging)">Category</a></td>
<td><div class="summary">
Defines values for the categories used by <a href="/patterns-practices/reference/iloggerfacade-interface-mspp-logging" data-raw-source="[ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)">ILoggerFacade</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubenumeration.gif" alt="Public enumeration"/></td>
<td><a href="/patterns-practices/reference/priority-enumeration-mspp-logging" data-raw-source="[Priority](/patterns-practices/reference/priority-enumeration-mspp-logging)">Priority</a></td>
<td><div class="summary">
Defines values for the priorities used by <a href="/patterns-practices/reference/iloggerfacade-interface-mspp-logging" data-raw-source="[ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)">ILoggerFacade</a>.
</div></td>
</tr>
</tbody>
</table>
