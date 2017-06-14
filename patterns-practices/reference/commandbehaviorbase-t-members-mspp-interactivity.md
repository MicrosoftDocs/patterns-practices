---
TOCTitle: 'CommandBehaviorBase(T) Members'
Title: 'CommandBehaviorBase(T) Members (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Interactivity.CommandBehaviorBase\`1'
ms:mtpsurl: 'commandbehaviorbase-t-members-mspp-interactivity.md'
---

# CommandBehaviorBase&lt;T&gt; Members

The [CommandBehaviorBase&lt;T&gt;](/patterns-practices/reference/commandbehaviorbase-t-class-mspp-interactivity) type exposes the following members.

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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>CommandBehaviorBase&lt;T&gt;</td>
<td><div class="summary">
Constructor specifying the target object.
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ExecuteCommand](/patterns-practices/reference/commandbehaviorbase-t-executecommand-method-mspp-interactivity
)</td>
<td><div class="summary">
Executes the command, if it's set, providing the [CommandParameter](/patterns-practices/reference/commandbehaviorbase-t-commandparameter-property-mspp-interactivity
)
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
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
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[UpdateEnabledState](/patterns-practices/reference/commandbehaviorbase-t-updateenabledstate-method-mspp-interactivity
)</td>
<td><div class="summary">
Updates the target object's IsEnabled property based on the commands ability to execute.
</div></td>
</tr>
</tbody>
</table>

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
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Command](/patterns-practices/reference/commandbehaviorbase-t-command-property-mspp-interactivity
)</td>
<td><div class="summary">
Corresponding command to be execute and monitored for [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106)
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[CommandParameter](/patterns-practices/reference/commandbehaviorbase-t-commandparameter-property-mspp-interactivity
)</td>
<td><div class="summary">
The parameter to supply the command during execution
</div></td>
</tr>
<tr class="odd">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[TargetObject](/patterns-practices/reference/commandbehaviorbase-t-targetobject-property-mspp-interactivity
)</td>
<td><div class="summary">
Object to which this behavior is attached.
</div></td>
</tr>
</tbody>
</table>

## See Also

[CommandBehaviorBase&lt;T&gt; Class](/patterns-practices/reference/commandbehaviorbase-t-class-mspp-interactivity)<br/>
[Microsoft.Practices.Prism.Interactivity Namespace](/patterns-practices/reference/mspp-interactivity-namespace)<br/>