---
TOCTitle: InteractionRequestTrigger Methods
Title: 'InteractionRequestTrigger Methods (Microsoft.Practices.Prism.Interactivity.InteractionRequest)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Interactivity.InteractionRequest.InteractionRequestTrigger'
ms:mtpsurl: 'interactionrequesttrigger-methods-mspp-interactivity-interactionrequest.md'
---

# InteractionRequestTrigger Methods

The [InteractionRequestTrigger](/patterns-practices/reference/interactionrequesttrigger-class-mspp-interactivity-interactionrequest) type exposes the following members.

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
<td>[ApplyAnimationClock(DependencyProperty, AnimationClock)](http://msdn.microsoft.com/en-us/library/ms590752)</td>
<td><div class="summary">
Applies an [AnimationClock](http://msdn.microsoft.com/en-us/library/ms618394) to the specified [DependencyProperty](http://msdn.microsoft.com/en-us/library/ms589318). If the property is already animated, the [SnapshotAndReplace](http://msdn.microsoft.com/en-us/library/ms596029) handoff behavior is used.
</div>
(Inherited from [Animatable](http://msdn.microsoft.com/en-us/library/ms618388).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ApplyAnimationClock(DependencyProperty, AnimationClock, HandoffBehavior)](http://msdn.microsoft.com/en-us/library/ms590755)</td>
<td><div class="summary">
Applies an [AnimationClock](http://msdn.microsoft.com/en-us/library/ms618394) to the specified [DependencyProperty](http://msdn.microsoft.com/en-us/library/ms589318). If the property is already animated, the specified [HandoffBehavior](http://msdn.microsoft.com/en-us/library/ms596029) is used.
</div>
(Inherited from [Animatable](http://msdn.microsoft.com/en-us/library/ms618388).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>Attach</td>
<td>(Inherited from TriggerBase.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[BeginAnimation(DependencyProperty, AnimationTimeline)](http://msdn.microsoft.com/en-us/library/ms590761)</td>
<td><div class="summary">
Applies an animation to the specified [DependencyProperty](http://msdn.microsoft.com/en-us/library/ms589318). The animation is started when the next frame is rendered. If the specified property is already animated, the [SnapshotAndReplace](http://msdn.microsoft.com/en-us/library/ms596029) handoff behavior is used.
</div>
(Inherited from [Animatable](http://msdn.microsoft.com/en-us/library/ms618388).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[BeginAnimation(DependencyProperty, AnimationTimeline, HandoffBehavior)](http://msdn.microsoft.com/en-us/library/ms590757)</td>
<td><div class="summary">
Applies an animation to the specified [DependencyProperty](http://msdn.microsoft.com/en-us/library/ms589318). The animation is started when the next frame is rendered. If the specified property is already animated, the specified [HandoffBehavior](http://msdn.microsoft.com/en-us/library/ms596029) is used.
</div>
(Inherited from [Animatable](http://msdn.microsoft.com/en-us/library/ms618388).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CheckAccess](http://msdn.microsoft.com/en-us/library/ms591167)</td>
<td><div class="summary">
Determines whether the calling thread has access to this [DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925).
</div>
(Inherited from [DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ClearValue(DependencyProperty)](http://msdn.microsoft.com/en-us/library/ms597464)</td>
<td><div class="summary">
Clears the local value of a property. The property to be cleared is specified by a [DependencyProperty](http://msdn.microsoft.com/en-us/library/ms589318) identifier.
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ClearValue(DependencyPropertyKey)](http://msdn.microsoft.com/en-us/library/ms597465)</td>
<td><div class="summary">
Clears the local value of a read-only property. The property to be cleared is specified by a [DependencyPropertyKey](http://msdn.microsoft.com/en-us/library/ms602348).
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Clone](http://msdn.microsoft.com/en-us/library/ms590765)</td>
<td><div class="summary">
Creates a modifiable clone of this [Animatable](http://msdn.microsoft.com/en-us/library/ms618388), making deep copies of this object's values. When copying this object's dependency properties, this method copies resource references and data bindings (but they might no longer resolve) but not animations or their current values.
</div>
(Inherited from [Animatable](http://msdn.microsoft.com/en-us/library/ms618388).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CloneCore](http://msdn.microsoft.com/en-us/library/ms557724)</td>
<td><div class="summary">
Makes the instance a clone (deep copy) of the specified [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) using base (non-animated) property values.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CloneCurrentValue](http://msdn.microsoft.com/en-us/library/ms557727)</td>
<td><div class="summary">
Creates a modifiable clone (deep copy) of the [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) using its current values.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CloneCurrentValueCore](http://msdn.microsoft.com/en-us/library/ms557729)</td>
<td><div class="summary">
Makes the instance a modifiable clone (deep copy) of the specified [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) using current property values.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CoerceValue](http://msdn.microsoft.com/en-us/library/ms597466)</td>
<td><div class="summary">
Coerces the value of the specified dependency property. This is accomplished by invoking any [CoerceValueCallback](http://msdn.microsoft.com/en-us/library/ms589135) function specified in property metadata for the dependency property as it exists on the calling [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateInstance](http://msdn.microsoft.com/en-us/library/ms557732)</td>
<td><div class="summary">
Initializes a new instance of the [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) class.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>CreateInstanceCore</td>
<td>(Inherited from TriggerBase.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>Detach</td>
<td>(Inherited from TriggerBase.)</td>
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
<td>[Freeze](http://msdn.microsoft.com/en-us/library/ms557735)</td>
<td><div class="summary">
Makes the current object unmodifiable and sets its [IsFrozen](http://msdn.microsoft.com/en-us/library/ms600924) property to true.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[FreezeCore](http://msdn.microsoft.com/en-us/library/ms590769)</td>
<td><div class="summary">
Makes this [Animatable](http://msdn.microsoft.com/en-us/library/ms618388) object unmodifiable or determines whether it can be made unmodifiable.
</div>
(Inherited from [Animatable](http://msdn.microsoft.com/en-us/library/ms618388).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetAnimationBaseValue](http://msdn.microsoft.com/en-us/library/ms590770)</td>
<td><div class="summary">
Returns the non-animated value of the specified [DependencyProperty](http://msdn.microsoft.com/en-us/library/ms589318).
</div>
(Inherited from [Animatable](http://msdn.microsoft.com/en-us/library/ms618388).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetAsFrozen](http://msdn.microsoft.com/en-us/library/ms557740)</td>
<td><div class="summary">
Creates a frozen copy of the [Freezable](http://msdn.microsoft.com/en-us/library/ms602734), using base (non-animated) property values. Because the copy is frozen, any frozen sub-objects are copied by reference.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[GetAsFrozenCore](http://msdn.microsoft.com/en-us/library/ms557742)</td>
<td><div class="summary">
Makes the instance a frozen clone of the specified [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) using base (non-animated) property values.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetCurrentValueAsFrozen](http://msdn.microsoft.com/en-us/library/ms557743)</td>
<td><div class="summary">
Creates a frozen copy of the [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) using current property values. Because the copy is frozen, any frozen sub-objects are copied by reference.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[GetCurrentValueAsFrozenCore](http://msdn.microsoft.com/en-us/library/ms557745)</td>
<td><div class="summary">
Makes the current instance a frozen clone of the specified [Freezable](http://msdn.microsoft.com/en-us/library/ms602734). If the object has animated dependency properties, their current animated values are copied.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[GetEventName](/patterns-practices/reference/interactionrequesttrigger-geteventname-method-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Specifies the name of the Event this EventTriggerBase is listening for.
</div>
(Overrides EventTriggerGetEventName()()().)</td>
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
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>InvokeActions</td>
<td>(Inherited from TriggerBase.)</td>
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
<td>[OnAttached](/patterns-practices/reference/interactionrequesttrigger-onattached-method-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Called after the trigger is attached to an AssociatedObject.
</div>
(Overrides EventTriggerBaseOnAttached()()().)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnChanged](http://msdn.microsoft.com/en-us/library/ms557749)</td>
<td><div class="summary">
Called when the current [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) object is modified.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnDetaching](/patterns-practices/reference/interactionrequesttrigger-ondetaching-method-mspp-interactivity-interactionrequest)</td>
<td><div class="summary">
Called when the trigger is being dettached from its AssociatedObject, but before it has actually occurred.
</div>
(Overrides EventTriggerBaseOnDetaching()()().)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>OnEvent</td>
<td>(Inherited from EventTriggerBase.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnFreezablePropertyChanged(DependencyObject, DependencyObject)](http://msdn.microsoft.com/en-us/library/aa345824)</td>
<td><div class="summary">
Ensures that appropriate context pointers are established for a [DependencyObjectType](http://msdn.microsoft.com/en-us/library/ms589310) data member that has just been set.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnFreezablePropertyChanged(DependencyObject, DependencyObject, DependencyProperty)](http://msdn.microsoft.com/en-us/library/aa345825)</td>
<td><div class="summary">
This member supports the Windows Presentation Foundation (WPF) infrastructure and is not intended to be used directly from your code.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPropertyChanged](http://msdn.microsoft.com/en-us/library/ms557754)</td>
<td><div class="summary">
Overrides the [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) implementation of [OnPropertyChanged(DependencyPropertyChangedEventArgs)](http://msdn.microsoft.com/en-us/library/ms597471) to also invoke any [Changed](http://msdn.microsoft.com/en-us/library/ms596566) handlers in response to a changing dependency property of type [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>OnSourceChanged</td>
<td>(Inherited from EventTriggerBase[&lt;Object&gt;](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ReadLocalValue](http://msdn.microsoft.com/en-us/library/ms597472)</td>
<td><div class="summary">
Returns the local value of a dependency property, if it exists.
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ReadPreamble](http://msdn.microsoft.com/en-us/library/ms557756)</td>
<td><div class="summary">
Ensures that the [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) is being accessed from a valid thread. Inheritors of [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) must call this method at the beginning of any API that reads data members that are not dependency properties.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
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
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[WritePostscript](http://msdn.microsoft.com/en-us/library/ms557762)</td>
<td><div class="summary">
Raises the [Changed](http://msdn.microsoft.com/en-us/library/ms596566) event for the [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) and invokes its [OnChanged()()()](http://msdn.microsoft.com/en-us/library/ms557749) method. Classes that derive from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) should call this method at the end of any API that modifies class members that are not stored as dependency properties.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[WritePreamble](http://msdn.microsoft.com/en-us/library/ms557763)</td>
<td><div class="summary">
Verifies that the [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) is not frozen and that it is being accessed from a valid threading context. [Freezable](http://msdn.microsoft.com/en-us/library/ms602734) inheritors should call this method at the beginning of any API that writes to data members that are not dependency properties.
</div>
(Inherited from [Freezable](http://msdn.microsoft.com/en-us/library/ms602734).)</td>
</tr>
</tbody>
</table>

## See Also

[InteractionRequestTrigger Class](/patterns-practices/reference/interactionrequesttrigger-class-mspp-interactivity-interactionrequest)  
[Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace](/patterns-practices/reference/mspp-interactivity-interactionrequest-namespace)