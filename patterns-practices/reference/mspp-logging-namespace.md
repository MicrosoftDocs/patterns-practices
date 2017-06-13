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
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[EmptyLogger](/patterns-practices/reference/emptylogger-class-mspp-logging)</td>
<td><div class="summary">
Implementation of [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) that does nothing. This implementation is useful when the application does not need logging but there are infrastructure pieces that assume there is a logger.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[TextLogger](/patterns-practices/reference/textlogger-class-mspp-logging)</td>
<td><div class="summary">
Implementation of [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) that logs into a [TextWriter](http://msdn.microsoft.com/en-us/library/ywxh2328).
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[TraceLogger](/patterns-practices/reference/tracelogger-class-mspp-logging)</td>
<td><div class="summary">
Implementation of [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) that logs to .NET [Trace](http://msdn.microsoft.com/en-us/library/36hhw2t6) class.
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
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)</td>
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
<td>![Public enumeration](/patterns-practices/reference/images/pubenumeration.gif)</td>
<td>[Category](/patterns-practices/reference/category-enumeration-mspp-logging)</td>
<td><div class="summary">
Defines values for the categories used by [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging).
</div></td>
</tr>
<tr class="even">
<td>![Public enumeration](/patterns-practices/reference/images/pubenumeration.gif)</td>
<td>[Priority](/patterns-practices/reference/priority-enumeration-mspp-logging)</td>
<td><div class="summary">
Defines values for the priorities used by [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging).
</div></td>
</tr>
</tbody>
</table>
