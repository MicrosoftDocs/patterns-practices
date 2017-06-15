---
TOCTitle: DelegateCommand Methods
Title: 'DelegateCommand Methods (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Commands.DelegateCommand'
ms:mtpsurl: 'delegatecommand-methods-mspp-commands.md'
---


# DelegateCommand Methods

The [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands) type exposes the following members.

## Methods


<table>
<colsgroup>
<col width="80">
<col>
<col>
</colsgroup>
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
<td>[CanExecute()](/patterns-practices/reference/delegatecommand-canexecute-method-mspp-commands)</td>
<td><div class="summary">
Determines if the command can be executed.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CanExecute(Object)](/patterns-practices/reference/delegatecommandbase-canexecute-method-mspp-commands)</td>
<td><div class="summary">
Determines if the command can execute with the provided parameter by invoking the [Func&lt;T, TResult&gt;](http://msdn.microsoft.com/en-us/library/bb549151) supplied during construction.
</div>
(Inherited from [DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands).)</td>
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
<td>[Execute()](/patterns-practices/reference/delegatecommand-execute-method-mspp-commands)</td>
<td><div class="summary">
Executes the command.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Execute(Object)](/patterns-practices/reference/delegatecommandbase-execute-method-mspp-commands)</td>
<td><div class="summary">
Executes the command with the provided parameter by invoking the [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) supplied during construction.
</div>
(Inherited from [DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands).)</td>
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[FromAsyncHandler(Func&lt;Task&gt;)](/patterns-practices/reference/delegatecommand-fromasynchandler-method-func-task-mspp-commands)</td>
<td><div class="summary">
Factory method to create a new instance of [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands) from an awaitable handler method.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[FromAsyncHandler(Func&lt;Task&gt;, Func&lt;Boolean&gt;)](/patterns-practices/reference/delegatecommand-fromasynchandler-method-func-task-func-boolean-mspp-commands)</td>
<td><div class="summary">
Factory method to create a new instance of [DelegateCommand](/patterns-practices/reference/delegatecommand-class-mspp-commands) from an awaitable handler method.
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
<td>[OnCanExecuteChanged](/patterns-practices/reference/delegatecommandbase-oncanexecutechanged-method-mspp-commands)</td>
<td><div class="summary">
Raises [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) on the UI thread so every command invoker can requery [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093).
</div>
(Inherited from [DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnIsActiveChanged](/patterns-practices/reference/delegatecommandbase-onisactivechanged-method-mspp-commands)</td>
<td><div class="summary">
This raises the [IsActiveChanged](/patterns-practices/reference/delegatecommandbase-isactivechanged-event-mspp-commands) event.
</div>
(Inherited from [DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RaiseCanExecuteChanged](/patterns-practices/reference/delegatecommandbase-raisecanexecutechanged-method-mspp-commands)</td>
<td><div class="summary">
Raises [CanExecuteChanged](/patterns-practices/reference/delegatecommandbase-canexecutechanged-event-mspp-commands) on the UI thread so every command invoker can requery to check if the command can execute.
<div>

<h3>Remarks</h3>

Note that this will trigger the execution of [CanExecute(Object)](/patterns-practices/reference/delegatecommandbase-canexecute-method-mspp-commands) once for each invoker.
</div>
</div>
(Inherited from [DelegateCommandBase](/patterns-practices/reference/delegatecommandbase-class-mspp-commands).)</td>
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

## See Also

[DelegateCommand Class](/patterns-practices/reference/delegatecommand-class-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)
