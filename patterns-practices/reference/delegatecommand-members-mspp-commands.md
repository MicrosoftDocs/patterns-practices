---
TOCTitle: DelegateCommand Members
Title: 'DelegateCommand Members (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Commands.DelegateCommand'
ms:mtpsurl: 'delegatecommand-members-mspp-commands.md'
---

# DelegateCommand Members

The [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands) type exposes the following members.

## Constructors

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/delegatecommand-class-mspp-commands" data-raw-source="[DelegateCommand(Action)](/patterns-practices/reference/delegatecommand-class-mspp-commands)">DelegateCommand(Action)</a></td>
<td><div class="summary">
Creates a new instance of <a href="/patterns-practices/reference/delegatecommand-class-mspp-commands" data-raw-source="[DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)">DelegateCommand</a> with the <a href="http://msdn.microsoft.com/en-us/library/bb534741" data-raw-source="[Action](http://msdn.microsoft.com/en-us/library/bb534741)">Action</a> to invoke on execution.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/delegatecommand-class-mspp-commands" data-raw-source="[DelegateCommand(Action, Func&amp;lt;Boolean&amp;gt;)](/patterns-practices/reference/delegatecommand-class-mspp-commands)">DelegateCommand(Action, Func&lt;Boolean&gt;)</a></td>
<td><div class="summary">
Creates a new instance of <a href="/patterns-practices/reference/delegatecommand-class-mspp-commands" data-raw-source="[DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)">DelegateCommand</a> with the <a href="http://msdn.microsoft.com/en-us/library/bb534741" data-raw-source="[Action](http://msdn.microsoft.com/en-us/library/bb534741)">Action</a> to invoke on execution and a <strong>Func</strong> to query for determining if the command can execute.
</div></td>
</tr>
</tbody>
</table>

