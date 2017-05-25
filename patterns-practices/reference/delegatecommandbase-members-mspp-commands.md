---
TOCTitle: DelegateCommandBase Members
Title: 'DelegateCommandBase Members (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Commands.DelegateCommandBase'
ms:mtpsurl: 'delegatecommandbase-members-mspp-commands.md'
---

Prism Class Library

DelegateCommandBase Members
===========================

The [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430762.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.">DelegateCommandBase(Action&lt;(Of &lt;(Object&gt;)&gt;), Func&lt;(Of &lt;(Object, Boolean&gt;)&gt;))</a></td>
<td><div class="summary">
Creates a new instance of a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase">DelegateCommandBase</a>, specifying both the execute action and the can execute function.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430762.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.">DelegateCommandBase(Func&lt;(Of &lt;(Object, Task&gt;)&gt;), Func&lt;(Of &lt;(Object, Boolean&gt;)&gt;))</a></td>
<td><div class="summary">
Creates a new instance of a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase">DelegateCommandBase</a>, specifying both the Execute action as an awaitable Task and the CanExecute function.
</div></td>
</tr>
</tbody>
</table>

Methods
-------

<span id="methodTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430762.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.canexecute(system.object)">CanExecute</a></td>
<td><div class="summary">
Determines if the command can execute with the provided parameter by invoking the <a href="http://msdn.microsoft.com/en-us/library/bb549151">Func&lt;(Of &lt;(T, TResult&gt;)&gt;)</a> supplied during construction.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430762.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.execute(system.object)">Execute</a></td>
<td><div class="summary">
Executes the command with the provided parameter by invoking the <a href="http://msdn.microsoft.com/en-us/library/018hxwa8">Action&lt;(Of &lt;(T&gt;)&gt;)</a> supplied during construction.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430762.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430762.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430762.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.oncanexecutechanged">OnCanExecuteChanged</a></td>
<td><div class="summary">
Raises <a href="http://msdn.microsoft.com/en-us/library/ms523106">CanExecuteChanged</a> on the UI thread so every command invoker can requery <a href="http://msdn.microsoft.com/en-us/library/ms604093">CanExecute(Object)</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430762.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.onisactivechanged">OnIsActiveChanged</a></td>
<td><div class="summary">
This raises the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.isactivechanged">IsActiveChanged</a> event.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
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
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

Fields
------

<span id="fieldTableToggle"></span>
|                                                                                                | Name                                                                                                                        | Description |
|------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|-------------|
| ![](https://msdn.microsoft.com/en-us/Gg430762.protfield(en-us,PandP.50).gif "Protected field") | [\_canExecuteMethod](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase._canexecutemethod) |             |
| ![](https://msdn.microsoft.com/en-us/Gg430762.protfield(en-us,PandP.50).gif "Protected field") | [\_executeMethod](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase._executemethod)       |             |

Properties
----------

<span id="propertyTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430762.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.isactive">IsActive</a></td>
<td><div class="summary">
Gets or sets a value indicating whether the object is active.
</div></td>
</tr>
</tbody>
</table>

Events
------

<span id="eventTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430762.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.canexecutechanged">CanExecuteChanged</a></td>
<td><div class="summary">
Occurs when changes occur that affect whether or not the command should execute. You must keep a hard reference to the handler to avoid garbage collection and unexpected results. See remarks for more information.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430762.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.isactivechanged">IsActiveChanged</a></td>
<td><div class="summary">
Fired if the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.isactive">IsActive</a> property changes.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[DelegateCommandBase Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
