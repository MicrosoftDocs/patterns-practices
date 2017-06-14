---
TOCTitle: ItemMetadata Methods
Title: 'ItemMetadata Methods (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.ItemMetadata'
ms:mtpsurl: 'itemmetadata-methods-mspp-regions.md'
---

# ItemMetadata Methods

The [ItemMetadata](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.itemmetadata) type exposes the following members.

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
<td>[CheckAccess](http://msdn.microsoft.com/en-us/library/ms591167)</td>
<td><div class="summary">
Determines whether the calling thread has access to this [DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925).
</div>
(Inherited from [DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ClearValue(DependencyProperty)](http://msdn.microsoft.com/en-us/library/ms597464)</td>
<td><div class="summary">
Clears the local value of a property. The property to be cleared is specified by a [DependencyProperty](http://msdn.microsoft.com/en-us/library/ms589318) identifier.
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ClearValue(DependencyPropertyKey)](http://msdn.microsoft.com/en-us/library/ms597465)</td>
<td><div class="summary">
Clears the local value of a read-only property. The property to be cleared is specified by a [DependencyPropertyKey](http://msdn.microsoft.com/en-us/library/ms602348).
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CoerceValue](http://msdn.microsoft.com/en-us/library/ms597466)</td>
<td><div class="summary">
Coerces the value of the specified dependency property. This is accomplished by invoking any [CoerceValueCallback](http://msdn.microsoft.com/en-us/library/ms589135) function specified in property metadata for the dependency property as it exists on the calling [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/aa345743)</td>
<td><div class="summary">
Determines whether a provided [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) is equivalent to the current [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
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
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/aa345744)</td>
<td><div class="summary">
Gets a hash code for this [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetLocalValueEnumerator](http://msdn.microsoft.com/en-us/library/ms597467)</td>
<td><div class="summary">
Creates a specialized enumerator for determining which dependency properties have locally set values on this [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetValue](http://msdn.microsoft.com/en-us/library/ms597469)</td>
<td><div class="summary">
Returns the current effective value of a dependency property on this instance of a [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[InvalidateProperty](http://msdn.microsoft.com/en-us/library/ms597470)</td>
<td><div class="summary">
Re-evaluates the effective value for the specified dependency property
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[InvokeMetadataChanged](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.itemmetadata.invokemetadatachanged)</td>
<td><div class="summary">
Explicitly invokes [MetadataChanged](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.itemmetadata.metadatachanged) to notify listeners.
</div></td>
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
<td>[OnPropertyChanged](http://msdn.microsoft.com/en-us/library/ms597471)</td>
<td><div class="summary">
Invoked whenever the effective value of any dependency property on this [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) has been updated. The specific dependency property that changed is reported in the event data.
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ReadLocalValue](http://msdn.microsoft.com/en-us/library/ms597472)</td>
<td><div class="summary">
Returns the local value of a dependency property, if it exists.
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[SetCurrentValue](http://msdn.microsoft.com/en-us/library/dd549644)</td>
<td><div class="summary">
Sets the value of a dependency property without changing its value source.
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[SetValue(DependencyProperty, Object)](http://msdn.microsoft.com/en-us/library/ms597473)</td>
<td><div class="summary">
Sets the local value of a dependency property, specified by its dependency property identifier.
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[SetValue(DependencyPropertyKey, Object)](http://msdn.microsoft.com/en-us/library/ms597474)</td>
<td><div class="summary">
Sets the local value of a read-only dependency property, specified by the [DependencyPropertyKey](http://msdn.microsoft.com/en-us/library/ms602348) identifier of the dependency property.
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ShouldSerializeProperty](http://msdn.microsoft.com/en-us/library/ms597475)</td>
<td><div class="summary">
Returns a value that indicates whether serialization processes should serialize the value for the provided dependency property.
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[VerifyAccess](http://msdn.microsoft.com/en-us/library/ms591169)</td>
<td><div class="summary">
Enforces that the calling thread has access to this [DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925).
</div>
(Inherited from [DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925).)</td>
</tr>
</tbody>
</table>

## See Also

[ItemMetadata Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.itemmetadata)  
[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)