## Methods

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/delegatecommand-canexecute-method-mspp-commands" data-raw-source="[CanExecute()](/patterns-practices/reference/delegatecommand-canexecute-method-mspp-commands)">CanExecute()</a></td>
<td><div class="summary">
Determines if the command can be executed.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-canexecute-method-mspp-commands" data-raw-source="[CanExecute(Object)](/patterns-practices/reference/delegatecommandbase-canexecute-method-mspp-commands)">CanExecute(Object)</a></td>
<td><div class="summary">
Determines if the command can execute with the provided parameter by invoking the <a href="http://msdn.microsoft.com/en-us/library/bb549151" data-raw-source="[Func&amp;lt;T, TResult&amp;gt;](http://msdn.microsoft.com/en-us/library/bb549151)">Func&lt;T, TResult&gt;</a> supplied during construction.
</div>
(Inherited from <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">DelegateCommandBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47" data-raw-source="[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/execute-mthd" data-raw-source="[Execute()](/patterns-practices/reference/execute-mthd)">Execute()</a></td>
<td><div class="summary">
Executes the command.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-execute-method-mspp-commands" data-raw-source="[Execute(Object)](/patterns-practices/reference/delegatecommandbase-execute-method-mspp-commands)">Execute(Object)</a></td>
<td><div class="summary">
Executes the command with the provided parameter by invoking the <a href="http://msdn.microsoft.com/en-us/library/018hxwa8" data-raw-source="[Action&amp;lt;T&amp;gt;](http://msdn.microsoft.com/en-us/library/018hxwa8)">Action&lt;T&gt;</a> supplied during construction.
</div>
(Inherited from <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">DelegateCommandBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7" data-raw-source="[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/delegatecommand-fromasynchandler-method-func-task-mspp-commands" data-raw-source="[FromAsyncHandler(Func&amp;lt;Task&amp;gt;)](/patterns-practices/reference/delegatecommand-fromasynchandler-method-func-task-mspp-commands)">FromAsyncHandler(Func&lt;Task&gt;)</a></td>
<td><div class="summary">
Factory method to create a new instance of <a href="/patterns-practices/reference/delegatecommand-class-mspp-commands" data-raw-source="[DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)">DelegateCommand</a> from an awaitable handler method.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/delegatecommand-fromasynchandler-method-func-task-func-boolean-mspp-commands" data-raw-source="[FromAsyncHandler(Func&amp;lt;Task&amp;gt;, Func&amp;lt;Boolean&amp;gt;)](/patterns-practices/reference/delegatecommand-fromasynchandler-method-func-task-func-boolean-mspp-commands)">FromAsyncHandler(Func&lt;Task&gt;, Func&lt;Boolean&gt;)</a></td>
<td><div class="summary">
Factory method to create a new instance of <a href="/patterns-practices/reference/delegatecommand-class-mspp-commands" data-raw-source="[DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands)">DelegateCommand</a> from an awaitable handler method.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y" data-raw-source="[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9" data-raw-source="[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65" data-raw-source="[Type](http://msdn.microsoft.com/en-us/library/42892f65)">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a" data-raw-source="[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-oncanexecutechanged-method-mspp-commands" data-raw-source="[OnCanExecuteChanged](/patterns-practices/reference/delegatecommandbase-oncanexecutechanged-method-mspp-commands)">OnCanExecuteChanged</a></td>
<td><div class="summary">
Raises <a href="http://msdn.microsoft.com/en-us/library/ms523106" data-raw-source="[CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106)">CanExecuteChanged</a> on the UI thread so every command invoker can requery <a href="http://msdn.microsoft.com/en-us/library/ms604093" data-raw-source="[CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093)">CanExecute(Object)</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">DelegateCommandBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-onisactivechanged-method-mspp-commands" data-raw-source="[OnIsActiveChanged](/patterns-practices/reference/delegatecommandbase-onisactivechanged-method-mspp-commands)">OnIsActiveChanged</a></td>
<td><div class="summary">
This raises the <a href="/patterns-practices/reference/delegatecommandbase-isactivechanged-event-mspp-commands" data-raw-source="[IsActiveChanged](/patterns-practices/reference/delegatecommandbase-isactivechanged-event-mspp-commands)">IsActiveChanged</a> event.
</div>
(Inherited from <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">DelegateCommandBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-raisecanexecutechanged-method-mspp-commands" data-raw-source="[RaiseCanExecuteChanged](/patterns-practices/reference/delegatecommandbase-raisecanexecutechanged-method-mspp-commands)">RaiseCanExecuteChanged</a></td>
<td><div class="summary">
Raises <a href="/patterns-practices/reference/delegatecommandbase-canexecutechanged-event-mspp-commands" data-raw-source="[CanExecuteChanged](/patterns-practices/reference/delegatecommandbase-canexecutechanged-event-mspp-commands)">CanExecuteChanged</a> on the UI thread so every command invoker can requery to check if the command can execute.
<div>
<h2 id="remarks">Remarks</h2>
Note that this will trigger the execution of <a href="/patterns-practices/reference/delegatecommandbase-canexecute-method-mspp-commands" data-raw-source="[CanExecute(Object)](/patterns-practices/reference/delegatecommandbase-canexecute-method-mspp-commands)">CanExecute(Object)</a> once for each invoker.
</div>
</div>
(Inherited from <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">DelegateCommandBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2" data-raw-source="[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
</tbody>
</table>

## Fields


|   |                                   Name                                   |                                                   Description                                                   |
|---|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|
|   | [\_canExecuteMethod](/patterns-practices/reference/canexecutemthd-field) | (Inherited from [DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands).)  |
|   |    [\_executeMethod](/patterns-practices/reference/executemthd-field)    | (Inherited from  [DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands).) |

## Properties

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-isactive-property-mspp-commands" data-raw-source="[IsActive](/patterns-practices/reference/delegatecommandbase-isactive-property-mspp-commands)">IsActive</a></td>
<td><div class="summary">
Gets or sets a value indicating whether the object is active.
</div>
(Inherited from <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">DelegateCommandBase</a>.)</td>
</tr>
</tbody>
</table>

## Events

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-canexecutechanged-event-mspp-commands" data-raw-source="[CanExecuteChanged](/patterns-practices/reference/delegatecommandbase-canexecutechanged-event-mspp-commands)">CanExecuteChanged</a></td>
<td><div class="summary">
Occurs when changes occur that affect whether or not the command should execute. You must keep a hard reference to the handler to avoid garbage collection and unexpected results. See remarks for more information.
</div>
(Inherited from <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">DelegateCommandBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-isactivechanged-event-mspp-commands" data-raw-source="[IsActiveChanged](/patterns-practices/reference/delegatecommandbase-isactivechanged-event-mspp-commands)">IsActiveChanged</a></td>
<td><div class="summary">
Fired if the <a href="/patterns-practices/reference/delegatecommandbase-isactive-property-mspp-commands" data-raw-source="[IsActive](/patterns-practices/reference/delegatecommandbase-isactive-property-mspp-commands)">IsActive</a> property changes.
</div>
(Inherited from <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">DelegateCommandBase</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[DelegateCommand Class](/patterns-practices/reference/delegatecommand-class-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  