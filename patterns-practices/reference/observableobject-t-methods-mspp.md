---
TOCTitle: 'ObservableObject(T) Methods'
Title: 'ObservableObject(T) Methods (Microsoft.Practices.Prism)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.ObservableObject\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431068(v=PandP.50)'
---

Prism Class Library

ObservableObject&lt;(Of &lt;(T&gt;)&gt;) Methods
================================================

The [ObservableObject&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.observableobject%601) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598898">AddHandler(RoutedEvent, Delegate)</a></td>
<td><div class="summary">
Adds a routed event handler for a specified routed event, adding the handler to the handler collection on the current element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598899">AddHandler(RoutedEvent, Delegate, Boolean)</a></td>
<td><div class="summary">
Adds a routed event handler for a specified routed event, adding the handler to the handler collection on the current element. Specify handledEventsToo as true to have the provided handler be invoked for routed event that had already been marked as handled by another element along the event route.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598090">AddLogicalChild</a></td>
<td><div class="summary">
Adds the provided object to the logical tree of this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598900">AddToEventRoute</a></td>
<td><div class="summary">
Adds handlers to the specified <a href="http://msdn.microsoft.com/en-us/library/ms602393">EventRoute</a> for the current <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a> event handler collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608754">AddVisualChild</a></td>
<td><div class="summary">
Defines the parent-child relationship between two visuals.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598901">ApplyAnimationClock(DependencyProperty, AnimationClock)</a></td>
<td><div class="summary">
Applies an animation to a specified dependency property on this element. Any existing animations are stopped and replaced with the new animation.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598902">ApplyAnimationClock(DependencyProperty, AnimationClock, HandoffBehavior)</a></td>
<td><div class="summary">
Applies an animation to a specified dependency property on this element, with the ability to specify what happens if the property already has a running animation.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598092">ApplyTemplate</a></td>
<td><div class="summary">
Builds the current template's visual tree if necessary, and returns a value that indicates whether the visual tree was rebuilt by this call.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598904">Arrange</a></td>
<td><div class="summary">
Positions child elements and determines a size for a <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>. Parent elements call this method from their <a href="http://msdn.microsoft.com/en-us/library/ms598903">ArrangeCore(Rect)</a> implementation (or a WPF framework-level equivalent) to form a recursive layout update. This method constitutes the second pass of a layout update.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598095">ArrangeCore</a></td>
<td><div class="summary">
Implements <a href="http://msdn.microsoft.com/en-us/library/ms598903">ArrangeCore(Rect)</a> (defined as virtual in <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>) and seals the implementation.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598098">ArrangeOverride</a></td>
<td><div class="summary">
When overridden in a derived class, positions child elements and determines a size for a <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a> derived class.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598906">BeginAnimation(DependencyProperty, AnimationTimeline)</a></td>
<td><div class="summary">
Starts an animation for a specified animated property on this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598905">BeginAnimation(DependencyProperty, AnimationTimeline, HandoffBehavior)</a></td>
<td><div class="summary">
Starts a specific animation for a specified animated property on this element, with the option of specifying what happens if the property already has a running animation.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598100">BeginInit</a></td>
<td><div class="summary">
Starts the initialization process for this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598106">BeginStoryboard(Storyboard)</a></td>
<td><div class="summary">
Begins the sequence of actions that are contained in the provided storyboard.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598109">BeginStoryboard(Storyboard, HandoffBehavior)</a></td>
<td><div class="summary">
Begins the sequence of actions contained in the provided storyboard, with options specified for what should happen if the property is already animated.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598103">BeginStoryboard(Storyboard, HandoffBehavior, Boolean)</a></td>
<td><div class="summary">
Begins the sequence of actions contained in the provided storyboard, with specified state for control of the animation after it is started.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598110">BringIntoView()()()</a></td>
<td><div class="summary">
Attempts to bring this element into view, within any scrollable regions it is contained within.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598115">BringIntoView(Rect)</a></td>
<td><div class="summary">
Attempts to bring the provided region size of this element into view, within any scrollable regions it is contained within.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598907">CaptureMouse</a></td>
<td><div class="summary">
Attempts to force capture of the mouse to this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598908">CaptureStylus</a></td>
<td><div class="summary">
Attempts to force capture of the stylus to this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd992299">CaptureTouch</a></td>
<td><div class="summary">
Attempts to force capture of a touch to this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms591167">CheckAccess</a></td>
<td><div class="summary">
Determines whether the calling thread has access to this <a href="http://msdn.microsoft.com/en-us/library/ms615925">DispatcherObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms615925">DispatcherObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597464">ClearValue(DependencyProperty)</a></td>
<td><div class="summary">
Clears the local value of a property. The property to be cleared is specified by a <a href="http://msdn.microsoft.com/en-us/library/ms589318">DependencyProperty</a> identifier.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597465">ClearValue(DependencyPropertyKey)</a></td>
<td><div class="summary">
Clears the local value of a read-only property. The property to be cleared is specified by a <a href="http://msdn.microsoft.com/en-us/library/ms602348">DependencyPropertyKey</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597466">CoerceValue</a></td>
<td><div class="summary">
Coerces the value of the specified dependency property. This is accomplished by invoking any <a href="http://msdn.microsoft.com/en-us/library/ms589135">CoerceValueCallback</a> function specified in property metadata for the dependency property as it exists on the calling <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598118">EndInit</a></td>
<td><div class="summary">
Indicates that the initialization process for the element is complete.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/aa345743">Equals</a></td>
<td><div class="summary">
Determines whether a provided <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a> is equivalent to the current <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608755">FindCommonVisualAncestor</a></td>
<td><div class="summary">
Returns the common ancestor of two visual objects.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598120">FindName</a></td>
<td><div class="summary">
Finds an element that has the provided identifier name.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598123">FindResource</a></td>
<td><div class="summary">
Searches for a resource with the specified key, and throws an exception if the requested resource is not found.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598909">Focus</a></td>
<td><div class="summary">
Attempts to set focus to this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598910">GetAnimationBaseValue</a></td>
<td><div class="summary">
Returns the base property value for the specified property on this element, disregarding any possible animated value from a running or stopped animation.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598124">GetBindingExpression</a></td>
<td><div class="summary">
Returns the <a href="http://msdn.microsoft.com/en-us/library/ms613455">BindingExpression</a> that represents the binding on the specified property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/aa345744">GetHashCode</a></td>
<td><div class="summary">
Gets a hash code for this <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598129">GetLayoutClip</a></td>
<td><div class="summary">
Returns a geometry for a clipping mask. The mask applies if the layout system attempts to arrange an element that is larger than the available display space.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597467">GetLocalValueEnumerator</a></td>
<td><div class="summary">
Creates a specialized enumerator for determining which dependency properties have locally set values on this <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598132">GetTemplateChild</a></td>
<td><div class="summary">
Returns the named element in the visual tree of an instantiated <a href="http://msdn.microsoft.com/en-us/library/ms609827">ControlTemplate</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598135">GetUIParentCore</a></td>
<td><div class="summary">
Returns an alternative logical parent for this element if there is no visual parent.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597469">GetValue</a></td>
<td><div class="summary">
Returns the current effective value of a dependency property on this instance of a <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598141">GetVisualChild</a></td>
<td><div class="summary">
Overrides <a href="http://msdn.microsoft.com/en-us/library/ms608857">GetVisualChild(Int32)</a>, and returns a child at the specified index from a collection of child elements.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598915">HitTestCore(PointHitTestParameters)</a></td>
<td><div class="summary">
Implements <a href="http://msdn.microsoft.com/en-us/library/ms608859">HitTestCore(PointHitTestParameters)</a> to supply base element hit testing behavior (returning <a href="http://msdn.microsoft.com/en-us/library/ms619158">HitTestResult</a>).
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598914">HitTestCore(GeometryHitTestParameters)</a></td>
<td><div class="summary">
Implements <a href="http://msdn.microsoft.com/en-us/library/ms608858">HitTestCore(GeometryHitTestParameters)</a> to supply base element hit testing behavior (returning <a href="http://msdn.microsoft.com/en-us/library/ms634997">GeometryHitTestResult</a>).
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598916">InputHitTest</a></td>
<td><div class="summary">
Returns the input element within the current element that is at the specified coordinates, relative to the current element's origin.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598917">InvalidateArrange</a></td>
<td><div class="summary">
Invalidates the arrange state (layout) for the element. After the invalidation, the element will have its layout updated, which will occur asynchronously unless subsequently forced by <a href="http://msdn.microsoft.com/en-us/library/ms599327">UpdateLayout()()()</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598918">InvalidateMeasure</a></td>
<td><div class="summary">
Invalidates the measurement state (layout) for the element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597470">InvalidateProperty</a></td>
<td><div class="summary">
Re-evaluates the effective value for the specified dependency property
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598919">InvalidateVisual</a></td>
<td><div class="summary">
Invalidates the rendering of the element, and forces a complete new layout pass. <a href="http://msdn.microsoft.com/en-us/library/ms599305">OnRender(DrawingContext)</a> is called after the layout cycle is completed.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608860">IsAncestorOf</a></td>
<td><div class="summary">
Determines whether the visual object is an ancestor of the descendant visual object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608861">IsDescendantOf</a></td>
<td><div class="summary">
Determines whether the visual object is a descendant of the ancestor visual object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598921">Measure</a></td>
<td><div class="summary">
Updates the <a href="http://msdn.microsoft.com/en-us/library/ms588686">DesiredSize</a> of a <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>. Parent elements call this method from their own <a href="http://msdn.microsoft.com/en-us/library/ms598920">MeasureCore(Size)</a> implementations to form a recursive layout update. Calling this method constitutes the first pass (the &quot;Measure&quot; pass) of a layout update.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598224">MeasureCore</a></td>
<td><div class="summary">
Implements basic measure-pass layout system behavior for <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598227">MeasureOverride</a></td>
<td><div class="summary">
When overridden in a derived class, measures the size in layout required for child elements and determines a size for the <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>-derived class.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598231">MoveFocus</a></td>
<td><div class="summary">
Moves the keyboard focus away from this element and to another element in a provided traversal direction.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598923">OnAccessKey</a></td>
<td><div class="summary">
Provides class handling for when an access key that is meaningful for this element is invoked.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598234">OnApplyTemplate</a></td>
<td><div class="summary">
When overridden in a derived class, is invoked whenever application code or internal processes call <a href="http://msdn.microsoft.com/en-us/library/ms598092">ApplyTemplate()()()</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598924">OnChildDesiredSizeChanged</a></td>
<td><div class="summary">
Supports layout behavior when a child element is resized.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598237">OnContextMenuClosing</a></td>
<td><div class="summary">
Invoked whenever an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596552">ContextMenuClosing</a> routed event reaches this class in its route. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598240">OnContextMenuOpening</a></td>
<td><div class="summary">
Invoked whenever an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596554">ContextMenuOpening</a> routed event reaches this class in its route. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598925">OnCreateAutomationPeer</a></td>
<td><div class="summary">
Returns class-specific <a href="http://msdn.microsoft.com/en-us/library/ms523415">AutomationPeer</a> implementations for the Windows Presentation Foundation (WPF) infrastructure.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598926">OnDragEnter</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596509">DragEnter</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598927">OnDragLeave</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596511">DragLeave</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598928">OnDragOver</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596513">DragOver</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598929">OnDrop</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596509">DragEnter</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598930">OnGiveFeedback</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596516">GiveFeedback</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598242">OnGotFocus</a></td>
<td><div class="summary">
Invoked whenever an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596645">GotFocus</a> event reaches this element in its route.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598932">OnGotKeyboardFocus</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/aa345917">GotKeyboardFocus</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598933">OnGotMouseCapture</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523136">GotMouseCapture</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598934">OnGotStylusCapture</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523179">GotStylusCapture</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd783579">OnGotTouchCapture</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd989297">GotTouchCapture</a> routed event that occurs when a touch is captured to this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598244">OnInitialized</a></td>
<td><div class="summary">
Raises the <a href="http://msdn.microsoft.com/en-us/library/ms596557">Initialized</a> event. This method is invoked whenever <a href="http://msdn.microsoft.com/en-us/library/ms600884">IsInitialized</a> is set to true internally.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598935">OnIsKeyboardFocusedChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596651">IsKeyboardFocusedChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598936">OnIsKeyboardFocusWithinChanged</a></td>
<td><div class="summary">
Invoked just before the <a href="http://msdn.microsoft.com/en-us/library/ms596652">IsKeyboardFocusWithinChanged</a> event is raised by this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599252">OnIsMouseCapturedChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596653">IsMouseCapturedChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599253">OnIsMouseCaptureWithinChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596654">IsMouseCaptureWithinChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599254">OnIsMouseDirectlyOverChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596655">IsMouseDirectlyOverChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599255">OnIsStylusCapturedChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596656">IsStylusCapturedChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599256">OnIsStylusCaptureWithinChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596657">IsStylusCaptureWithinChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599257">OnIsStylusDirectlyOverChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596658">IsStylusDirectlyOverChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599258">OnKeyDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523126">KeyDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599259">OnKeyUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523129">KeyUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599260">OnLostFocus</a></td>
<td><div class="summary">
Raises the <a href="http://msdn.microsoft.com/en-us/library/ms596673">LostFocus</a> routed event by using the event data that is provided.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599261">OnLostKeyboardFocus</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/aa345918">LostKeyboardFocus</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599262">OnLostMouseCapture</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523139">LostMouseCapture</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599263">OnLostStylusCapture</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523183">LostStylusCapture</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd784514">OnLostTouchCapture</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd784505">LostTouchCapture</a> routed event that occurs when this element loses a touch capture.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd549563">OnManipulationBoundaryFeedback</a></td>
<td><div class="summary">
Called when the <a href="http://msdn.microsoft.com/en-us/library/dd549583">ManipulationBoundaryFeedback</a> event occurs.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd403062">OnManipulationCompleted</a></td>
<td><div class="summary">
Called when the <a href="http://msdn.microsoft.com/en-us/library/dd403080">ManipulationCompleted</a> event occurs.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd403423">OnManipulationDelta</a></td>
<td><div class="summary">
Called when the <a href="http://msdn.microsoft.com/en-us/library/dd403301">ManipulationDelta</a> event occurs.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd549618">OnManipulationInertiaStarting</a></td>
<td><div class="summary">
Called when the <a href="http://msdn.microsoft.com/en-us/library/dd549561">ManipulationInertiaStarting</a> event occurs.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd403303">OnManipulationStarted</a></td>
<td><div class="summary">
Called when the <a href="http://msdn.microsoft.com/en-us/library/dd403503">ManipulationStarted</a> event occurs.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd991606">OnManipulationStarting</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd782370">ManipulationStarting</a> routed event that occurs when the manipulation processor is first created.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599264">OnMouseDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523141">MouseDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599265">OnMouseEnter</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523142">MouseEnter</a> attached event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599266">OnMouseLeave</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523144">MouseLeave</a> attached event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599267">OnMouseLeftButtonDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596680">MouseLeftButtonDown</a> routed event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599268">OnMouseLeftButtonUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596681">MouseLeftButtonUp</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599269">OnMouseMove</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523146">MouseMove</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599270">OnMouseRightButtonDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596683">MouseRightButtonDown</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599271">OnMouseRightButtonUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596684">MouseRightButtonUp</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599272">OnMouseUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523148">MouseUp</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599273">OnMouseWheel</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523151">MouseWheel</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599274">OnPreviewDragEnter</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596517">PreviewDragEnter</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599275">OnPreviewDragLeave</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596519">PreviewDragLeave</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599276">OnPreviewDragOver</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596521">PreviewDragOver</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599277">OnPreviewDrop</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596523">PreviewDrop</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599278">OnPreviewGiveFeedback</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596525">PreviewGiveFeedback</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599279">OnPreviewGotKeyboardFocus</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/aa345919">PreviewGotKeyboardFocus</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599280">OnPreviewKeyDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523131">PreviewKeyDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599281">OnPreviewKeyUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523134">PreviewKeyUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599282">OnPreviewLostKeyboardFocus</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523131">PreviewKeyDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599283">OnPreviewMouseDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523154">PreviewMouseDown</a> attached routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599284">OnPreviewMouseLeftButtonDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596697">PreviewMouseLeftButtonDown</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599285">OnPreviewMouseLeftButtonUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596698">PreviewMouseLeftButtonUp</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599286">OnPreviewMouseMove</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523159">PreviewMouseMove</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599287">OnPreviewMouseRightButtonDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596700">PreviewMouseRightButtonDown</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599288">OnPreviewMouseRightButtonUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596701">PreviewMouseRightButtonUp</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599289">OnPreviewMouseUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523163">PreviewMouseUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599290">OnPreviewMouseWheel</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523168">PreviewMouseWheel</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599291">OnPreviewQueryContinueDrag</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596527">PreviewQueryContinueDrag</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599292">OnPreviewStylusButtonDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523186">PreviewStylusButtonDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599293">OnPreviewStylusButtonUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523189">PreviewStylusButtonUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599294">OnPreviewStylusDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523193">PreviewStylusDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599295">OnPreviewStylusInAirMove</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523196">PreviewStylusInAirMove</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599296">OnPreviewStylusInRange</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523198">PreviewStylusInRange</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599297">OnPreviewStylusMove</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588440">PreviewStylusMove</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599298">OnPreviewStylusOutOfRange</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588441">PreviewStylusOutOfRange</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599299">OnPreviewStylusSystemGesture</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588442">PreviewStylusSystemGesture</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599300">OnPreviewStylusUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588443">PreviewStylusUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599301">OnPreviewTextInput</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588471">PreviewTextInput</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd992477">OnPreviewTouchDown</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd991743">PreviewTouchDown</a> routed event that occurs when a touch presses this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd784544">OnPreviewTouchMove</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd990490">PreviewTouchMove</a> routed event that occurs when a touch moves while inside this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd783493">OnPreviewTouchUp</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd783905">PreviewTouchUp</a> routed event that occurs when a touch is released inside this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598246">OnPropertyChanged</a></td>
<td><div class="summary">
Invoked whenever the effective value of any dependency property on this <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a> has been updated. The specific dependency property that changed is reported in the arguments parameter. Overrides <a href="http://msdn.microsoft.com/en-us/library/ms597471">OnPropertyChanged(DependencyPropertyChangedEventArgs)</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599302">OnQueryContinueDrag</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596529">QueryContinueDrag</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599303">OnQueryCursor</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523171">QueryCursor</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599305">OnRender</a></td>
<td><div class="summary">
When overridden in a derived class, participates in rendering operations that are directed by the layout system. The rendering instructions for this element are not used directly when this method is invoked, and are instead preserved for later asynchronous use by layout and drawing.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598248">OnRenderSizeChanged</a></td>
<td><div class="summary">
Raises the <a href="http://msdn.microsoft.com/en-us/library/ms596560">SizeChanged</a> event, using the specified information as part of the eventual event data.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598251">OnStyleChanged</a></td>
<td><div class="summary">
Invoked when the style in use on this element changes, which will invalidate the layout.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599306">OnStylusButtonDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588445">StylusButtonDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599307">OnStylusButtonUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588446">StylusButtonUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599308">OnStylusDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588447">StylusDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599309">OnStylusEnter</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588448">StylusEnter</a> attached event is raised by this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599310">OnStylusInAirMove</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588449">StylusInAirMove</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599311">OnStylusInRange</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588450">StylusInRange</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599312">OnStylusLeave</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588452">StylusLeave</a> attached event is raised by this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599313">OnStylusMove</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588455">StylusMove</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599314">OnStylusOutOfRange</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588460">StylusOutOfRange</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599315">OnStylusSystemGesture</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588464">StylusSystemGesture</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599316">OnStylusUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588467">StylusUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599317">OnTextInput</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms601826">TextInput</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598255">OnToolTipClosing</a></td>
<td><div class="summary">
Invoked whenever an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596563">ToolTipClosing</a> routed event reaches this class in its route. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598256">OnToolTipOpening</a></td>
<td><div class="summary">
Invoked whenever the <a href="http://msdn.microsoft.com/en-us/library/ms596564">ToolTipOpening</a> routed event reaches this class in its route. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd991371">OnTouchDown</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd782616">TouchDown</a> routed event that occurs when a touch presses inside this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd782614">OnTouchEnter</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd990673">TouchEnter</a> routed event that occurs when a touch moves from outside to inside the bounds of this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd782894">OnTouchLeave</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd991524">TouchLeave</a> routed event that occurs when a touch moves from inside to outside the bounds of this <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd783255">OnTouchMove</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd991311">TouchMove</a> routed event that occurs when a touch moves while inside this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd992297">OnTouchUp</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd991789">TouchUp</a> routed event that occurs when a touch is released inside this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608862">OnVisualChildrenChanged</a></td>
<td><div class="summary">
Called when the <a href="http://msdn.microsoft.com/en-us/library/ms635644">VisualCollection</a> of the visual object is modified.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598258">OnVisualParentChanged</a></td>
<td><div class="summary">
Invoked when the parent of this element in the visual tree is changed. Overrides <a href="http://msdn.microsoft.com/en-us/library/ms599318">OnVisualParentChanged(DependencyObject)</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598260">ParentLayoutInvalidated</a></td>
<td><div class="summary">
Supports incremental layout implementations in specialized subclasses of <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>. <a href="http://msdn.microsoft.com/en-us/library/ms598260">ParentLayoutInvalidated(UIElement)</a> is invoked when a child element has invalidated a property that is marked in metadata as affecting the parent's measure or arrange passes during layout.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/aa346960">PointFromScreen</a></td>
<td><div class="summary">
Converts a <a href="http://msdn.microsoft.com/en-us/library/ms602977">Point</a> in screen coordinates into a <a href="http://msdn.microsoft.com/en-us/library/ms602977">Point</a> that represents the current coordinate system of the <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/aa346961">PointToScreen</a></td>
<td><div class="summary">
Converts a <a href="http://msdn.microsoft.com/en-us/library/ms602977">Point</a> that represents the current coordinate system of the <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a> into a <a href="http://msdn.microsoft.com/en-us/library/ms602977">Point</a> in screen coordinates.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598263">PredictFocus</a></td>
<td><div class="summary">
Determines the next element that would receive focus relative to this element for a provided focus movement direction, but does not actually move the focus.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599320">RaiseEvent</a></td>
<td><div class="summary">
Raises a specific routed event. The <a href="http://msdn.microsoft.com/en-us/library/ms589739">RoutedEvent</a> to be raised is identified within the <a href="http://msdn.microsoft.com/en-us/library/ms589740">RoutedEventArgs</a> instance that is provided (as the <a href="http://msdn.microsoft.com/en-us/library/ms601234">RoutedEvent</a> property of that event data).
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597472">ReadLocalValue</a></td>
<td><div class="summary">
Returns the local value of a dependency property, if it exists.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598265">RegisterName</a></td>
<td><div class="summary">
Provides an accessor that simplifies access to the <a href="http://msdn.microsoft.com/en-us/library/ms602968">NameScope</a> registration method.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd783351">ReleaseAllTouchCaptures</a></td>
<td><div class="summary">
Releases all captured touch devices from this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599321">ReleaseMouseCapture</a></td>
<td><div class="summary">
Releases the mouse capture, if this element held the capture.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599322">ReleaseStylusCapture</a></td>
<td><div class="summary">
Releases the stylus device capture, if this element held the capture.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd990535">ReleaseTouchCapture</a></td>
<td><div class="summary">
Attempts to release the specified touch device from this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599323">RemoveHandler</a></td>
<td><div class="summary">
Removes the specified routed event handler from this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598268">RemoveLogicalChild</a></td>
<td><div class="summary">
Removes the provided object from this element's logical tree. <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a> updates the affected logical tree parent pointers to keep in sync with this deletion.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608864">RemoveVisualChild</a></td>
<td><div class="summary">
Removes the parent-child relationship between two visuals.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598273">SetBinding(DependencyProperty, BindingBase)</a></td>
<td><div class="summary">
Attaches a binding to this element, based on the provided binding object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598270">SetBinding(DependencyProperty, String)</a></td>
<td><div class="summary">
Attaches a binding to this element, based on the provided source property name as a path qualification to the data source.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd549644">SetCurrentValue</a></td>
<td><div class="summary">
Sets the value of a dependency property without changing its value source.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557690">SetResourceReference</a></td>
<td><div class="summary">
Searches for a resource with the specified name and sets up a resource reference to it for the specified property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597473">SetValue(DependencyProperty, Object)</a></td>
<td><div class="summary">
Sets the local value of a dependency property, specified by its dependency property identifier.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597474">SetValue(DependencyPropertyKey, Object)</a></td>
<td><div class="summary">
Sets the local value of a read-only dependency property, specified by the <a href="http://msdn.microsoft.com/en-us/library/ms602348">DependencyPropertyKey</a> identifier of the dependency property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599324">ShouldSerializeCommandBindings</a></td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the <a href="http://msdn.microsoft.com/en-us/library/ms588680">CommandBindings</a> property on instances of this class.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599325">ShouldSerializeInputBindings</a></td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the <a href="http://msdn.microsoft.com/en-us/library/ms588692">InputBindings</a> property on instances of this class.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597475">ShouldSerializeProperty</a></td>
<td><div class="summary">
Returns a value that indicates whether serialization processes should serialize the value for the provided dependency property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557692">ShouldSerializeResources</a></td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the <a href="http://msdn.microsoft.com/en-us/library/ms600898">Resources</a> property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557694">ShouldSerializeStyle</a></td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the <a href="http://msdn.microsoft.com/en-us/library/ms600899">Style</a> property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557696">ShouldSerializeTriggers</a></td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the <a href="http://msdn.microsoft.com/en-us/library/ms600903">Triggers</a> property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608865">TransformToAncestor(Visual)</a></td>
<td><div class="summary">
Returns a transform that can be used to transform coordinates from the <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a> to the specified <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a> ancestor of the visual object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bb763975">TransformToAncestor(Visual3D)</a></td>
<td><div class="summary">
Returns a transform that can be used to transform coordinates from the <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a> to the specified <a href="http://msdn.microsoft.com/en-us/library/ms594932">Visual3D</a> ancestor of the visual object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608866">TransformToDescendant</a></td>
<td><div class="summary">
Returns a transform that can be used to transform coordinates from the <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a> to the specified visual object descendant.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608867">TransformToVisual</a></td>
<td><div class="summary">
Returns a transform that can be used to transform coordinates from the <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a> to the specified visual object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637">Visual</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599326">TranslatePoint</a></td>
<td><div class="summary">
Translates a point relative to this element to coordinates that are relative to the specified element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557698">TryFindResource</a></td>
<td><div class="summary">
Searches for a resource with the specified key, and returns that resource if found.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557700">UnregisterName</a></td>
<td><div class="summary">
Simplifies access to the <a href="http://msdn.microsoft.com/en-us/library/ms602968">NameScope</a> de-registration method.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/hh534717">UpdateDefaultStyle</a></td>
<td><div class="summary">
Reapplies the default style to the current <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599327">UpdateLayout</a></td>
<td><div class="summary">
Ensures that all visual child elements of this element are properly updated for layout.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431068.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms591169">VerifyAccess</a></td>
<td><div class="summary">
Enforces that the calling thread has access to this <a href="http://msdn.microsoft.com/en-us/library/ms615925">DispatcherObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms615925">DispatcherObject</a>.)</td>
</tr>
</tbody>
</table>

See Also
--------


[ObservableObject&lt;(Of &lt;(T&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.observableobject%601)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
