---
TOCTitle: PopupWindowAction Methods
Title: 'PopupWindowAction Methods (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Interactivity.PopupWindowAction'
ms:mtpsurl: 'popupwindowaction-methods-mspp-interactivity.md'
---

# PopupWindowAction Methods

The [PopupWindowAction](https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.popupwindowaction) type exposes the following members.

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
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms590752">ApplyAnimationClock(DependencyProperty, AnimationClock)</a></td>
<td><div class="summary">
Applies an <a href="http://msdn.microsoft.com/en-us/library/ms618394">AnimationClock</a> to the specified <a href="http://msdn.microsoft.com/en-us/library/ms589318">DependencyProperty</a>. If the property is already animated, the <a href="http://msdn.microsoft.com/en-us/library/ms596029">SnapshotAndReplace</a> handoff behavior is used.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms618388">Animatable</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms590755">ApplyAnimationClock(DependencyProperty, AnimationClock, HandoffBehavior)</a></td>
<td><div class="summary">
Applies an <a href="http://msdn.microsoft.com/en-us/library/ms618394">AnimationClock</a> to the specified <a href="http://msdn.microsoft.com/en-us/library/ms589318">DependencyProperty</a>. If the property is already animated, the specified <a href="http://msdn.microsoft.com/en-us/library/ms596029">HandoffBehavior</a> is used.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms618388">Animatable</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td>Attach</td>
<td>(Inherited from TriggerAction.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms590761">BeginAnimation(DependencyProperty, AnimationTimeline)</a></td>
<td><div class="summary">
Applies an animation to the specified <a href="http://msdn.microsoft.com/en-us/library/ms589318">DependencyProperty</a>. The animation is started when the next frame is rendered. If the specified property is already animated, the <a href="http://msdn.microsoft.com/en-us/library/ms596029">SnapshotAndReplace</a> handoff behavior is used.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms618388">Animatable</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms590757">BeginAnimation(DependencyProperty, AnimationTimeline, HandoffBehavior)</a></td>
<td><div class="summary">
Applies an animation to the specified <a href="http://msdn.microsoft.com/en-us/library/ms589318">DependencyProperty</a>. The animation is started when the next frame is rendered. If the specified property is already animated, the specified <a href="http://msdn.microsoft.com/en-us/library/ms596029">HandoffBehavior</a> is used.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms618388">Animatable</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms591167">CheckAccess</a></td>
<td><div class="summary">
Determines whether the calling thread has access to this <a href="http://msdn.microsoft.com/en-us/library/ms615925">DispatcherObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms615925">DispatcherObject</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597464">ClearValue(DependencyProperty)</a></td>
<td><div class="summary">
Clears the local value of a property. The property to be cleared is specified by a <a href="http://msdn.microsoft.com/en-us/library/ms589318">DependencyProperty</a> identifier.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597465">ClearValue(DependencyPropertyKey)</a></td>
<td><div class="summary">
Clears the local value of a read-only property. The property to be cleared is specified by a <a href="http://msdn.microsoft.com/en-us/library/ms602348">DependencyPropertyKey</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms590765">Clone</a></td>
<td><div class="summary">
Creates a modifiable clone of this <a href="http://msdn.microsoft.com/en-us/library/ms618388">Animatable</a>, making deep copies of this object's values. When copying this object's dependency properties, this method copies resource references and data bindings (but they might no longer resolve) but not animations or their current values.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms618388">Animatable</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557724">CloneCore</a></td>
<td><div class="summary">
Makes the instance a clone (deep copy) of the specified <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> using base (non-animated) property values.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557727">CloneCurrentValue</a></td>
<td><div class="summary">
Creates a modifiable clone (deep copy) of the <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> using its current values.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557729">CloneCurrentValueCore</a></td>
<td><div class="summary">
Makes the instance a modifiable clone (deep copy) of the specified <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> using current property values.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597466">CoerceValue</a></td>
<td><div class="summary">
Coerces the value of the specified dependency property. This is accomplished by invoking any <a href="http://msdn.microsoft.com/en-us/library/ms589135">CoerceValueCallback</a> function specified in property metadata for the dependency property as it exists on the calling <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.popupwindowaction.createdefaultwindow(microsoft.practices.prism.interactivity.interactionrequest.inotification)">CreateDefaultWindow</a></td>
<td><div class="summary">
When no WindowContent is sent this method is used to create a default basic window to show the corresponding <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.interactionrequest.inotification">INotification</a> or <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.interactionrequest.iconfirmation">IConfirmation</a>.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557732">CreateInstance</a></td>
<td><div class="summary">
Initializes a new instance of the <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> class.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td>CreateInstanceCore</td>
<td>(Inherited from TriggerAction.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td>Detach</td>
<td>(Inherited from TriggerAction.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/aa345743">Equals</a></td>
<td><div class="summary">
Determines whether a provided <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a> is equivalent to the current <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557735">Freeze</a></td>
<td><div class="summary">
Makes the current object unmodifiable and sets its <a href="http://msdn.microsoft.com/en-us/library/ms600924">IsFrozen</a> property to true.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms590769">FreezeCore</a></td>
<td><div class="summary">
Makes this <a href="http://msdn.microsoft.com/en-us/library/ms618388">Animatable</a> object unmodifiable or determines whether it can be made unmodifiable.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms618388">Animatable</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms590770">GetAnimationBaseValue</a></td>
<td><div class="summary">
Returns the non-animated value of the specified <a href="http://msdn.microsoft.com/en-us/library/ms589318">DependencyProperty</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms618388">Animatable</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557740">GetAsFrozen</a></td>
<td><div class="summary">
Creates a frozen copy of the <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>, using base (non-animated) property values. Because the copy is frozen, any frozen sub-objects are copied by reference.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557742">GetAsFrozenCore</a></td>
<td><div class="summary">
Makes the instance a frozen clone of the specified <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> using base (non-animated) property values.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557743">GetCurrentValueAsFrozen</a></td>
<td><div class="summary">
Creates a frozen copy of the <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> using current property values. Because the copy is frozen, any frozen sub-objects are copied by reference.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557745">GetCurrentValueAsFrozenCore</a></td>
<td><div class="summary">
Makes the current instance a frozen clone of the specified <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>. If the object has animated dependency properties, their current animated values are copied.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/aa345744">GetHashCode</a></td>
<td><div class="summary">
Gets a hash code for this <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597467">GetLocalValueEnumerator</a></td>
<td><div class="summary">
Creates a specialized enumerator for determining which dependency properties have locally set values on this <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597469">GetValue</a></td>
<td><div class="summary">
Returns the current effective value of a dependency property on this instance of a <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.popupwindowaction.getwindow(microsoft.practices.prism.interactivity.interactionrequest.inotification)">GetWindow</a></td>
<td><div class="summary">
Returns the window to display as part of the trigger action.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597470">InvalidateProperty</a></td>
<td><div class="summary">
Re-evaluates the effective value for the specified dependency property
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.popupwindowaction.invoke(system.object)">Invoke</a></td>
<td><div class="summary">
Displays the child window and collects results for <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequest">IInteractionRequest</a>.
</div>
(Overrides TriggerActionInvoke(Object).)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td>OnAttached</td>
<td>(Inherited from TriggerAction.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557749">OnChanged</a></td>
<td><div class="summary">
Called when the current <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> object is modified.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td>OnDetaching</td>
<td>(Inherited from TriggerAction.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/aa345824">OnFreezablePropertyChanged(DependencyObject, DependencyObject)</a></td>
<td><div class="summary">
Ensures that appropriate context pointers are established for a <a href="http://msdn.microsoft.com/en-us/library/ms589310">DependencyObjectType</a> data member that has just been set.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/aa345825">OnFreezablePropertyChanged(DependencyObject, DependencyObject, DependencyProperty)</a></td>
<td><div class="summary">
This member supports the Windows Presentation Foundation (WPF) infrastructure and is not intended to be used directly from your code.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557754">OnPropertyChanged</a></td>
<td><div class="summary">
Overrides the <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a> implementation of <a href="http://msdn.microsoft.com/en-us/library/ms597471">OnPropertyChanged(DependencyPropertyChangedEventArgs)</a> to also invoke any <a href="http://msdn.microsoft.com/en-us/library/ms596566">Changed</a> handlers in response to a changing dependency property of type <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.popupwindowaction.preparecontentforwindow(microsoft.practices.prism.interactivity.interactionrequest.inotification%2csystem.windows.window)">PrepareContentForWindow</a></td>
<td><div class="summary">
Checks if the WindowContent or its DataContext implements <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.interactionrequest.iinteractionrequestaware">IInteractionRequestAware</a>. If so, it sets the corresponding value. Also, if WindowContent does not have a RegionManager attached, it creates a new scoped RegionManager for it.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597472">ReadLocalValue</a></td>
<td><div class="summary">
Returns the local value of a dependency property, if it exists.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557756">ReadPreamble</a></td>
<td><div class="summary">
Ensures that the <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> is being accessed from a valid thread. Inheritors of <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> must call this method at the beginning of any API that reads data members that are not dependency properties.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd549644">SetCurrentValue</a></td>
<td><div class="summary">
Sets the value of a dependency property without changing its value source.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597473">SetValue(DependencyProperty, Object)</a></td>
<td><div class="summary">
Sets the local value of a dependency property, specified by its dependency property identifier.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597474">SetValue(DependencyPropertyKey, Object)</a></td>
<td><div class="summary">
Sets the local value of a read-only dependency property, specified by the <a href="http://msdn.microsoft.com/en-us/library/ms602348">DependencyPropertyKey</a> identifier of the dependency property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597475">ShouldSerializeProperty</a></td>
<td><div class="summary">
Returns a value that indicates whether serialization processes should serialize the value for the provided dependency property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms591169">VerifyAccess</a></td>
<td><div class="summary">
Enforces that the calling thread has access to this <a href="http://msdn.microsoft.com/en-us/library/ms615925">DispatcherObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms615925">DispatcherObject</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557762">WritePostscript</a></td>
<td><div class="summary">
Raises the <a href="http://msdn.microsoft.com/en-us/library/ms596566">Changed</a> event for the <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> and invokes its <a href="http://msdn.microsoft.com/en-us/library/ms557749">OnChanged()()()</a> method. Classes that derive from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> should call this method at the end of any API that modifies class members that are not stored as dependency properties.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557763">WritePreamble</a></td>
<td><div class="summary">
Verifies that the <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> is not frozen and that it is being accessed from a valid threading context. <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a> inheritors should call this method at the beginning of any API that writes to data members that are not dependency properties.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602734">Freezable</a>.)</td>
</tr>
</tbody>
</table>

## See Also
[PopupWindowAction Class](https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.popupwindowaction)

[Microsoft.Practices.Prism.Interactivity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity)
