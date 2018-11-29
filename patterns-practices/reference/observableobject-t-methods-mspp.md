---
TOCTitle: 'ObservableObject(T) Methods'
Title: 'ObservableObject(T) Methods (Microsoft.Practices.Prism)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.ObservableObject\`1'
ms:mtpsurl: 'observableobject-t-methods-mspp.md'
---

# ObservableObject(Of T) Methods

The [ObservableObject(Of T) Methods](/patterns-practices/reference/observableobject-t-class-mspp) type exposes the following members.

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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598898" data-raw-source="[AddHandler(RoutedEvent, Delegate)](http://msdn.microsoft.com/en-us/library/ms598898)">AddHandler(RoutedEvent, Delegate)</a></td>
<td><div class="summary">
Adds a routed event handler for a specified routed event, adding the handler to the handler collection on the current element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598899" data-raw-source="[AddHandler(RoutedEvent, Delegate, Boolean)](http://msdn.microsoft.com/en-us/library/ms598899)">AddHandler(RoutedEvent, Delegate, Boolean)</a></td>
<td><div class="summary">
Adds a routed event handler for a specified routed event, adding the handler to the handler collection on the current element. Specify handledEventsToo as true to have the provided handler be invoked for routed event that had already been marked as handled by another element along the event route.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598090" data-raw-source="[AddLogicalChild](http://msdn.microsoft.com/en-us/library/ms598090)">AddLogicalChild</a></td>
<td><div class="summary">
Adds the provided object to the logical tree of this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598900" data-raw-source="[AddToEventRoute](http://msdn.microsoft.com/en-us/library/ms598900)">AddToEventRoute</a></td>
<td><div class="summary">
Adds handlers to the specified <a href="http://msdn.microsoft.com/en-us/library/ms602393" data-raw-source="[EventRoute](http://msdn.microsoft.com/en-us/library/ms602393)">EventRoute</a> for the current <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a> event handler collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608754" data-raw-source="[AddVisualChild](http://msdn.microsoft.com/en-us/library/ms608754)">AddVisualChild</a></td>
<td><div class="summary">
Defines the parent-child relationship between two visuals.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598901" data-raw-source="[ApplyAnimationClock(DependencyProperty, AnimationClock)](http://msdn.microsoft.com/en-us/library/ms598901)">ApplyAnimationClock(DependencyProperty, AnimationClock)</a></td>
<td><div class="summary">
Applies an animation to a specified dependency property on this element. Any existing animations are stopped and replaced with the new animation.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598902" data-raw-source="[ApplyAnimationClock(DependencyProperty, AnimationClock, HandoffBehavior)](http://msdn.microsoft.com/en-us/library/ms598902)">ApplyAnimationClock(DependencyProperty, AnimationClock, HandoffBehavior)</a></td>
<td><div class="summary">
Applies an animation to a specified dependency property on this element, with the ability to specify what happens if the property already has a running animation.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598092" data-raw-source="[ApplyTemplate](http://msdn.microsoft.com/en-us/library/ms598092)">ApplyTemplate</a></td>
<td><div class="summary">
Builds the current template&#39;s visual tree if necessary, and returns a value that indicates whether the visual tree was rebuilt by this call.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598904" data-raw-source="[Arrange](http://msdn.microsoft.com/en-us/library/ms598904)">Arrange</a></td>
<td><div class="summary">
Positions child elements and determines a size for a <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>. Parent elements call this method from their <a href="http://msdn.microsoft.com/en-us/library/ms598903" data-raw-source="[ArrangeCore(Rect)](http://msdn.microsoft.com/en-us/library/ms598903)">ArrangeCore(Rect)</a> implementation (or a WPF framework-level equivalent) to form a recursive layout update. This method constitutes the second pass of a layout update.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598095" data-raw-source="[ArrangeCore](http://msdn.microsoft.com/en-us/library/ms598095)">ArrangeCore</a></td>
<td><div class="summary">
Implements <a href="http://msdn.microsoft.com/en-us/library/ms598903" data-raw-source="[ArrangeCore(Rect)](http://msdn.microsoft.com/en-us/library/ms598903)">ArrangeCore(Rect)</a> (defined as virtual in <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>) and seals the implementation.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598098" data-raw-source="[ArrangeOverride](http://msdn.microsoft.com/en-us/library/ms598098)">ArrangeOverride</a></td>
<td><div class="summary">
When overridden in a derived class, positions child elements and determines a size for a <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a> derived class.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598906" data-raw-source="[BeginAnimation(DependencyProperty, AnimationTimeline)](http://msdn.microsoft.com/en-us/library/ms598906)">BeginAnimation(DependencyProperty, AnimationTimeline)</a></td>
<td><div class="summary">
Starts an animation for a specified animated property on this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598905" data-raw-source="[BeginAnimation(DependencyProperty, AnimationTimeline, HandoffBehavior)](http://msdn.microsoft.com/en-us/library/ms598905)">BeginAnimation(DependencyProperty, AnimationTimeline, HandoffBehavior)</a></td>
<td><div class="summary">
Starts a specific animation for a specified animated property on this element, with the option of specifying what happens if the property already has a running animation.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598100" data-raw-source="[BeginInit](http://msdn.microsoft.com/en-us/library/ms598100)">BeginInit</a></td>
<td><div class="summary">
Starts the initialization process for this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598106" data-raw-source="[BeginStoryboard(Storyboard)](http://msdn.microsoft.com/en-us/library/ms598106)">BeginStoryboard(Storyboard)</a></td>
<td><div class="summary">
Begins the sequence of actions that are contained in the provided storyboard.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598109" data-raw-source="[BeginStoryboard(Storyboard, HandoffBehavior)](http://msdn.microsoft.com/en-us/library/ms598109)">BeginStoryboard(Storyboard, HandoffBehavior)</a></td>
<td><div class="summary">
Begins the sequence of actions contained in the provided storyboard, with options specified for what should happen if the property is already animated.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598103" data-raw-source="[BeginStoryboard(Storyboard, HandoffBehavior, Boolean)](http://msdn.microsoft.com/en-us/library/ms598103)">BeginStoryboard(Storyboard, HandoffBehavior, Boolean)</a></td>
<td><div class="summary">
Begins the sequence of actions contained in the provided storyboard, with specified state for control of the animation after it is started.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598110" data-raw-source="[BringIntoView](http://msdn.microsoft.com/en-us/library/ms598110)">BringIntoView</a></td>
<td><div class="summary">
Attempts to bring this element into view, within any scrollable regions it is contained within.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598115" data-raw-source="[BringIntoView(Rect)](http://msdn.microsoft.com/en-us/library/ms598115)">BringIntoView(Rect)</a></td>
<td><div class="summary">
Attempts to bring the provided region size of this element into view, within any scrollable regions it is contained within.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598907" data-raw-source="[CaptureMouse](http://msdn.microsoft.com/en-us/library/ms598907)">CaptureMouse</a></td>
<td><div class="summary">
Attempts to force capture of the mouse to this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598908" data-raw-source="[CaptureStylus](http://msdn.microsoft.com/en-us/library/ms598908)">CaptureStylus</a></td>
<td><div class="summary">
Attempts to force capture of the stylus to this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd992299" data-raw-source="[CaptureTouch](http://msdn.microsoft.com/en-us/library/dd992299)">CaptureTouch</a></td>
<td><div class="summary">
Attempts to force capture of a touch to this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms591167" data-raw-source="[CheckAccess](http://msdn.microsoft.com/en-us/library/ms591167)">CheckAccess</a></td>
<td><div class="summary">
Determines whether the calling thread has access to this <a href="http://msdn.microsoft.com/en-us/library/ms615925" data-raw-source="[DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925)">DispatcherObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms615925" data-raw-source="[DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925)">DispatcherObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597464" data-raw-source="[ClearValue(DependencyProperty)](http://msdn.microsoft.com/en-us/library/ms597464)">ClearValue(DependencyProperty)</a></td>
<td><div class="summary">
Clears the local value of a property. The property to be cleared is specified by a <a href="http://msdn.microsoft.com/en-us/library/ms589318" data-raw-source="[DependencyProperty](http://msdn.microsoft.com/en-us/library/ms589318)">DependencyProperty</a> identifier.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597465" data-raw-source="[ClearValue(DependencyPropertyKey)](http://msdn.microsoft.com/en-us/library/ms597465)">ClearValue(DependencyPropertyKey)</a></td>
<td><div class="summary">
Clears the local value of a read-only property. The property to be cleared is specified by a <a href="http://msdn.microsoft.com/en-us/library/ms602348" data-raw-source="[DependencyPropertyKey](http://msdn.microsoft.com/en-us/library/ms602348)">DependencyPropertyKey</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597466" data-raw-source="[CoerceValue](http://msdn.microsoft.com/en-us/library/ms597466)">CoerceValue</a></td>
<td><div class="summary">
Coerces the value of the specified dependency property. This is accomplished by invoking any <a href="http://msdn.microsoft.com/en-us/library/ms589135" data-raw-source="[CoerceValueCallback](http://msdn.microsoft.com/en-us/library/ms589135)">CoerceValueCallback</a> function specified in property metadata for the dependency property as it exists on the calling <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598118" data-raw-source="[EndInit](http://msdn.microsoft.com/en-us/library/ms598118)">EndInit</a></td>
<td><div class="summary">
Indicates that the initialization process for the element is complete.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/aa345743" data-raw-source="[Equals](http://msdn.microsoft.com/en-us/library/aa345743)">Equals</a></td>
<td><div class="summary">
Determines whether a provided <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a> is equivalent to the current <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7" data-raw-source="[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608755" data-raw-source="[FindCommonVisualAncestor](http://msdn.microsoft.com/en-us/library/ms608755)">FindCommonVisualAncestor</a></td>
<td><div class="summary">
Returns the common ancestor of two visual objects.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598120" data-raw-source="[FindName](http://msdn.microsoft.com/en-us/library/ms598120)">FindName</a></td>
<td><div class="summary">
Finds an element that has the provided identifier name.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598123" data-raw-source="[FindResource](http://msdn.microsoft.com/en-us/library/ms598123)">FindResource</a></td>
<td><div class="summary">
Searches for a resource with the specified key, and throws an exception if the requested resource is not found.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598909" data-raw-source="[Focus](http://msdn.microsoft.com/en-us/library/ms598909)">Focus</a></td>
<td><div class="summary">
Attempts to set focus to this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598910" data-raw-source="[GetAnimationBaseValue](http://msdn.microsoft.com/en-us/library/ms598910)">GetAnimationBaseValue</a></td>
<td><div class="summary">
Returns the base property value for the specified property on this element, disregarding any possible animated value from a running or stopped animation.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598124" data-raw-source="[GetBindingExpression](http://msdn.microsoft.com/en-us/library/ms598124)">GetBindingExpression</a></td>
<td><div class="summary">
Returns the <a href="http://msdn.microsoft.com/en-us/library/ms613455" data-raw-source="[BindingExpression](http://msdn.microsoft.com/en-us/library/ms613455)">BindingExpression</a> that represents the binding on the specified property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/aa345744" data-raw-source="[GetHashCode](http://msdn.microsoft.com/en-us/library/aa345744)">GetHashCode</a></td>
<td><div class="summary">
Gets a hash code for this <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598129" data-raw-source="[GetLayoutClip](http://msdn.microsoft.com/en-us/library/ms598129)">GetLayoutClip</a></td>
<td><div class="summary">
Returns a geometry for a clipping mask. The mask applies if the layout system attempts to arrange an element that is larger than the available display space.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597467" data-raw-source="[GetLocalValueEnumerator](http://msdn.microsoft.com/en-us/library/ms597467)">GetLocalValueEnumerator</a></td>
<td><div class="summary">
Creates a specialized enumerator for determining which dependency properties have locally set values on this <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598132" data-raw-source="[GetTemplateChild](http://msdn.microsoft.com/en-us/library/ms598132)">GetTemplateChild</a></td>
<td><div class="summary">
Returns the named element in the visual tree of an instantiated <a href="http://msdn.microsoft.com/en-us/library/ms609827" data-raw-source="[ControlTemplate](http://msdn.microsoft.com/en-us/library/ms609827)">ControlTemplate</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9" data-raw-source="[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65" data-raw-source="[Type](http://msdn.microsoft.com/en-us/library/42892f65)">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598135" data-raw-source="[GetUIParentCore](http://msdn.microsoft.com/en-us/library/ms598135)">GetUIParentCore</a></td>
<td><div class="summary">
Returns an alternative logical parent for this element if there is no visual parent.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597469" data-raw-source="[GetValue](http://msdn.microsoft.com/en-us/library/ms597469)">GetValue</a></td>
<td><div class="summary">
Returns the current effective value of a dependency property on this instance of a <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598141" data-raw-source="[GetVisualChild](http://msdn.microsoft.com/en-us/library/ms598141)">GetVisualChild</a></td>
<td><div class="summary">
Overrides <a href="http://msdn.microsoft.com/en-us/library/ms608857" data-raw-source="[GetVisualChild(Int32)](http://msdn.microsoft.com/en-us/library/ms608857)">GetVisualChild(Int32)</a>, and returns a child at the specified index from a collection of child elements.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598915" data-raw-source="[HitTestCore(PointHitTestParameters)](http://msdn.microsoft.com/en-us/library/ms598915)">HitTestCore(PointHitTestParameters)</a></td>
<td><div class="summary">
Implements <a href="http://msdn.microsoft.com/en-us/library/ms608859" data-raw-source="[HitTestCore(PointHitTestParameters)](http://msdn.microsoft.com/en-us/library/ms608859)">HitTestCore(PointHitTestParameters)</a> to supply base element hit testing behavior (returning <a href="http://msdn.microsoft.com/en-us/library/ms619158" data-raw-source="[HitTestResult](http://msdn.microsoft.com/en-us/library/ms619158)">HitTestResult</a>).
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598914" data-raw-source="[HitTestCore(GeometryHitTestParameters)](http://msdn.microsoft.com/en-us/library/ms598914)">HitTestCore(GeometryHitTestParameters)</a></td>
<td><div class="summary">
Implements <a href="http://msdn.microsoft.com/en-us/library/ms608858" data-raw-source="[HitTestCore(GeometryHitTestParameters)](http://msdn.microsoft.com/en-us/library/ms608858)">HitTestCore(GeometryHitTestParameters)</a> to supply base element hit testing behavior (returning <a href="http://msdn.microsoft.com/en-us/library/ms634997" data-raw-source="[GeometryHitTestResult](http://msdn.microsoft.com/en-us/library/ms634997)">GeometryHitTestResult</a>).
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598916" data-raw-source="[InputHitTest](http://msdn.microsoft.com/en-us/library/ms598916)">InputHitTest</a></td>
<td><div class="summary">
Returns the input element within the current element that is at the specified coordinates, relative to the current element&#39;s origin.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598917" data-raw-source="[InvalidateArrange](http://msdn.microsoft.com/en-us/library/ms598917)">InvalidateArrange</a></td>
<td><div class="summary">
Invalidates the arrange state (layout) for the element. After the invalidation, the element will have its layout updated, which will occur asynchronously unless subsequently forced by <a href="http://msdn.microsoft.com/en-us/library/ms599327" data-raw-source="[UpdateLayout](http://msdn.microsoft.com/en-us/library/ms599327)">UpdateLayout</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598918" data-raw-source="[InvalidateMeasure](http://msdn.microsoft.com/en-us/library/ms598918)">InvalidateMeasure</a></td>
<td><div class="summary">
Invalidates the measurement state (layout) for the element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597470" data-raw-source="[InvalidateProperty](http://msdn.microsoft.com/en-us/library/ms597470)">InvalidateProperty</a></td>
<td><div class="summary">
Re-evaluates the effective value for the specified dependency property
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598919" data-raw-source="[InvalidateVisual](http://msdn.microsoft.com/en-us/library/ms598919)">InvalidateVisual</a></td>
<td><div class="summary">
Invalidates the rendering of the element, and forces a complete new layout pass. <a href="http://msdn.microsoft.com/en-us/library/ms599305" data-raw-source="[OnRender(DrawingContext)](http://msdn.microsoft.com/en-us/library/ms599305)">OnRender(DrawingContext)</a> is called after the layout cycle is completed.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608860" data-raw-source="[IsAncestorOf](http://msdn.microsoft.com/en-us/library/ms608860)">IsAncestorOf</a></td>
<td><div class="summary">
Determines whether the visual object is an ancestor of the descendant visual object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608861" data-raw-source="[IsDescendantOf](http://msdn.microsoft.com/en-us/library/ms608861)">IsDescendantOf</a></td>
<td><div class="summary">
Determines whether the visual object is a descendant of the ancestor visual object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598921" data-raw-source="[Measure](http://msdn.microsoft.com/en-us/library/ms598921)">Measure</a></td>
<td><div class="summary">
Updates the <a href="http://msdn.microsoft.com/en-us/library/ms588686" data-raw-source="[DesiredSize](http://msdn.microsoft.com/en-us/library/ms588686)">DesiredSize</a> of a <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>. Parent elements call this method from their own <a href="http://msdn.microsoft.com/en-us/library/ms598920" data-raw-source="[MeasureCore(Size)](http://msdn.microsoft.com/en-us/library/ms598920)">MeasureCore(Size)</a> implementations to form a recursive layout update. Calling this method constitutes the first pass (the &quot;Measure&quot; pass) of a layout update.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598224" data-raw-source="[MeasureCore](http://msdn.microsoft.com/en-us/library/ms598224)">MeasureCore</a></td>
<td><div class="summary">
Implements basic measure-pass layout system behavior for <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598227" data-raw-source="[MeasureOverride](http://msdn.microsoft.com/en-us/library/ms598227)">MeasureOverride</a></td>
<td><div class="summary">
When overridden in a derived class, measures the size in layout required for child elements and determines a size for the <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>-derived class.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a" data-raw-source="[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598231" data-raw-source="[MoveFocus](http://msdn.microsoft.com/en-us/library/ms598231)">MoveFocus</a></td>
<td><div class="summary">
Moves the keyboard focus away from this element and to another element in a provided traversal direction.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598923" data-raw-source="[OnAccessKey](http://msdn.microsoft.com/en-us/library/ms598923)">OnAccessKey</a></td>
<td><div class="summary">
Provides class handling for when an access key that is meaningful for this element is invoked.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598234" data-raw-source="[OnApplyTemplate](http://msdn.microsoft.com/en-us/library/ms598234)">OnApplyTemplate</a></td>
<td><div class="summary">
When overridden in a derived class, is invoked whenever application code or internal processes call <a href="http://msdn.microsoft.com/en-us/library/ms598092" data-raw-source="[ApplyTemplate](http://msdn.microsoft.com/en-us/library/ms598092)">ApplyTemplate</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598924" data-raw-source="[OnChildDesiredSizeChanged](http://msdn.microsoft.com/en-us/library/ms598924)">OnChildDesiredSizeChanged</a></td>
<td><div class="summary">
Supports layout behavior when a child element is resized.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598237" data-raw-source="[OnContextMenuClosing](http://msdn.microsoft.com/en-us/library/ms598237)">OnContextMenuClosing</a></td>
<td><div class="summary">
Invoked whenever an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596552" data-raw-source="[ContextMenuClosing](http://msdn.microsoft.com/en-us/library/ms596552)">ContextMenuClosing</a> routed event reaches this class in its route. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598240" data-raw-source="[OnContextMenuOpening](http://msdn.microsoft.com/en-us/library/ms598240)">OnContextMenuOpening</a></td>
<td><div class="summary">
Invoked whenever an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596554" data-raw-source="[ContextMenuOpening](http://msdn.microsoft.com/en-us/library/ms596554)">ContextMenuOpening</a> routed event reaches this class in its route. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598925" data-raw-source="[OnCreateAutomationPeer](http://msdn.microsoft.com/en-us/library/ms598925)">OnCreateAutomationPeer</a></td>
<td><div class="summary">
Returns class-specific <a href="http://msdn.microsoft.com/en-us/library/ms523415" data-raw-source="[AutomationPeer](http://msdn.microsoft.com/en-us/library/ms523415)">AutomationPeer</a> implementations for the Windows Presentation Foundation (WPF) infrastructure.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598926" data-raw-source="[OnDragEnter](http://msdn.microsoft.com/en-us/library/ms598926)">OnDragEnter</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596509" data-raw-source="[DragEnter](http://msdn.microsoft.com/en-us/library/ms596509)">DragEnter</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598927" data-raw-source="[OnDragLeave](http://msdn.microsoft.com/en-us/library/ms598927)">OnDragLeave</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596511" data-raw-source="[DragLeave](http://msdn.microsoft.com/en-us/library/ms596511)">DragLeave</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598928" data-raw-source="[OnDragOver](http://msdn.microsoft.com/en-us/library/ms598928)">OnDragOver</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596513" data-raw-source="[DragOver](http://msdn.microsoft.com/en-us/library/ms596513)">DragOver</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598929" data-raw-source="[OnDrop](http://msdn.microsoft.com/en-us/library/ms598929)">OnDrop</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596509" data-raw-source="[DragEnter](http://msdn.microsoft.com/en-us/library/ms596509)">DragEnter</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598930" data-raw-source="[OnGiveFeedback](http://msdn.microsoft.com/en-us/library/ms598930)">OnGiveFeedback</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596516" data-raw-source="[GiveFeedback](http://msdn.microsoft.com/en-us/library/ms596516)">GiveFeedback</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598242" data-raw-source="[OnGotFocus](http://msdn.microsoft.com/en-us/library/ms598242)">OnGotFocus</a></td>
<td><div class="summary">
Invoked whenever an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596645" data-raw-source="[GotFocus](http://msdn.microsoft.com/en-us/library/ms596645)">GotFocus</a> event reaches this element in its route.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598932" data-raw-source="[OnGotKeyboardFocus](http://msdn.microsoft.com/en-us/library/ms598932)">OnGotKeyboardFocus</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/aa345917" data-raw-source="[GotKeyboardFocus](http://msdn.microsoft.com/en-us/library/aa345917)">GotKeyboardFocus</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598933" data-raw-source="[OnGotMouseCapture](http://msdn.microsoft.com/en-us/library/ms598933)">OnGotMouseCapture</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523136" data-raw-source="[GotMouseCapture](http://msdn.microsoft.com/en-us/library/ms523136)">GotMouseCapture</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598934" data-raw-source="[OnGotStylusCapture](http://msdn.microsoft.com/en-us/library/ms598934)">OnGotStylusCapture</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523179" data-raw-source="[GotStylusCapture](http://msdn.microsoft.com/en-us/library/ms523179)">GotStylusCapture</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd783579" data-raw-source="[OnGotTouchCapture](http://msdn.microsoft.com/en-us/library/dd783579)">OnGotTouchCapture</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd989297" data-raw-source="[GotTouchCapture](http://msdn.microsoft.com/en-us/library/dd989297)">GotTouchCapture</a> routed event that occurs when a touch is captured to this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598244" data-raw-source="[OnInitialized](http://msdn.microsoft.com/en-us/library/ms598244)">OnInitialized</a></td>
<td><div class="summary">
Raises the <a href="http://msdn.microsoft.com/en-us/library/ms596557" data-raw-source="[Initialized](http://msdn.microsoft.com/en-us/library/ms596557)">Initialized</a> event. This method is invoked whenever <a href="http://msdn.microsoft.com/en-us/library/ms600884" data-raw-source="[IsInitialized](http://msdn.microsoft.com/en-us/library/ms600884)">IsInitialized</a> is set to true internally.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598935" data-raw-source="[OnIsKeyboardFocusedChanged](http://msdn.microsoft.com/en-us/library/ms598935)">OnIsKeyboardFocusedChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596651" data-raw-source="[IsKeyboardFocusedChanged](http://msdn.microsoft.com/en-us/library/ms596651)">IsKeyboardFocusedChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598936" data-raw-source="[OnIsKeyboardFocusWithinChanged](http://msdn.microsoft.com/en-us/library/ms598936)">OnIsKeyboardFocusWithinChanged</a></td>
<td><div class="summary">
Invoked just before the <a href="http://msdn.microsoft.com/en-us/library/ms596652" data-raw-source="[IsKeyboardFocusWithinChanged](http://msdn.microsoft.com/en-us/library/ms596652)">IsKeyboardFocusWithinChanged</a> event is raised by this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599252" data-raw-source="[OnIsMouseCapturedChanged](http://msdn.microsoft.com/en-us/library/ms599252)">OnIsMouseCapturedChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596653" data-raw-source="[IsMouseCapturedChanged](http://msdn.microsoft.com/en-us/library/ms596653)">IsMouseCapturedChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599253" data-raw-source="[OnIsMouseCaptureWithinChanged](http://msdn.microsoft.com/en-us/library/ms599253)">OnIsMouseCaptureWithinChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596654" data-raw-source="[IsMouseCaptureWithinChanged](http://msdn.microsoft.com/en-us/library/ms596654)">IsMouseCaptureWithinChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599254" data-raw-source="[OnIsMouseDirectlyOverChanged](http://msdn.microsoft.com/en-us/library/ms599254)">OnIsMouseDirectlyOverChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596655" data-raw-source="[IsMouseDirectlyOverChanged](http://msdn.microsoft.com/en-us/library/ms596655)">IsMouseDirectlyOverChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599255" data-raw-source="[OnIsStylusCapturedChanged](http://msdn.microsoft.com/en-us/library/ms599255)">OnIsStylusCapturedChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596656" data-raw-source="[IsStylusCapturedChanged](http://msdn.microsoft.com/en-us/library/ms596656)">IsStylusCapturedChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599256" data-raw-source="[OnIsStylusCaptureWithinChanged](http://msdn.microsoft.com/en-us/library/ms599256)">OnIsStylusCaptureWithinChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596657" data-raw-source="[IsStylusCaptureWithinChanged](http://msdn.microsoft.com/en-us/library/ms596657)">IsStylusCaptureWithinChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599257" data-raw-source="[OnIsStylusDirectlyOverChanged](http://msdn.microsoft.com/en-us/library/ms599257)">OnIsStylusDirectlyOverChanged</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596658" data-raw-source="[IsStylusDirectlyOverChanged](http://msdn.microsoft.com/en-us/library/ms596658)">IsStylusDirectlyOverChanged</a> event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599258" data-raw-source="[OnKeyDown](http://msdn.microsoft.com/en-us/library/ms599258)">OnKeyDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523126" data-raw-source="[KeyDown](http://msdn.microsoft.com/en-us/library/ms523126)">KeyDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599259" data-raw-source="[OnKeyUp](http://msdn.microsoft.com/en-us/library/ms599259)">OnKeyUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523129" data-raw-source="[KeyUp](http://msdn.microsoft.com/en-us/library/ms523129)">KeyUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599260" data-raw-source="[OnLostFocus](http://msdn.microsoft.com/en-us/library/ms599260)">OnLostFocus</a></td>
<td><div class="summary">
Raises the <a href="http://msdn.microsoft.com/en-us/library/ms596673" data-raw-source="[LostFocus](http://msdn.microsoft.com/en-us/library/ms596673)">LostFocus</a> routed event by using the event data that is provided.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599261" data-raw-source="[OnLostKeyboardFocus](http://msdn.microsoft.com/en-us/library/ms599261)">OnLostKeyboardFocus</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/aa345918" data-raw-source="[LostKeyboardFocus](http://msdn.microsoft.com/en-us/library/aa345918)">LostKeyboardFocus</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599262" data-raw-source="[OnLostMouseCapture](http://msdn.microsoft.com/en-us/library/ms599262)">OnLostMouseCapture</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523139" data-raw-source="[LostMouseCapture](http://msdn.microsoft.com/en-us/library/ms523139)">LostMouseCapture</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599263" data-raw-source="[OnLostStylusCapture](http://msdn.microsoft.com/en-us/library/ms599263)">OnLostStylusCapture</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523183" data-raw-source="[LostStylusCapture](http://msdn.microsoft.com/en-us/library/ms523183)">LostStylusCapture</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd784514" data-raw-source="[OnLostTouchCapture](http://msdn.microsoft.com/en-us/library/dd784514)">OnLostTouchCapture</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd784505" data-raw-source="[LostTouchCapture](http://msdn.microsoft.com/en-us/library/dd784505)">LostTouchCapture</a> routed event that occurs when this element loses a touch capture.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd549563" data-raw-source="[OnManipulationBoundaryFeedback](http://msdn.microsoft.com/en-us/library/dd549563)">OnManipulationBoundaryFeedback</a></td>
<td><div class="summary">
Called when the <a href="http://msdn.microsoft.com/en-us/library/dd549583" data-raw-source="[ManipulationBoundaryFeedback](http://msdn.microsoft.com/en-us/library/dd549583)">ManipulationBoundaryFeedback</a> event occurs.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd403062" data-raw-source="[OnManipulationCompleted](http://msdn.microsoft.com/en-us/library/dd403062)">OnManipulationCompleted</a></td>
<td><div class="summary">
Called when the <a href="http://msdn.microsoft.com/en-us/library/dd403080" data-raw-source="[ManipulationCompleted](http://msdn.microsoft.com/en-us/library/dd403080)">ManipulationCompleted</a> event occurs.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd403423" data-raw-source="[OnManipulationDelta](http://msdn.microsoft.com/en-us/library/dd403423)">OnManipulationDelta</a></td>
<td><div class="summary">
Called when the <a href="http://msdn.microsoft.com/en-us/library/dd403301" data-raw-source="[ManipulationDelta](http://msdn.microsoft.com/en-us/library/dd403301)">ManipulationDelta</a> event occurs.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd549618" data-raw-source="[OnManipulationInertiaStarting](http://msdn.microsoft.com/en-us/library/dd549618)">OnManipulationInertiaStarting</a></td>
<td><div class="summary">
Called when the <a href="http://msdn.microsoft.com/en-us/library/dd549561" data-raw-source="[ManipulationInertiaStarting](http://msdn.microsoft.com/en-us/library/dd549561)">ManipulationInertiaStarting</a> event occurs.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd403303" data-raw-source="[OnManipulationStarted](http://msdn.microsoft.com/en-us/library/dd403303)">OnManipulationStarted</a></td>
<td><div class="summary">
Called when the <a href="http://msdn.microsoft.com/en-us/library/dd403503" data-raw-source="[ManipulationStarted](http://msdn.microsoft.com/en-us/library/dd403503)">ManipulationStarted</a> event occurs.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd991606" data-raw-source="[OnManipulationStarting](http://msdn.microsoft.com/en-us/library/dd991606)">OnManipulationStarting</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd782370" data-raw-source="[ManipulationStarting](http://msdn.microsoft.com/en-us/library/dd782370)">ManipulationStarting</a> routed event that occurs when the manipulation processor is first created.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599264" data-raw-source="[OnMouseDown](http://msdn.microsoft.com/en-us/library/ms599264)">OnMouseDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523141" data-raw-source="[MouseDown](http://msdn.microsoft.com/en-us/library/ms523141)">MouseDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599265" data-raw-source="[OnMouseEnter](http://msdn.microsoft.com/en-us/library/ms599265)">OnMouseEnter</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523142" data-raw-source="[MouseEnter](http://msdn.microsoft.com/en-us/library/ms523142)">MouseEnter</a> attached event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599266" data-raw-source="[OnMouseLeave](http://msdn.microsoft.com/en-us/library/ms599266)">OnMouseLeave</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523144" data-raw-source="[MouseLeave](http://msdn.microsoft.com/en-us/library/ms523144)">MouseLeave</a> attached event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599267" data-raw-source="[OnMouseLeftButtonDown](http://msdn.microsoft.com/en-us/library/ms599267)">OnMouseLeftButtonDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596680" data-raw-source="[MouseLeftButtonDown](http://msdn.microsoft.com/en-us/library/ms596680)">MouseLeftButtonDown</a> routed event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599268" data-raw-source="[OnMouseLeftButtonUp](http://msdn.microsoft.com/en-us/library/ms599268)">OnMouseLeftButtonUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596681" data-raw-source="[MouseLeftButtonUp](http://msdn.microsoft.com/en-us/library/ms596681)">MouseLeftButtonUp</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599269" data-raw-source="[OnMouseMove](http://msdn.microsoft.com/en-us/library/ms599269)">OnMouseMove</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523146" data-raw-source="[MouseMove](http://msdn.microsoft.com/en-us/library/ms523146)">MouseMove</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599270" data-raw-source="[OnMouseRightButtonDown](http://msdn.microsoft.com/en-us/library/ms599270)">OnMouseRightButtonDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596683" data-raw-source="[MouseRightButtonDown](http://msdn.microsoft.com/en-us/library/ms596683)">MouseRightButtonDown</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599271" data-raw-source="[OnMouseRightButtonUp](http://msdn.microsoft.com/en-us/library/ms599271)">OnMouseRightButtonUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596684" data-raw-source="[MouseRightButtonUp](http://msdn.microsoft.com/en-us/library/ms596684)">MouseRightButtonUp</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599272" data-raw-source="[OnMouseUp](http://msdn.microsoft.com/en-us/library/ms599272)">OnMouseUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523148" data-raw-source="[MouseUp](http://msdn.microsoft.com/en-us/library/ms523148)">MouseUp</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599273" data-raw-source="[OnMouseWheel](http://msdn.microsoft.com/en-us/library/ms599273)">OnMouseWheel</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523151" data-raw-source="[MouseWheel](http://msdn.microsoft.com/en-us/library/ms523151)">MouseWheel</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599274" data-raw-source="[OnPreviewDragEnter](http://msdn.microsoft.com/en-us/library/ms599274)">OnPreviewDragEnter</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596517" data-raw-source="[PreviewDragEnter](http://msdn.microsoft.com/en-us/library/ms596517)">PreviewDragEnter</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599275" data-raw-source="[OnPreviewDragLeave](http://msdn.microsoft.com/en-us/library/ms599275)">OnPreviewDragLeave</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596519" data-raw-source="[PreviewDragLeave](http://msdn.microsoft.com/en-us/library/ms596519)">PreviewDragLeave</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599276" data-raw-source="[OnPreviewDragOver](http://msdn.microsoft.com/en-us/library/ms599276)">OnPreviewDragOver</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596521" data-raw-source="[PreviewDragOver](http://msdn.microsoft.com/en-us/library/ms596521)">PreviewDragOver</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599277" data-raw-source="[OnPreviewDrop](http://msdn.microsoft.com/en-us/library/ms599277)">OnPreviewDrop</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596523" data-raw-source="[PreviewDrop](http://msdn.microsoft.com/en-us/library/ms596523)">PreviewDrop</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599278" data-raw-source="[OnPreviewGiveFeedback](http://msdn.microsoft.com/en-us/library/ms599278)">OnPreviewGiveFeedback</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596525" data-raw-source="[PreviewGiveFeedback](http://msdn.microsoft.com/en-us/library/ms596525)">PreviewGiveFeedback</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599279" data-raw-source="[OnPreviewGotKeyboardFocus](http://msdn.microsoft.com/en-us/library/ms599279)">OnPreviewGotKeyboardFocus</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/aa345919" data-raw-source="[PreviewGotKeyboardFocus](http://msdn.microsoft.com/en-us/library/aa345919)">PreviewGotKeyboardFocus</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599280" data-raw-source="[OnPreviewKeyDown](http://msdn.microsoft.com/en-us/library/ms599280)">OnPreviewKeyDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523131" data-raw-source="[PreviewKeyDown](http://msdn.microsoft.com/en-us/library/ms523131)">PreviewKeyDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599281" data-raw-source="[OnPreviewKeyUp](http://msdn.microsoft.com/en-us/library/ms599281)">OnPreviewKeyUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523134" data-raw-source="[PreviewKeyUp](http://msdn.microsoft.com/en-us/library/ms523134)">PreviewKeyUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599282" data-raw-source="[OnPreviewLostKeyboardFocus](http://msdn.microsoft.com/en-us/library/ms599282)">OnPreviewLostKeyboardFocus</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523131" data-raw-source="[PreviewKeyDown](http://msdn.microsoft.com/en-us/library/ms523131)">PreviewKeyDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599283" data-raw-source="[OnPreviewMouseDown](http://msdn.microsoft.com/en-us/library/ms599283)">OnPreviewMouseDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523154" data-raw-source="[PreviewMouseDown](http://msdn.microsoft.com/en-us/library/ms523154)">PreviewMouseDown</a> attached routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599284" data-raw-source="[OnPreviewMouseLeftButtonDown](http://msdn.microsoft.com/en-us/library/ms599284)">OnPreviewMouseLeftButtonDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596697" data-raw-source="[PreviewMouseLeftButtonDown](http://msdn.microsoft.com/en-us/library/ms596697)">PreviewMouseLeftButtonDown</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599285" data-raw-source="[OnPreviewMouseLeftButtonUp](http://msdn.microsoft.com/en-us/library/ms599285)">OnPreviewMouseLeftButtonUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596698" data-raw-source="[PreviewMouseLeftButtonUp](http://msdn.microsoft.com/en-us/library/ms596698)">PreviewMouseLeftButtonUp</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599286" data-raw-source="[OnPreviewMouseMove](http://msdn.microsoft.com/en-us/library/ms599286)">OnPreviewMouseMove</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523159" data-raw-source="[PreviewMouseMove](http://msdn.microsoft.com/en-us/library/ms523159)">PreviewMouseMove</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599287" data-raw-source="[OnPreviewMouseRightButtonDown](http://msdn.microsoft.com/en-us/library/ms599287)">OnPreviewMouseRightButtonDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596700" data-raw-source="[PreviewMouseRightButtonDown](http://msdn.microsoft.com/en-us/library/ms596700)">PreviewMouseRightButtonDown</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599288" data-raw-source="[OnPreviewMouseRightButtonUp](http://msdn.microsoft.com/en-us/library/ms599288)">OnPreviewMouseRightButtonUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596701" data-raw-source="[PreviewMouseRightButtonUp](http://msdn.microsoft.com/en-us/library/ms596701)">PreviewMouseRightButtonUp</a> routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599289" data-raw-source="[OnPreviewMouseUp](http://msdn.microsoft.com/en-us/library/ms599289)">OnPreviewMouseUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523163" data-raw-source="[PreviewMouseUp](http://msdn.microsoft.com/en-us/library/ms523163)">PreviewMouseUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599290" data-raw-source="[OnPreviewMouseWheel](http://msdn.microsoft.com/en-us/library/ms599290)">OnPreviewMouseWheel</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523168" data-raw-source="[PreviewMouseWheel](http://msdn.microsoft.com/en-us/library/ms523168)">PreviewMouseWheel</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599291" data-raw-source="[OnPreviewQueryContinueDrag](http://msdn.microsoft.com/en-us/library/ms599291)">OnPreviewQueryContinueDrag</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596527" data-raw-source="[PreviewQueryContinueDrag](http://msdn.microsoft.com/en-us/library/ms596527)">PreviewQueryContinueDrag</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599292" data-raw-source="[OnPreviewStylusButtonDown](http://msdn.microsoft.com/en-us/library/ms599292)">OnPreviewStylusButtonDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523186" data-raw-source="[PreviewStylusButtonDown](http://msdn.microsoft.com/en-us/library/ms523186)">PreviewStylusButtonDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599293" data-raw-source="[OnPreviewStylusButtonUp](http://msdn.microsoft.com/en-us/library/ms599293)">OnPreviewStylusButtonUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523189" data-raw-source="[PreviewStylusButtonUp](http://msdn.microsoft.com/en-us/library/ms523189)">PreviewStylusButtonUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599294" data-raw-source="[OnPreviewStylusDown](http://msdn.microsoft.com/en-us/library/ms599294)">OnPreviewStylusDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523193" data-raw-source="[PreviewStylusDown](http://msdn.microsoft.com/en-us/library/ms523193)">PreviewStylusDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599295" data-raw-source="[OnPreviewStylusInAirMove](http://msdn.microsoft.com/en-us/library/ms599295)">OnPreviewStylusInAirMove</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523196" data-raw-source="[PreviewStylusInAirMove](http://msdn.microsoft.com/en-us/library/ms523196)">PreviewStylusInAirMove</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599296" data-raw-source="[OnPreviewStylusInRange](http://msdn.microsoft.com/en-us/library/ms599296)">OnPreviewStylusInRange</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523198" data-raw-source="[PreviewStylusInRange](http://msdn.microsoft.com/en-us/library/ms523198)">PreviewStylusInRange</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599297" data-raw-source="[OnPreviewStylusMove](http://msdn.microsoft.com/en-us/library/ms599297)">OnPreviewStylusMove</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588440" data-raw-source="[PreviewStylusMove](http://msdn.microsoft.com/en-us/library/ms588440)">PreviewStylusMove</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599298" data-raw-source="[OnPreviewStylusOutOfRange](http://msdn.microsoft.com/en-us/library/ms599298)">OnPreviewStylusOutOfRange</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588441" data-raw-source="[PreviewStylusOutOfRange](http://msdn.microsoft.com/en-us/library/ms588441)">PreviewStylusOutOfRange</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599299" data-raw-source="[OnPreviewStylusSystemGesture](http://msdn.microsoft.com/en-us/library/ms599299)">OnPreviewStylusSystemGesture</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588442" data-raw-source="[PreviewStylusSystemGesture](http://msdn.microsoft.com/en-us/library/ms588442)">PreviewStylusSystemGesture</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599300" data-raw-source="[OnPreviewStylusUp](http://msdn.microsoft.com/en-us/library/ms599300)">OnPreviewStylusUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588443" data-raw-source="[PreviewStylusUp](http://msdn.microsoft.com/en-us/library/ms588443)">PreviewStylusUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599301" data-raw-source="[OnPreviewTextInput](http://msdn.microsoft.com/en-us/library/ms599301)">OnPreviewTextInput</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588471" data-raw-source="[PreviewTextInput](http://msdn.microsoft.com/en-us/library/ms588471)">PreviewTextInput</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd992477" data-raw-source="[OnPreviewTouchDown](http://msdn.microsoft.com/en-us/library/dd992477)">OnPreviewTouchDown</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd991743" data-raw-source="[PreviewTouchDown](http://msdn.microsoft.com/en-us/library/dd991743)">PreviewTouchDown</a> routed event that occurs when a touch presses this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd784544" data-raw-source="[OnPreviewTouchMove](http://msdn.microsoft.com/en-us/library/dd784544)">OnPreviewTouchMove</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd990490" data-raw-source="[PreviewTouchMove](http://msdn.microsoft.com/en-us/library/dd990490)">PreviewTouchMove</a> routed event that occurs when a touch moves while inside this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd783493" data-raw-source="[OnPreviewTouchUp](http://msdn.microsoft.com/en-us/library/dd783493)">OnPreviewTouchUp</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd783905" data-raw-source="[PreviewTouchUp](http://msdn.microsoft.com/en-us/library/dd783905)">PreviewTouchUp</a> routed event that occurs when a touch is released inside this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598246" data-raw-source="[OnPropertyChanged](http://msdn.microsoft.com/en-us/library/ms598246)">OnPropertyChanged</a></td>
<td><div class="summary">
Invoked whenever the effective value of any dependency property on this <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a> has been updated. The specific dependency property that changed is reported in the arguments parameter. Overrides <a href="http://msdn.microsoft.com/en-us/library/ms597471" data-raw-source="[OnPropertyChanged(DependencyPropertyChangedEventArgs)](http://msdn.microsoft.com/en-us/library/ms597471)">OnPropertyChanged(DependencyPropertyChangedEventArgs)</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599302" data-raw-source="[OnQueryContinueDrag](http://msdn.microsoft.com/en-us/library/ms599302)">OnQueryContinueDrag</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596529" data-raw-source="[QueryContinueDrag](http://msdn.microsoft.com/en-us/library/ms596529)">QueryContinueDrag</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599303" data-raw-source="[OnQueryCursor](http://msdn.microsoft.com/en-us/library/ms599303)">OnQueryCursor</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms523171" data-raw-source="[QueryCursor](http://msdn.microsoft.com/en-us/library/ms523171)">QueryCursor</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599305" data-raw-source="[OnRender](http://msdn.microsoft.com/en-us/library/ms599305)">OnRender</a></td>
<td><div class="summary">
When overridden in a derived class, participates in rendering operations that are directed by the layout system. The rendering instructions for this element are not used directly when this method is invoked, and are instead preserved for later asynchronous use by layout and drawing.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598248" data-raw-source="[OnRenderSizeChanged](http://msdn.microsoft.com/en-us/library/ms598248)">OnRenderSizeChanged</a></td>
<td><div class="summary">
Raises the <a href="http://msdn.microsoft.com/en-us/library/ms596560" data-raw-source="[SizeChanged](http://msdn.microsoft.com/en-us/library/ms596560)">SizeChanged</a> event, using the specified information as part of the eventual event data.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598251" data-raw-source="[OnStyleChanged](http://msdn.microsoft.com/en-us/library/ms598251)">OnStyleChanged</a></td>
<td><div class="summary">
Invoked when the style in use on this element changes, which will invalidate the layout.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599306" data-raw-source="[OnStylusButtonDown](http://msdn.microsoft.com/en-us/library/ms599306)">OnStylusButtonDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588445" data-raw-source="[StylusButtonDown](http://msdn.microsoft.com/en-us/library/ms588445)">StylusButtonDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599307" data-raw-source="[OnStylusButtonUp](http://msdn.microsoft.com/en-us/library/ms599307)">OnStylusButtonUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588446" data-raw-source="[StylusButtonUp](http://msdn.microsoft.com/en-us/library/ms588446)">StylusButtonUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599308" data-raw-source="[OnStylusDown](http://msdn.microsoft.com/en-us/library/ms599308)">OnStylusDown</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588447" data-raw-source="[StylusDown](http://msdn.microsoft.com/en-us/library/ms588447)">StylusDown</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599309" data-raw-source="[OnStylusEnter](http://msdn.microsoft.com/en-us/library/ms599309)">OnStylusEnter</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588448" data-raw-source="[StylusEnter](http://msdn.microsoft.com/en-us/library/ms588448)">StylusEnter</a> attached event is raised by this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599310" data-raw-source="[OnStylusInAirMove](http://msdn.microsoft.com/en-us/library/ms599310)">OnStylusInAirMove</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588449" data-raw-source="[StylusInAirMove](http://msdn.microsoft.com/en-us/library/ms588449)">StylusInAirMove</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599311" data-raw-source="[OnStylusInRange](http://msdn.microsoft.com/en-us/library/ms599311)">OnStylusInRange</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588450" data-raw-source="[StylusInRange](http://msdn.microsoft.com/en-us/library/ms588450)">StylusInRange</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599312" data-raw-source="[OnStylusLeave](http://msdn.microsoft.com/en-us/library/ms599312)">OnStylusLeave</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588452" data-raw-source="[StylusLeave](http://msdn.microsoft.com/en-us/library/ms588452)">StylusLeave</a> attached event is raised by this element. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599313" data-raw-source="[OnStylusMove](http://msdn.microsoft.com/en-us/library/ms599313)">OnStylusMove</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588455" data-raw-source="[StylusMove](http://msdn.microsoft.com/en-us/library/ms588455)">StylusMove</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599314" data-raw-source="[OnStylusOutOfRange](http://msdn.microsoft.com/en-us/library/ms599314)">OnStylusOutOfRange</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588460" data-raw-source="[StylusOutOfRange](http://msdn.microsoft.com/en-us/library/ms588460)">StylusOutOfRange</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599315" data-raw-source="[OnStylusSystemGesture](http://msdn.microsoft.com/en-us/library/ms599315)">OnStylusSystemGesture</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588464" data-raw-source="[StylusSystemGesture](http://msdn.microsoft.com/en-us/library/ms588464)">StylusSystemGesture</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599316" data-raw-source="[OnStylusUp](http://msdn.microsoft.com/en-us/library/ms599316)">OnStylusUp</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms588467" data-raw-source="[StylusUp](http://msdn.microsoft.com/en-us/library/ms588467)">StylusUp</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599317" data-raw-source="[OnTextInput](http://msdn.microsoft.com/en-us/library/ms599317)">OnTextInput</a></td>
<td><div class="summary">
Invoked when an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms601826" data-raw-source="[TextInput](http://msdn.microsoft.com/en-us/library/ms601826)">TextInput</a> attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598255" data-raw-source="[OnToolTipClosing](http://msdn.microsoft.com/en-us/library/ms598255)">OnToolTipClosing</a></td>
<td><div class="summary">
Invoked whenever an unhandled <a href="http://msdn.microsoft.com/en-us/library/ms596563" data-raw-source="[ToolTipClosing](http://msdn.microsoft.com/en-us/library/ms596563)">ToolTipClosing</a> routed event reaches this class in its route. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598256" data-raw-source="[OnToolTipOpening](http://msdn.microsoft.com/en-us/library/ms598256)">OnToolTipOpening</a></td>
<td><div class="summary">
Invoked whenever the <a href="http://msdn.microsoft.com/en-us/library/ms596564" data-raw-source="[ToolTipOpening](http://msdn.microsoft.com/en-us/library/ms596564)">ToolTipOpening</a> routed event reaches this class in its route. Implement this method to add class handling for this event.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd991371" data-raw-source="[OnTouchDown](http://msdn.microsoft.com/en-us/library/dd991371)">OnTouchDown</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd782616" data-raw-source="[TouchDown](http://msdn.microsoft.com/en-us/library/dd782616)">TouchDown</a> routed event that occurs when a touch presses inside this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd782614" data-raw-source="[OnTouchEnter](http://msdn.microsoft.com/en-us/library/dd782614)">OnTouchEnter</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd990673" data-raw-source="[TouchEnter](http://msdn.microsoft.com/en-us/library/dd990673)">TouchEnter</a> routed event that occurs when a touch moves from outside to inside the bounds of this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd782894" data-raw-source="[OnTouchLeave](http://msdn.microsoft.com/en-us/library/dd782894)">OnTouchLeave</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd991524" data-raw-source="[TouchLeave](http://msdn.microsoft.com/en-us/library/dd991524)">TouchLeave</a> routed event that occurs when a touch moves from inside to outside the bounds of this <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd783255" data-raw-source="[OnTouchMove](http://msdn.microsoft.com/en-us/library/dd783255)">OnTouchMove</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd991311" data-raw-source="[TouchMove](http://msdn.microsoft.com/en-us/library/dd991311)">TouchMove</a> routed event that occurs when a touch moves while inside this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd992297" data-raw-source="[OnTouchUp](http://msdn.microsoft.com/en-us/library/dd992297)">OnTouchUp</a></td>
<td><div class="summary">
Provides class handling for the <a href="http://msdn.microsoft.com/en-us/library/dd991789" data-raw-source="[TouchUp](http://msdn.microsoft.com/en-us/library/dd991789)">TouchUp</a> routed event that occurs when a touch is released inside this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608862" data-raw-source="[OnVisualChildrenChanged](http://msdn.microsoft.com/en-us/library/ms608862)">OnVisualChildrenChanged</a></td>
<td><div class="summary">
Called when the <a href="http://msdn.microsoft.com/en-us/library/ms635644" data-raw-source="[VisualCollection](http://msdn.microsoft.com/en-us/library/ms635644)">VisualCollection</a> of the visual object is modified.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598258" data-raw-source="[OnVisualParentChanged](http://msdn.microsoft.com/en-us/library/ms598258)">OnVisualParentChanged</a></td>
<td><div class="summary">
Invoked when the parent of this element in the visual tree is changed. Overrides <a href="http://msdn.microsoft.com/en-us/library/ms599318" data-raw-source="[OnVisualParentChanged(DependencyObject)](http://msdn.microsoft.com/en-us/library/ms599318)">OnVisualParentChanged(DependencyObject)</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598260" data-raw-source="[ParentLayoutInvalidated](http://msdn.microsoft.com/en-us/library/ms598260)">ParentLayoutInvalidated</a></td>
<td><div class="summary">
Supports incremental layout implementations in specialized subclasses of <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>. <a href="http://msdn.microsoft.com/en-us/library/ms598260" data-raw-source="[ParentLayoutInvalidated(UIElement)](http://msdn.microsoft.com/en-us/library/ms598260)">ParentLayoutInvalidated(UIElement)</a> is invoked when a child element has invalidated a property that is marked in metadata as affecting the parent&#39;s measure or arrange passes during layout.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/aa346960" data-raw-source="[PointFromScreen](http://msdn.microsoft.com/en-us/library/aa346960)">PointFromScreen</a></td>
<td><div class="summary">
Converts a <a href="http://msdn.microsoft.com/en-us/library/ms602977" data-raw-source="[Point](http://msdn.microsoft.com/en-us/library/ms602977)">Point</a> in screen coordinates into a <a href="http://msdn.microsoft.com/en-us/library/ms602977" data-raw-source="[Point](http://msdn.microsoft.com/en-us/library/ms602977)">Point</a> that represents the current coordinate system of the <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/aa346961" data-raw-source="[PointToScreen](http://msdn.microsoft.com/en-us/library/aa346961)">PointToScreen</a></td>
<td><div class="summary">
Converts a <a href="http://msdn.microsoft.com/en-us/library/ms602977" data-raw-source="[Point](http://msdn.microsoft.com/en-us/library/ms602977)">Point</a> that represents the current coordinate system of the <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a> into a <a href="http://msdn.microsoft.com/en-us/library/ms602977" data-raw-source="[Point](http://msdn.microsoft.com/en-us/library/ms602977)">Point</a> in screen coordinates.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598263" data-raw-source="[PredictFocus](http://msdn.microsoft.com/en-us/library/ms598263)">PredictFocus</a></td>
<td><div class="summary">
Determines the next element that would receive focus relative to this element for a provided focus movement direction, but does not actually move the focus.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599320" data-raw-source="[RaiseEvent](http://msdn.microsoft.com/en-us/library/ms599320)">RaiseEvent</a></td>
<td><div class="summary">
Raises a specific routed event. The <a href="http://msdn.microsoft.com/en-us/library/ms589739" data-raw-source="[RoutedEvent](http://msdn.microsoft.com/en-us/library/ms589739)">RoutedEvent</a> to be raised is identified within the <a href="http://msdn.microsoft.com/en-us/library/ms589740" data-raw-source="[RoutedEventArgs](http://msdn.microsoft.com/en-us/library/ms589740)">RoutedEventArgs</a> instance that is provided (as the <a href="http://msdn.microsoft.com/en-us/library/ms601234" data-raw-source="[RoutedEvent](http://msdn.microsoft.com/en-us/library/ms601234)">RoutedEvent</a> property of that event data).
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597472" data-raw-source="[ReadLocalValue](http://msdn.microsoft.com/en-us/library/ms597472)">ReadLocalValue</a></td>
<td><div class="summary">
Returns the local value of a dependency property, if it exists.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598265" data-raw-source="[RegisterName](http://msdn.microsoft.com/en-us/library/ms598265)">RegisterName</a></td>
<td><div class="summary">
Provides an accessor that simplifies access to the <a href="http://msdn.microsoft.com/en-us/library/ms602968" data-raw-source="[NameScope](http://msdn.microsoft.com/en-us/library/ms602968)">NameScope</a> registration method.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd783351" data-raw-source="[ReleaseAllTouchCaptures](http://msdn.microsoft.com/en-us/library/dd783351)">ReleaseAllTouchCaptures</a></td>
<td><div class="summary">
Releases all captured touch devices from this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599321" data-raw-source="[ReleaseMouseCapture](http://msdn.microsoft.com/en-us/library/ms599321)">ReleaseMouseCapture</a></td>
<td><div class="summary">
Releases the mouse capture, if this element held the capture.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599322" data-raw-source="[ReleaseStylusCapture](http://msdn.microsoft.com/en-us/library/ms599322)">ReleaseStylusCapture</a></td>
<td><div class="summary">
Releases the stylus device capture, if this element held the capture.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd990535" data-raw-source="[ReleaseTouchCapture](http://msdn.microsoft.com/en-us/library/dd990535)">ReleaseTouchCapture</a></td>
<td><div class="summary">
Attempts to release the specified touch device from this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599323" data-raw-source="[RemoveHandler](http://msdn.microsoft.com/en-us/library/ms599323)">RemoveHandler</a></td>
<td><div class="summary">
Removes the specified routed event handler from this element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598268" data-raw-source="[RemoveLogicalChild](http://msdn.microsoft.com/en-us/library/ms598268)">RemoveLogicalChild</a></td>
<td><div class="summary">
Removes the provided object from this element&#39;s logical tree. <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a> updates the affected logical tree parent pointers to keep in sync with this deletion.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608864" data-raw-source="[RemoveVisualChild](http://msdn.microsoft.com/en-us/library/ms608864)">RemoveVisualChild</a></td>
<td><div class="summary">
Removes the parent-child relationship between two visuals.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598273" data-raw-source="[SetBinding(DependencyProperty, BindingBase)](http://msdn.microsoft.com/en-us/library/ms598273)">SetBinding(DependencyProperty, BindingBase)</a></td>
<td><div class="summary">
Attaches a binding to this element, based on the provided binding object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms598270" data-raw-source="[SetBinding(DependencyProperty, String)](http://msdn.microsoft.com/en-us/library/ms598270)">SetBinding(DependencyProperty, String)</a></td>
<td><div class="summary">
Attaches a binding to this element, based on the provided source property name as a path qualification to the data source.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd549644" data-raw-source="[SetCurrentValue](http://msdn.microsoft.com/en-us/library/dd549644)">SetCurrentValue</a></td>
<td><div class="summary">
Sets the value of a dependency property without changing its value source.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557690" data-raw-source="[SetResourceReference](http://msdn.microsoft.com/en-us/library/ms557690)">SetResourceReference</a></td>
<td><div class="summary">
Searches for a resource with the specified name and sets up a resource reference to it for the specified property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597473" data-raw-source="[SetValue(DependencyProperty, Object)](http://msdn.microsoft.com/en-us/library/ms597473)">SetValue(DependencyProperty, Object)</a></td>
<td><div class="summary">
Sets the local value of a dependency property, specified by its dependency property identifier.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597474" data-raw-source="[SetValue(DependencyPropertyKey, Object)](http://msdn.microsoft.com/en-us/library/ms597474)">SetValue(DependencyPropertyKey, Object)</a></td>
<td><div class="summary">
Sets the local value of a read-only dependency property, specified by the <a href="http://msdn.microsoft.com/en-us/library/ms602348" data-raw-source="[DependencyPropertyKey](http://msdn.microsoft.com/en-us/library/ms602348)">DependencyPropertyKey</a> identifier of the dependency property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599324" data-raw-source="[ShouldSerializeCommandBindings](http://msdn.microsoft.com/en-us/library/ms599324)">ShouldSerializeCommandBindings</a></td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the <a href="http://msdn.microsoft.com/en-us/library/ms588680" data-raw-source="[CommandBindings](http://msdn.microsoft.com/en-us/library/ms588680)">CommandBindings</a> property on instances of this class.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599325" data-raw-source="[ShouldSerializeInputBindings](http://msdn.microsoft.com/en-us/library/ms599325)">ShouldSerializeInputBindings</a></td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the <a href="http://msdn.microsoft.com/en-us/library/ms588692" data-raw-source="[InputBindings](http://msdn.microsoft.com/en-us/library/ms588692)">InputBindings</a> property on instances of this class.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms597475" data-raw-source="[ShouldSerializeProperty](http://msdn.microsoft.com/en-us/library/ms597475)">ShouldSerializeProperty</a></td>
<td><div class="summary">
Returns a value that indicates whether serialization processes should serialize the value for the provided dependency property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms589309" data-raw-source="[DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)">DependencyObject</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557692" data-raw-source="[ShouldSerializeResources](http://msdn.microsoft.com/en-us/library/ms557692)">ShouldSerializeResources</a></td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the <a href="http://msdn.microsoft.com/en-us/library/ms600898" data-raw-source="[Resources](http://msdn.microsoft.com/en-us/library/ms600898)">Resources</a> property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557694" data-raw-source="[ShouldSerializeStyle](http://msdn.microsoft.com/en-us/library/ms557694)">ShouldSerializeStyle</a></td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the <a href="http://msdn.microsoft.com/en-us/library/ms600899" data-raw-source="[Style](http://msdn.microsoft.com/en-us/library/ms600899)">Style</a> property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557696" data-raw-source="[ShouldSerializeTriggers](http://msdn.microsoft.com/en-us/library/ms557696)">ShouldSerializeTriggers</a></td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the <a href="http://msdn.microsoft.com/en-us/library/ms600903" data-raw-source="[Triggers](http://msdn.microsoft.com/en-us/library/ms600903)">Triggers</a> property.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2" data-raw-source="[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608865" data-raw-source="[TransformToAncestor(Visual)](http://msdn.microsoft.com/en-us/library/ms608865)">TransformToAncestor(Visual)</a></td>
<td><div class="summary">
Returns a transform that can be used to transform coordinates from the <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a> to the specified <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a> ancestor of the visual object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bb763975" data-raw-source="[TransformToAncestor(Visual3D)](http://msdn.microsoft.com/en-us/library/bb763975)">TransformToAncestor(Visual3D)</a></td>
<td><div class="summary">
Returns a transform that can be used to transform coordinates from the <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a> to the specified <a href="http://msdn.microsoft.com/en-us/library/ms594932" data-raw-source="[Visual3D](http://msdn.microsoft.com/en-us/library/ms594932)">Visual3D</a> ancestor of the visual object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608866" data-raw-source="[TransformToDescendant](http://msdn.microsoft.com/en-us/library/ms608866)">TransformToDescendant</a></td>
<td><div class="summary">
Returns a transform that can be used to transform coordinates from the <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a> to the specified visual object descendant.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms608867" data-raw-source="[TransformToVisual](http://msdn.microsoft.com/en-us/library/ms608867)">TransformToVisual</a></td>
<td><div class="summary">
Returns a transform that can be used to transform coordinates from the <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a> to the specified visual object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms635637" data-raw-source="[Visual](http://msdn.microsoft.com/en-us/library/ms635637)">Visual</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599326" data-raw-source="[TranslatePoint](http://msdn.microsoft.com/en-us/library/ms599326)">TranslatePoint</a></td>
<td><div class="summary">
Translates a point relative to this element to coordinates that are relative to the specified element.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557698" data-raw-source="[TryFindResource](http://msdn.microsoft.com/en-us/library/ms557698)">TryFindResource</a></td>
<td><div class="summary">
Searches for a resource with the specified key, and returns that resource if found.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms557700" data-raw-source="[UnregisterName](http://msdn.microsoft.com/en-us/library/ms557700)">UnregisterName</a></td>
<td><div class="summary">
Simplifies access to the <a href="http://msdn.microsoft.com/en-us/library/ms602968" data-raw-source="[NameScope](http://msdn.microsoft.com/en-us/library/ms602968)">NameScope</a> de-registration method.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/hh534717" data-raw-source="[UpdateDefaultStyle](http://msdn.microsoft.com/en-us/library/hh534717)">UpdateDefaultStyle</a></td>
<td><div class="summary">
Reapplies the default style to the current <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms602714" data-raw-source="[FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)">FrameworkElement</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms599327" data-raw-source="[UpdateLayout](http://msdn.microsoft.com/en-us/library/ms599327)">UpdateLayout</a></td>
<td><div class="summary">
Ensures that all visual child elements of this element are properly updated for layout.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms590078" data-raw-source="[UIElement](http://msdn.microsoft.com/en-us/library/ms590078)">UIElement</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms591169" data-raw-source="[VerifyAccess](http://msdn.microsoft.com/en-us/library/ms591169)">VerifyAccess</a></td>
<td><div class="summary">
Enforces that the calling thread has access to this <a href="http://msdn.microsoft.com/en-us/library/ms615925" data-raw-source="[DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925)">DispatcherObject</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms615925" data-raw-source="[DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925)">DispatcherObject</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[ObservableObject(Of T) Class](/patterns-practices/reference/observableobject-t-class-mspp)  
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)  