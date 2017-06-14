---
TOCTitle: CompositeCommand Methods
Title: 'CompositeCommand Methods (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Commands.CompositeCommand'
ms:mtpsurl: 'compositecommand-methods-mspp-commands.md'
---


# CompositeCommand Methods

The [CompositeCommand](/patterns-practices/reference/compositecommand-class-mspp-commands) type exposes the following members.

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
<td>[CanExecute](/patterns-practices/reference/compositecommand-canexecute-method-mspp-commands)</td>
<td><div class="summary">
Forwards [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) to the registered commands and returns <strong>truetrue</strong> (<strong>True</strong> in Visual Basic) if all of the commands return <strong>truetrue</strong> (<strong>True</strong> in Visual Basic).
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Execute](/patterns-practices/reference/compositecommand-execute-method-mspp-commands)</td>
<td><div class="summary">
Forwards [Execute(Object)](http://msdn.microsoft.com/en-us/library/ms604094) to the registered commands.
</div></td>
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
<td>[OnCanExecuteChanged](/patterns-practices/reference/compositecommand-oncanexecutechanged-method-mspp-commands)</td>
<td><div class="summary">
Raises [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) on the UI thread so every command invoker can requery [CanExecute(Object)](http://msdn.microsoft.com/en-us/library/ms604093) to check if the [CompositeCommand](/patterns-practices/reference/compositecommand-class-mspp-commands) can execute.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RegisterCommand](/patterns-practices/reference/compositecommand-registercommand-method-mspp-commands)</td>
<td><div class="summary">
Adds a command to the collection and signs up for the [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) event of it.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ShouldExecute](/patterns-practices/reference/compositecommand-shouldexecute-method-mspp-commands)</td>
<td><div class="summary">
Evaluates if a command should execute.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[UnregisterCommand](/patterns-practices/reference/compositecommand-unregistercommand-method-mspp-commands)</td>
<td><div class="summary">
Removes a command from the collection and removes itself from the [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) event of it.
</div></td>
</tr>
</tbody>
</table>

## See Also

[CompositeCommand Class](/patterns-practices/reference/compositecommand-class-mspp-commands)<br/>
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)