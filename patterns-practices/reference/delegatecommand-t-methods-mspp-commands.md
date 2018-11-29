---
TOCTitle: 'DelegateCommand(T) Methods'
Title: 'DelegateCommand(T) Methods (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Commands.DelegateCommand\`1'
ms:mtpsurl: 'delegatecommand-t-methods-mspp-commands.md'
---

# DelegateCommand&lt;T&gt; Methods

The [DelegateCommand&lt;T&gt;](/patterns-practices/reference/delegatecommand-t-class-mspp-commands) type exposes the following members.

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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/delegatecommand-t-canexecute-method-t-mspp-commands" data-raw-source="[CanExecute(T)](/patterns-practices/reference/delegatecommand-t-canexecute-method-t-mspp-commands)">CanExecute(T)</a></td>
<td><div class="summary">
Determines if the command can execute by invoked the <a href="http://msdn.microsoft.com/en-us/library/bb549151" data-raw-source="[Func&amp;lt;T, TResult&amp;gt;](http://msdn.microsoft.com/en-us/library/bb549151)">Func&lt;T, TResult&gt;</a> provided during construction.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[CanExecute(Object)](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">CanExecute(Object)</a></td>
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
<td><a href="/patterns-practices/reference/delegatecommand-t-execute-method-t-mspp-commands" data-raw-source="[Execute(T)](/patterns-practices/reference/delegatecommand-t-execute-method-t-mspp-commands)">Execute(T)</a></td>
<td><div class="summary">
Executes the command and invokes the <a href="http://msdn.microsoft.com/en-us/library/018hxwa8" data-raw-source="[Action&amp;lt;T&amp;gt;](http://msdn.microsoft.com/en-us/library/018hxwa8)">Action&lt;T&gt;</a> provided during construction.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[Execute(Object)](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">Execute(Object)</a></td>
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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="static-member"/></td>
<td><a href="/patterns-practices/reference/delegatecommand-t-fromasynchandler-method-func-t-task-mspp-commands" data-raw-source="[FromAsyncHandler(Func&amp;lt;T, Task&amp;gt;)](/patterns-practices/reference/delegatecommand-t-fromasynchandler-method-func-t-task-mspp-commands)">FromAsyncHandler(Func&lt;T, Task&gt;)</a></td>
<td><div class="summary">
Factory method to create a new instance of <a href="/patterns-practices/reference/delegatecommand-t-class-mspp-commands" data-raw-source="[DelegateCommand&amp;lt;T&amp;gt;](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)">DelegateCommand&lt;T&gt;</a> from an awaitable handler method.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="static-member"/></td>
<td><a href="/patterns-practices/reference/delegatecommand-t-fromasynchandler-method-func-t-task-func-t-boolean-mspp-commands" data-raw-source="[FromAsyncHandler(Func&amp;lt;T, Task&amp;gt;, Func&amp;lt;T, Boolean&amp;gt;)](/patterns-practices/reference/delegatecommand-t-fromasynchandler-method-func-t-task-func-t-boolean-mspp-commands)">FromAsyncHandler(Func&lt;T, Task&gt;, Func&lt;T, Boolean&gt;)</a></td>
<td><div class="summary">
Factory method to create a new instance of <a href="/patterns-practices/reference/delegatecommand-t-class-mspp-commands" data-raw-source="[DelegateCommand&amp;lt;T&amp;gt;](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)">DelegateCommand&lt;T&gt;</a> from an awaitable handler method.
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
<td><a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands.oncanexecutechanged" data-raw-source="[OnCanExecuteChanged](/patterns-practices/reference/delegatecommandbase-class-mspp-commands.oncanexecutechanged)">OnCanExecuteChanged</a></td>
<td><div class="summary">
Raises <a href="http://msdn.microsoft.com/en-us/library/ms523106" data-raw-source="[CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106)">CanExecuteChanged</a> on the UI thread so every command invoker can requery <a href="http://msdn.microsoft.com/en-us/library/ms604093" data-raw-source="[CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093)">CanExecute(Object)</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">DelegateCommandBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands.onisactivechanged" data-raw-source="[OnIsActiveChanged](/patterns-practices/reference/delegatecommandbase-class-mspp-commands.onisactivechanged)">OnIsActiveChanged</a></td>
<td><div class="summary">
This raises the <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands.isactivechanged" data-raw-source="[IsActiveChanged](/patterns-practices/reference/delegatecommandbase-class-mspp-commands.isactivechanged)">IsActiveChanged</a> event.
</div>
(Inherited from <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">DelegateCommandBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands.raisecanexecutechanged" data-raw-source="[RaiseCanExecuteChanged](/patterns-practices/reference/delegatecommandbase-class-mspp-commands.raisecanexecutechanged)">RaiseCanExecuteChanged</a></td>
<td><div class="summary">
Raises <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands.canexecutechanged" data-raw-source="[CanExecuteChanged](/patterns-practices/reference/delegatecommandbase-class-mspp-commands.canexecutechanged)">CanExecuteChanged</a> on the UI thread so every command invoker can requery to check if the command can execute.
<div>
<h3 id="remarks">Remarks</h3>
Note that this will trigger the execution of <a href="/patterns-practices/reference/delegatecommandbase-class-mspp-commands" data-raw-source="[CanExecute(Object)](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)">CanExecute(Object)</a> once for each invoker.
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

## See Also

[DelegateCommand&lt;T&gt; Class](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  