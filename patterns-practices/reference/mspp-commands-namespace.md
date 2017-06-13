---
TOCTitle: 'Microsoft.Practices.Prism.Commands Namespace'
Title: 'Microsoft.Practices.Prism.Commands Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Commands'
ms:mtpsurl: 'mspp-commands-namespace.md'
---


# Microsoft.Practices.Prism.Commands Namespace

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
<td>[CompositeCommand](/patterns-practices/reference/compositecommand-class-mspp-commands)</td>
<td><div class="summary">
The CompositeCommand composes one or more ICommands.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)</td>
<td><div class="summary">
An [ICommand](http://msdn.microsoft.com/en-us/library/ms616869) whose delegates do not take any parameters for [Execute](/patterns-practices/reference/delegatecommand-execute-method-mspp-commands) and [CanExecute](/patterns-practices/reference/delegatecommand-canexecute-method-mspp-commands).
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[DelegateCommand(Of T)](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)</td>
<td><div class="summary">
An [ICommand](http://msdn.microsoft.com/en-us/library/ms616869) whose delegates can be attached for [Execute(T)](/patterns-practices/reference/delegatecommand-t-execute-method-t-mspp-commands) and [CanExecute(T)](/patterns-practices/reference/delegatecommand-t-canexecute-method-t-mspp-commands).
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)</td>
<td><div class="summary">
An [ICommand](http://msdn.microsoft.com/en-us/library/ms616869) whose delegates can be attached for [Execute(Object)](/patterns-practices/reference/delegatecommandbase-execute-method-mspp-commands) and [CanExecute(Object)](/patterns-practices/reference/delegatecommandbase-canexecute-method-mspp-commands).
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[WeakEventHandlerManager](/patterns-practices/reference/weakeventhandlermanager-class-mspp-commands)</td>
<td><div class="summary">
Handles management and dispatching of EventHandlers in a weak way.
</div></td>
</tr>
</tbody>
</table>
