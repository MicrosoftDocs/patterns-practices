---
TOCTitle: 'DelegateCommand(T) Members'
Title: 'DelegateCommand(T) Members (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Commands.DelegateCommand\`1'
ms:mtpsurl: 'delegatecommand-t-members-mspp-commands.md'
---

# DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Members

The [DelegateCommand&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601) type exposes the following members.

## Constructors


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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;)(Action&lt;(Of &lt;(T&gt;)&gt;))](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601.)</td>
<td><div class="summary">
Initializes a new instance of [DelegateCommand&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601).
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;)(Action&lt;(Of &lt;(T&gt;)&gt;), Func&lt;(Of &lt;(T, Boolean&gt;)&gt;))](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601.)</td>
<td><div class="summary">
Initializes a new instance of [DelegateCommand&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601).
</div></td>
</tr>
</tbody>
</table>

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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CanExecute(T)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601.canexecute(%600))</td>
<td><div class="summary">
Determines if the command can execute by invoked the [Func&lt;(Of &lt;(T, TResult&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bb549151) provided during construction.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CanExecute(Object)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.canexecute(system.object))</td>
<td><div class="summary">
Determines if the command can execute with the provided parameter by invoking the [Func&lt;(Of &lt;(T, TResult&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bb549151) supplied during construction.
</div>
(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Execute(T)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601.execute(%600))</td>
<td><div class="summary">
Executes the command and invokes the [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) provided during construction.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Execute(Object)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.execute(system.object))</td>
<td><div class="summary">
Executes the command with the provided parameter by invoking the [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) supplied during construction.
</div>
(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static.gif)</td>
<td>[FromAsyncHandler(Func&lt;(Of &lt;(T, Task&gt;)&gt;))](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601.fromasynchandler(system.func%7b%600%2csystem.threading.tasks.task%7d))</td>
<td><div class="summary">
Factory method to create a new instance of [DelegateCommand&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601) from an awaitable handler method.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static.gif)</td>
<td>[FromAsyncHandler(Func&lt;(Of &lt;(T, Task&gt;)&gt;), Func&lt;(Of &lt;(T, Boolean&gt;)&gt;))](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601.fromasynchandler(system.func%7b%600%2csystem.threading.tasks.task%7d%2csystem.func%7b%600%2csystem.boolean%7d))</td>
<td><div class="summary">
Factory method to create a new instance of [DelegateCommand&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601) from an awaitable handler method.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnCanExecuteChanged](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.oncanexecutechanged)</td>
<td><div class="summary">
Raises [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) on the UI thread so every command invoker can requery [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093).
</div>
(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnIsActiveChanged](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.onisactivechanged)</td>
<td><div class="summary">
This raises the [IsActiveChanged](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.isactivechanged) event.
</div>
(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RaiseCanExecuteChanged](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.raisecanexecutechanged)</td>
<td><div class="summary">
Raises [CanExecuteChanged](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.canexecutechanged) on the UI thread so every command invoker can requery to check if the command can execute.
<div>
<h2 id="remarks">Remarks</h2>
Note that this will trigger the execution of [CanExecute(Object)](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.canexecute(system.object)) once for each invoker.
</div>
</div>
(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
</tbody>
</table>

## Fields


|                                                                                                | Name                                                                                                                        | Description                                                                                                                  |
|------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| ![Protected field](/patterns-practices/reference/images/protfield.gif) | [\_canExecuteMethod](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase._canexecutemethod) | (Inherited from [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase).) |
| ![Protected field](/patterns-practices/reference/images/protfield.gif) | [\_executeMethod](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase._executemethod)       | (Inherited from [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase).) |

## Properties


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
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[IsActive](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.isactive)</td>
<td><div class="summary">
Gets or sets a value indicating whether the object is active.
</div>
(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase).)</td>
</tr>
</tbody>
</table>

## Events


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
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[CanExecuteChanged](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.canexecutechanged)</td>
<td><div class="summary">
Occurs when changes occur that affect whether or not the command should execute. You must keep a hard reference to the handler to avoid garbage collection and unexpected results. See remarks for more information.
</div>
(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase).)</td>
</tr>
<tr class="even">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[IsActiveChanged](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.isactivechanged)</td>
<td><div class="summary">
Fired if the [IsActive](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase.isactive) property changes.
</div>
(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommandbase).)</td>
</tr>
</tbody>
</table>

## See Also
[DelegateCommand&lt;(Of &lt;(T&gt;)&gt;) Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.delegatecommand%601)  
[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)  