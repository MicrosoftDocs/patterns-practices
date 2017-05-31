---
TOCTitle: DelegateCommandBase Methods
Title: 'DelegateCommandBase Methods (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Commands.DelegateCommandBase'
ms:mtpsurl: 'delegatecommandbase-methods-mspp-commands.md'
---

# DelegateCommandBase Methods

The [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase) type exposes the following members.

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
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.canexecute(system.object)">CanExecute</a></td>
<td><div class="summary">
Determines if the command can execute with the provided parameter by invoking the <a href="http://msdn.microsoft.com/en-us/library/bb549151">Func&lt;(Of &lt;(T, TResult&gt;)&gt;)</a> supplied during construction.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.execute(system.object)">Execute</a></td>
<td><div class="summary">
Executes the command with the provided parameter by invoking the <a href="http://msdn.microsoft.com/en-us/library/018hxwa8">Action&lt;(Of &lt;(T&gt;)&gt;)</a> supplied during construction.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.oncanexecutechanged">OnCanExecuteChanged</a></td>
<td><div class="summary">
Raises <a href="http://msdn.microsoft.com/en-us/library/ms523106">CanExecuteChanged</a> on the UI thread so every command invoker can requery <a href="http://msdn.microsoft.com/en-us/library/ms604093">CanExecute(Object)</a>.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.onisactivechanged">OnIsActiveChanged</a></td>
<td><div class="summary">
This raises the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.isactivechanged">IsActiveChanged</a> event.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.raisecanexecutechanged">RaiseCanExecuteChanged</a></td>
<td><div class="summary">
Raises <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.canexecutechanged">CanExecuteChanged</a> on the UI thread so every command invoker can requery to check if the command can execute.
<div>
<h2 id="remarks">Remarks</h2>
Note that this will trigger the execution of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.canexecute(system.object)">CanExecute(Object)</a> once for each invoker.
</div>
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

## See Also
[DelegateCommandBase Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
