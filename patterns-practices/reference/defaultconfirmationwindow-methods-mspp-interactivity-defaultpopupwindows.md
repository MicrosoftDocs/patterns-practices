---
TOCTitle: DefaultConfirmationWindow Methods
Title: 'DefaultConfirmationWindow Methods (Microsoft.Practices.Prism.Interactivity.DefaultPopupWindows)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Interactivity.DefaultPopupWindows.DefaultConfirmationWindow'
ms:mtpsurl: 'defaultconfirmationwindow-methods-mspp-interactivity-defaultpopupwindows.md'
---


# DefaultConfirmationWindow Methods

The [DefaultConfirmationWindow](/patterns-practices/reference/defaultconfirmationwindow-class-mspp-interactivity-defaultpopupwindows) type exposes the following members.

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
<td>[Activate](http://msdn.microsoft.com/en-us/library/ms599695)</td>
<td><div class="summary">
Attempts to bring the window to the foreground and activates it.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[AddChild](http://msdn.microsoft.com/en-us/library/ms588611)</td>
<td><div class="summary">
Adds a specified object as the child of a [ContentControl](http://msdn.microsoft.com/en-us/library/ms609797).
</div>
(Inherited from [ContentControl](http://msdn.microsoft.com/en-us/library/ms609797).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddHandler(RoutedEvent, Delegate)](http://msdn.microsoft.com/en-us/library/ms598898)</td>
<td><div class="summary">
Adds a routed event handler for a specified routed event, adding the handler to the handler collection on the current element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddHandler(RoutedEvent, Delegate, Boolean)](http://msdn.microsoft.com/en-us/library/ms598899)</td>
<td><div class="summary">
Adds a routed event handler for a specified routed event, adding the handler to the handler collection on the current element. Specify handledEventsToo as true to have the provided handler be invoked for routed event that had already been marked as handled by another element along the event route.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[AddLogicalChild](http://msdn.microsoft.com/en-us/library/ms598090)</td>
<td><div class="summary">
Adds the provided object to the logical tree of this element.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[AddText](http://msdn.microsoft.com/en-us/library/ms588612)</td>
<td><div class="summary">
Adds a specified text string to a [ContentControl](http://msdn.microsoft.com/en-us/library/ms609797).
</div>
(Inherited from [ContentControl](http://msdn.microsoft.com/en-us/library/ms609797).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[AddToEventRoute](http://msdn.microsoft.com/en-us/library/ms598900)</td>
<td><div class="summary">
Adds handlers to the specified [EventRoute](http://msdn.microsoft.com/en-us/library/ms602393) for the current [UIElement](http://msdn.microsoft.com/en-us/library/ms590078) event handler collection.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[AddVisualChild](http://msdn.microsoft.com/en-us/library/ms608754)</td>
<td><div class="summary">
Defines the parent-child relationship between two visuals.
</div>
(Inherited from [Visual](http://msdn.microsoft.com/en-us/library/ms635637).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ApplyAnimationClock(DependencyProperty, AnimationClock)](http://msdn.microsoft.com/en-us/library/ms598901)</td>
<td><div class="summary">
Applies an animation to a specified dependency property on this element. Any existing animations are stopped and replaced with the new animation.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ApplyAnimationClock(DependencyProperty, AnimationClock, HandoffBehavior)](http://msdn.microsoft.com/en-us/library/ms598902)</td>
<td><div class="summary">
Applies an animation to a specified dependency property on this element, with the ability to specify what happens if the property already has a running animation.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ApplyTemplate](http://msdn.microsoft.com/en-us/library/ms598092)</td>
<td><div class="summary">
Builds the current template's visual tree if necessary, and returns a value that indicates whether the visual tree was rebuilt by this call.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Arrange](http://msdn.microsoft.com/en-us/library/ms598904)</td>
<td><div class="summary">
Positions child elements and determines a size for a [UIElement](http://msdn.microsoft.com/en-us/library/ms590078). Parent elements call this method from their [ArrangeCore(Rect)](http://msdn.microsoft.com/en-us/library/ms598903) implementation (or a WPF framework-level equivalent) to form a recursive layout update. This method constitutes the second pass of a layout update.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ArrangeCore](http://msdn.microsoft.com/en-us/library/ms598095)</td>
<td><div class="summary">
Implements [ArrangeCore(Rect)](http://msdn.microsoft.com/en-us/library/ms598903) (defined as virtual in [UIElement](http://msdn.microsoft.com/en-us/library/ms590078)) and seals the implementation.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ArrangeOverride](http://msdn.microsoft.com/en-us/library/ms599696)</td>
<td><div class="summary">
Override this method to arrange and size a window and its child elements.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[BeginAnimation(DependencyProperty, AnimationTimeline)](http://msdn.microsoft.com/en-us/library/ms598906)</td>
<td><div class="summary">
Starts an animation for a specified animated property on this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[BeginAnimation(DependencyProperty, AnimationTimeline, HandoffBehavior)](http://msdn.microsoft.com/en-us/library/ms598905)</td>
<td><div class="summary">
Starts a specific animation for a specified animated property on this element, with the option of specifying what happens if the property already has a running animation.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[BeginInit](http://msdn.microsoft.com/en-us/library/ms598100)</td>
<td><div class="summary">
Starts the initialization process for this element.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[BeginStoryboard(Storyboard)](http://msdn.microsoft.com/en-us/library/ms598106)</td>
<td><div class="summary">
Begins the sequence of actions that are contained in the provided storyboard.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[BeginStoryboard(Storyboard, HandoffBehavior)](http://msdn.microsoft.com/en-us/library/ms598109)</td>
<td><div class="summary">
Begins the sequence of actions contained in the provided storyboard, with options specified for what should happen if the property is already animated.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[BeginStoryboard(Storyboard, HandoffBehavior, Boolean)](http://msdn.microsoft.com/en-us/library/ms598103)</td>
<td><div class="summary">
Begins the sequence of actions contained in the provided storyboard, with specified state for control of the animation after it is started.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[BringIntoView](http://msdn.microsoft.com/en-us/library/ms598110)</td>
<td><div class="summary">
Attempts to bring this element into view, within any scrollable regions it is contained within.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[BringIntoView(Rect)](http://msdn.microsoft.com/en-us/library/ms598115)</td>
<td><div class="summary">
Attempts to bring the provided region size of this element into view, within any scrollable regions it is contained within.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CaptureMouse](http://msdn.microsoft.com/en-us/library/ms598907)</td>
<td><div class="summary">
Attempts to force capture of the mouse to this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CaptureStylus](http://msdn.microsoft.com/en-us/library/ms598908)</td>
<td><div class="summary">
Attempts to force capture of the stylus to this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CaptureTouch](http://msdn.microsoft.com/en-us/library/dd992299)</td>
<td><div class="summary">
Attempts to force capture of a touch to this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
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
<td>[Close](http://msdn.microsoft.com/en-us/library/ms599697)</td>
<td><div class="summary">
Manually closes a [Window](http://msdn.microsoft.com/en-us/library/ms590112).
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
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
<td>[DragMove](http://msdn.microsoft.com/en-us/library/ms599698)</td>
<td><div class="summary">
Allows a window to be dragged by a mouse with its left button down over an exposed area of the window's client area.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[EndInit](http://msdn.microsoft.com/en-us/library/ms598118)</td>
<td><div class="summary">
Indicates that the initialization process for the element is complete.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
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
<td>[FindCommonVisualAncestor](http://msdn.microsoft.com/en-us/library/ms608755)</td>
<td><div class="summary">
Returns the common ancestor of two visual objects.
</div>
(Inherited from [Visual](http://msdn.microsoft.com/en-us/library/ms635637).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[FindName](http://msdn.microsoft.com/en-us/library/ms598120)</td>
<td><div class="summary">
Finds an element that has the provided identifier name.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[FindResource](http://msdn.microsoft.com/en-us/library/ms598123)</td>
<td><div class="summary">
Searches for a resource with the specified key, and throws an exception if the requested resource is not found.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Focus](http://msdn.microsoft.com/en-us/library/ms598909)</td>
<td><div class="summary">
Attempts to set focus to this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetAnimationBaseValue](http://msdn.microsoft.com/en-us/library/ms598910)</td>
<td><div class="summary">
Returns the base property value for the specified property on this element, disregarding any possible animated value from a running or stopped animation.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetBindingExpression](http://msdn.microsoft.com/en-us/library/ms598124)</td>
<td><div class="summary">
Returns the [BindingExpression](http://msdn.microsoft.com/en-us/library/ms613455) that represents the binding on the specified property.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
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
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[GetLayoutClip](http://msdn.microsoft.com/en-us/library/ms598129)</td>
<td><div class="summary">
Returns a geometry for a clipping mask. The mask applies if the layout system attempts to arrange an element that is larger than the available display space.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetLocalValueEnumerator](http://msdn.microsoft.com/en-us/library/ms597467)</td>
<td><div class="summary">
Creates a specialized enumerator for determining which dependency properties have locally set values on this [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[GetTemplateChild](http://msdn.microsoft.com/en-us/library/ms598132)</td>
<td><div class="summary">
Returns the named element in the visual tree of an instantiated [ControlTemplate](http://msdn.microsoft.com/en-us/library/ms609827).
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
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
<td>[GetUIParentCore](http://msdn.microsoft.com/en-us/library/ms598135)</td>
<td><div class="summary">
Returns an alternative logical parent for this element if there is no visual parent.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetValue](http://msdn.microsoft.com/en-us/library/ms597469)</td>
<td><div class="summary">
Returns the current effective value of a dependency property on this instance of a [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[GetVisualChild](http://msdn.microsoft.com/en-us/library/ms598141)</td>
<td><div class="summary">
Overrides [GetVisualChild(Int32)](http://msdn.microsoft.com/en-us/library/ms608857), and returns a child at the specified index from a collection of child elements.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Hide](http://msdn.microsoft.com/en-us/library/ms599700)</td>
<td><div class="summary">
Makes a window invisible.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[HitTestCore(PointHitTestParameters)](http://msdn.microsoft.com/en-us/library/ms598915)</td>
<td><div class="summary">
Implements [HitTestCore(PointHitTestParameters)](http://msdn.microsoft.com/en-us/library/ms608859) to supply base element hit testing behavior (returning [HitTestResult](http://msdn.microsoft.com/en-us/library/ms619158)).
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[HitTestCore(GeometryHitTestParameters)](http://msdn.microsoft.com/en-us/library/ms598914)</td>
<td><div class="summary">
Implements [HitTestCore(GeometryHitTestParameters)](http://msdn.microsoft.com/en-us/library/ms608858) to supply base element hit testing behavior (returning [GeometryHitTestResult](http://msdn.microsoft.com/en-us/library/ms634997)).
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[InitializeComponent](https://msdn.microsoft.com/library/microsoft.practices.prism.interactivity.defaultpopupwindows.defaultconfirmationwindow.initializecomponent)</td>
<td><div class="summary">
InitializeComponent
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[InputHitTest](http://msdn.microsoft.com/en-us/library/ms598916)</td>
<td><div class="summary">
Returns the input element within the current element that is at the specified coordinates, relative to the current element's origin.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[InvalidateArrange](http://msdn.microsoft.com/en-us/library/ms598917)</td>
<td><div class="summary">
Invalidates the arrange state (layout) for the element. After the invalidation, the element will have its layout updated, which will occur asynchronously unless subsequently forced by [UpdateLayout](http://msdn.microsoft.com/en-us/library/ms599327).
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[InvalidateMeasure](http://msdn.microsoft.com/en-us/library/ms598918)</td>
<td><div class="summary">
Invalidates the measurement state (layout) for the element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[InvalidateProperty](http://msdn.microsoft.com/en-us/library/ms597470)</td>
<td><div class="summary">
Re-evaluates the effective value for the specified dependency property
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[InvalidateVisual](http://msdn.microsoft.com/en-us/library/ms598919)</td>
<td><div class="summary">
Invalidates the rendering of the element, and forces a complete new layout pass. [OnRender(DrawingContext)](http://msdn.microsoft.com/en-us/library/ms599305) is called after the layout cycle is completed.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[IsAncestorOf](http://msdn.microsoft.com/en-us/library/ms608860)</td>
<td><div class="summary">
Determines whether the visual object is an ancestor of the descendant visual object.
</div>
(Inherited from [Visual](http://msdn.microsoft.com/en-us/library/ms635637).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[IsDescendantOf](http://msdn.microsoft.com/en-us/library/ms608861)</td>
<td><div class="summary">
Determines whether the visual object is a descendant of the ancestor visual object.
</div>
(Inherited from [Visual](http://msdn.microsoft.com/en-us/library/ms635637).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Measure](http://msdn.microsoft.com/en-us/library/ms598921)</td>
<td><div class="summary">
Updates the [DesiredSize](http://msdn.microsoft.com/en-us/library/ms588686) of a [UIElement](http://msdn.microsoft.com/en-us/library/ms590078). Parent elements call this method from their own [MeasureCore(Size)](http://msdn.microsoft.com/en-us/library/ms598920) implementations to form a recursive layout update. Calling this method constitutes the first pass (the &quot;Measure&quot; pass) of a layout update.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MeasureCore](http://msdn.microsoft.com/en-us/library/ms598224)</td>
<td><div class="summary">
Implements basic measure-pass layout system behavior for [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MeasureOverride](http://msdn.microsoft.com/en-us/library/ms599701)</td>
<td><div class="summary">
Override this method to measure the size of a window.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[MoveFocus](http://msdn.microsoft.com/en-us/library/ms598231)</td>
<td><div class="summary">
Moves the keyboard focus away from this element and to another element in a provided traversal direction.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnAccessKey](http://msdn.microsoft.com/en-us/library/ms598923)</td>
<td><div class="summary">
Provides class handling for when an access key that is meaningful for this element is invoked.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnActivated](http://msdn.microsoft.com/en-us/library/ms599702)</td>
<td><div class="summary">
Raises the [Activated](http://msdn.microsoft.com/en-us/library/ms596796) event.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[OnApplyTemplate](http://msdn.microsoft.com/en-us/library/ms598234)</td>
<td><div class="summary">
When overridden in a derived class, is invoked whenever application code or internal processes call [ApplyTemplate](http://msdn.microsoft.com/en-us/library/ms598092).
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnChildDesiredSizeChanged](http://msdn.microsoft.com/en-us/library/ms598924)</td>
<td><div class="summary">
Supports layout behavior when a child element is resized.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnClosed](http://msdn.microsoft.com/en-us/library/ms599703)</td>
<td><div class="summary">
Raises the [Closed](http://msdn.microsoft.com/en-us/library/ms596797) event.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnClosing](http://msdn.microsoft.com/en-us/library/ms599704)</td>
<td><div class="summary">
Raises the [Closing](http://msdn.microsoft.com/en-us/library/ms596798) event.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnContentChanged](http://msdn.microsoft.com/en-us/library/ms599705)</td>
<td><div class="summary">
Called when the [Content](http://msdn.microsoft.com/en-us/library/ms592476) property changes.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnContentRendered](http://msdn.microsoft.com/en-us/library/ms599706)</td>
<td><div class="summary">
Raises the [ContentRendered](http://msdn.microsoft.com/en-us/library/ms596799) event.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnContentStringFormatChanged](http://msdn.microsoft.com/en-us/library/cc490883)</td>
<td><div class="summary">
Occurs when the [ContentStringFormat](http://msdn.microsoft.com/en-us/library/cc490889) property changes.
</div>
(Inherited from [ContentControl](http://msdn.microsoft.com/en-us/library/ms609797).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnContentTemplateChanged](http://msdn.microsoft.com/en-us/library/ms601784)</td>
<td><div class="summary">
Called when the [ContentTemplate](http://msdn.microsoft.com/en-us/library/ms592477) property changes.
</div>
(Inherited from [ContentControl](http://msdn.microsoft.com/en-us/library/ms609797).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnContentTemplateSelectorChanged](http://msdn.microsoft.com/en-us/library/ms601786)</td>
<td><div class="summary">
Called when the [ContentTemplateSelector](http://msdn.microsoft.com/en-us/library/ms592478) property changes.
</div>
(Inherited from [ContentControl](http://msdn.microsoft.com/en-us/library/ms609797).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnContextMenuClosing](http://msdn.microsoft.com/en-us/library/ms598237)</td>
<td><div class="summary">
Invoked whenever an unhandled [ContextMenuClosing](http://msdn.microsoft.com/en-us/library/ms596552) routed event reaches this class in its route. Implement this method to add class handling for this event.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnContextMenuOpening](http://msdn.microsoft.com/en-us/library/ms598240)</td>
<td><div class="summary">
Invoked whenever an unhandled [ContextMenuOpening](http://msdn.microsoft.com/en-us/library/ms596554) routed event reaches this class in its route. Implement this method to add class handling for this event.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnCreateAutomationPeer](http://msdn.microsoft.com/en-us/library/ms599707)</td>
<td><div class="summary">
Creates and returns a [WindowAutomationPeer](http://msdn.microsoft.com/en-us/library/ms608022) object for this [Window](http://msdn.microsoft.com/en-us/library/ms590112).
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnDeactivated](http://msdn.microsoft.com/en-us/library/ms599708)</td>
<td><div class="summary">
Raises the [Deactivated](http://msdn.microsoft.com/en-us/library/ms596800) event.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnDragEnter](http://msdn.microsoft.com/en-us/library/ms598926)</td>
<td><div class="summary">
Invoked when an unhandled [DragEnter](http://msdn.microsoft.com/en-us/library/ms596509) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnDragLeave](http://msdn.microsoft.com/en-us/library/ms598927)</td>
<td><div class="summary">
Invoked when an unhandled [DragLeave](http://msdn.microsoft.com/en-us/library/ms596511) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnDragOver](http://msdn.microsoft.com/en-us/library/ms598928)</td>
<td><div class="summary">
Invoked when an unhandled [DragOver](http://msdn.microsoft.com/en-us/library/ms596513) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnDrop](http://msdn.microsoft.com/en-us/library/ms598929)</td>
<td><div class="summary">
Invoked when an unhandled [DragEnter](http://msdn.microsoft.com/en-us/library/ms596509) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnGiveFeedback](http://msdn.microsoft.com/en-us/library/ms598930)</td>
<td><div class="summary">
Invoked when an unhandled [GiveFeedback](http://msdn.microsoft.com/en-us/library/ms596516) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnGotFocus](http://msdn.microsoft.com/en-us/library/ms598242)</td>
<td><div class="summary">
Invoked whenever an unhandled [GotFocus](http://msdn.microsoft.com/en-us/library/ms596645) event reaches this element in its route.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnGotKeyboardFocus](http://msdn.microsoft.com/en-us/library/ms598932)</td>
<td><div class="summary">
Invoked when an unhandled [GotKeyboardFocus](http://msdn.microsoft.com/en-us/library/aa345917) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnGotMouseCapture](http://msdn.microsoft.com/en-us/library/ms598933)</td>
<td><div class="summary">
Invoked when an unhandled [GotMouseCapture](http://msdn.microsoft.com/en-us/library/ms523136) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnGotStylusCapture](http://msdn.microsoft.com/en-us/library/ms598934)</td>
<td><div class="summary">
Invoked when an unhandled [GotStylusCapture](http://msdn.microsoft.com/en-us/library/ms523179) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnGotTouchCapture](http://msdn.microsoft.com/en-us/library/dd783579)</td>
<td><div class="summary">
Provides class handling for the [GotTouchCapture](http://msdn.microsoft.com/en-us/library/dd989297) routed event that occurs when a touch is captured to this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnInitialized](http://msdn.microsoft.com/en-us/library/ms598244)</td>
<td><div class="summary">
Raises the [Initialized](http://msdn.microsoft.com/en-us/library/ms596557) event. This method is invoked whenever [IsInitialized](http://msdn.microsoft.com/en-us/library/ms600884) is set to true internally.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnIsKeyboardFocusedChanged](http://msdn.microsoft.com/en-us/library/ms598935)</td>
<td><div class="summary">
Invoked when an unhandled [IsKeyboardFocusedChanged](http://msdn.microsoft.com/en-us/library/ms596651) event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnIsKeyboardFocusWithinChanged](http://msdn.microsoft.com/en-us/library/ms598936)</td>
<td><div class="summary">
Invoked just before the [IsKeyboardFocusWithinChanged](http://msdn.microsoft.com/en-us/library/ms596652) event is raised by this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnIsMouseCapturedChanged](http://msdn.microsoft.com/en-us/library/ms599252)</td>
<td><div class="summary">
Invoked when an unhandled [IsMouseCapturedChanged](http://msdn.microsoft.com/en-us/library/ms596653) event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnIsMouseCaptureWithinChanged](http://msdn.microsoft.com/en-us/library/ms599253)</td>
<td><div class="summary">
Invoked when an unhandled [IsMouseCaptureWithinChanged](http://msdn.microsoft.com/en-us/library/ms596654) event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnIsMouseDirectlyOverChanged](http://msdn.microsoft.com/en-us/library/ms599254)</td>
<td><div class="summary">
Invoked when an unhandled [IsMouseDirectlyOverChanged](http://msdn.microsoft.com/en-us/library/ms596655) event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnIsStylusCapturedChanged](http://msdn.microsoft.com/en-us/library/ms599255)</td>
<td><div class="summary">
Invoked when an unhandled [IsStylusCapturedChanged](http://msdn.microsoft.com/en-us/library/ms596656) event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnIsStylusCaptureWithinChanged](http://msdn.microsoft.com/en-us/library/ms599256)</td>
<td><div class="summary">
Invoked when an unhandled [IsStylusCaptureWithinChanged](http://msdn.microsoft.com/en-us/library/ms596657) event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnIsStylusDirectlyOverChanged](http://msdn.microsoft.com/en-us/library/ms599257)</td>
<td><div class="summary">
Invoked when an unhandled [IsStylusDirectlyOverChanged](http://msdn.microsoft.com/en-us/library/ms596658) event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnKeyDown](http://msdn.microsoft.com/en-us/library/ms599258)</td>
<td><div class="summary">
Invoked when an unhandled [KeyDown](http://msdn.microsoft.com/en-us/library/ms523126) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnKeyUp](http://msdn.microsoft.com/en-us/library/ms599259)</td>
<td><div class="summary">
Invoked when an unhandled [KeyUp](http://msdn.microsoft.com/en-us/library/ms523129) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnLocationChanged](http://msdn.microsoft.com/en-us/library/ms599709)</td>
<td><div class="summary">
Raises the [LocationChanged](http://msdn.microsoft.com/en-us/library/ms596801) event.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnLostFocus](http://msdn.microsoft.com/en-us/library/ms599260)</td>
<td><div class="summary">
Raises the [LostFocus](http://msdn.microsoft.com/en-us/library/ms596673) routed event by using the event data that is provided.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnLostKeyboardFocus](http://msdn.microsoft.com/en-us/library/ms599261)</td>
<td><div class="summary">
Invoked when an unhandled [LostKeyboardFocus](http://msdn.microsoft.com/en-us/library/aa345918) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnLostMouseCapture](http://msdn.microsoft.com/en-us/library/ms599262)</td>
<td><div class="summary">
Invoked when an unhandled [LostMouseCapture](http://msdn.microsoft.com/en-us/library/ms523139) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnLostStylusCapture](http://msdn.microsoft.com/en-us/library/ms599263)</td>
<td><div class="summary">
Invoked when an unhandled [LostStylusCapture](http://msdn.microsoft.com/en-us/library/ms523183) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnLostTouchCapture](http://msdn.microsoft.com/en-us/library/dd784514)</td>
<td><div class="summary">
Provides class handling for the [LostTouchCapture](http://msdn.microsoft.com/en-us/library/dd784505) routed event that occurs when this element loses a touch capture.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnManipulationBoundaryFeedback](http://msdn.microsoft.com/en-us/library/dd549629)</td>
<td><div class="summary">
Called when the [ManipulationBoundaryFeedback](http://msdn.microsoft.com/en-us/library/dd549583) event occurs.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnManipulationCompleted](http://msdn.microsoft.com/en-us/library/dd403062)</td>
<td><div class="summary">
Called when the [ManipulationCompleted](http://msdn.microsoft.com/en-us/library/dd403080) event occurs.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnManipulationDelta](http://msdn.microsoft.com/en-us/library/dd403423)</td>
<td><div class="summary">
Called when the [ManipulationDelta](http://msdn.microsoft.com/en-us/library/dd403301) event occurs.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnManipulationInertiaStarting](http://msdn.microsoft.com/en-us/library/dd549618)</td>
<td><div class="summary">
Called when the [ManipulationInertiaStarting](http://msdn.microsoft.com/en-us/library/dd549561) event occurs.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnManipulationStarted](http://msdn.microsoft.com/en-us/library/dd403303)</td>
<td><div class="summary">
Called when the [ManipulationStarted](http://msdn.microsoft.com/en-us/library/dd403503) event occurs.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnManipulationStarting](http://msdn.microsoft.com/en-us/library/dd991606)</td>
<td><div class="summary">
Provides class handling for the [ManipulationStarting](http://msdn.microsoft.com/en-us/library/dd782370) routed event that occurs when the manipulation processor is first created.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnMouseDoubleClick](http://msdn.microsoft.com/en-us/library/ms558165)</td>
<td><div class="summary">
Raises the [MouseDoubleClick](http://msdn.microsoft.com/en-us/library/ms597616) routed event.
</div>
(Inherited from [Control](http://msdn.microsoft.com/en-us/library/ms609826).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnMouseDown](http://msdn.microsoft.com/en-us/library/ms599264)</td>
<td><div class="summary">
Invoked when an unhandled [MouseDown](http://msdn.microsoft.com/en-us/library/ms523141) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnMouseEnter](http://msdn.microsoft.com/en-us/library/ms599265)</td>
<td><div class="summary">
Invoked when an unhandled [MouseEnter](http://msdn.microsoft.com/en-us/library/ms523142) attached event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnMouseLeave](http://msdn.microsoft.com/en-us/library/ms599266)</td>
<td><div class="summary">
Invoked when an unhandled [MouseLeave](http://msdn.microsoft.com/en-us/library/ms523144) attached event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnMouseLeftButtonDown](http://msdn.microsoft.com/en-us/library/ms599267)</td>
<td><div class="summary">
Invoked when an unhandled [MouseLeftButtonDown](http://msdn.microsoft.com/en-us/library/ms596680) routed event is raised on this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnMouseLeftButtonUp](http://msdn.microsoft.com/en-us/library/ms599268)</td>
<td><div class="summary">
Invoked when an unhandled [MouseLeftButtonUp](http://msdn.microsoft.com/en-us/library/ms596681) routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnMouseMove](http://msdn.microsoft.com/en-us/library/ms599269)</td>
<td><div class="summary">
Invoked when an unhandled [MouseMove](http://msdn.microsoft.com/en-us/library/ms523146) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnMouseRightButtonDown](http://msdn.microsoft.com/en-us/library/ms599270)</td>
<td><div class="summary">
Invoked when an unhandled [MouseRightButtonDown](http://msdn.microsoft.com/en-us/library/ms596683) routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnMouseRightButtonUp](http://msdn.microsoft.com/en-us/library/ms599271)</td>
<td><div class="summary">
Invoked when an unhandled [MouseRightButtonUp](http://msdn.microsoft.com/en-us/library/ms596684) routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnMouseUp](http://msdn.microsoft.com/en-us/library/ms599272)</td>
<td><div class="summary">
Invoked when an unhandled [MouseUp](http://msdn.microsoft.com/en-us/library/ms523148) routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnMouseWheel](http://msdn.microsoft.com/en-us/library/ms599273)</td>
<td><div class="summary">
Invoked when an unhandled [MouseWheel](http://msdn.microsoft.com/en-us/library/ms523151) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewDragEnter](http://msdn.microsoft.com/en-us/library/ms599274)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewDragEnter](http://msdn.microsoft.com/en-us/library/ms596517) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewDragLeave](http://msdn.microsoft.com/en-us/library/ms599275)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewDragLeave](http://msdn.microsoft.com/en-us/library/ms596519) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewDragOver](http://msdn.microsoft.com/en-us/library/ms599276)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewDragOver](http://msdn.microsoft.com/en-us/library/ms596521) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewDrop](http://msdn.microsoft.com/en-us/library/ms599277)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewDrop](http://msdn.microsoft.com/en-us/library/ms596523) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewGiveFeedback](http://msdn.microsoft.com/en-us/library/ms599278)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewGiveFeedback](http://msdn.microsoft.com/en-us/library/ms596525) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewGotKeyboardFocus](http://msdn.microsoft.com/en-us/library/ms599279)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewGotKeyboardFocus](http://msdn.microsoft.com/en-us/library/aa345919) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewKeyDown](http://msdn.microsoft.com/en-us/library/ms599280)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewKeyDown](http://msdn.microsoft.com/en-us/library/ms523131) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewKeyUp](http://msdn.microsoft.com/en-us/library/ms599281)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewKeyUp](http://msdn.microsoft.com/en-us/library/ms523134) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewLostKeyboardFocus](http://msdn.microsoft.com/en-us/library/ms599282)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewKeyDown](http://msdn.microsoft.com/en-us/library/ms523131) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewMouseDoubleClick](http://msdn.microsoft.com/en-us/library/ms558166)</td>
<td><div class="summary">
Raises the [PreviewMouseDoubleClick](http://msdn.microsoft.com/en-us/library/ms597617) routed event.
</div>
(Inherited from [Control](http://msdn.microsoft.com/en-us/library/ms609826).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewMouseDown](http://msdn.microsoft.com/en-us/library/ms599283)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewMouseDown](http://msdn.microsoft.com/en-us/library/ms523154) attached routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewMouseLeftButtonDown](http://msdn.microsoft.com/en-us/library/ms599284)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewMouseLeftButtonDown](http://msdn.microsoft.com/en-us/library/ms596697) routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewMouseLeftButtonUp](http://msdn.microsoft.com/en-us/library/ms599285)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewMouseLeftButtonUp](http://msdn.microsoft.com/en-us/library/ms596698) routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewMouseMove](http://msdn.microsoft.com/en-us/library/ms599286)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewMouseMove](http://msdn.microsoft.com/en-us/library/ms523159) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewMouseRightButtonDown](http://msdn.microsoft.com/en-us/library/ms599287)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewMouseRightButtonDown](http://msdn.microsoft.com/en-us/library/ms596700) routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewMouseRightButtonUp](http://msdn.microsoft.com/en-us/library/ms599288)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewMouseRightButtonUp](http://msdn.microsoft.com/en-us/library/ms596701) routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewMouseUp](http://msdn.microsoft.com/en-us/library/ms599289)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewMouseUp](http://msdn.microsoft.com/en-us/library/ms523163) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewMouseWheel](http://msdn.microsoft.com/en-us/library/ms599290)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewMouseWheel](http://msdn.microsoft.com/en-us/library/ms523168) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewQueryContinueDrag](http://msdn.microsoft.com/en-us/library/ms599291)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewQueryContinueDrag](http://msdn.microsoft.com/en-us/library/ms596527) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewStylusButtonDown](http://msdn.microsoft.com/en-us/library/ms599292)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewStylusButtonDown](http://msdn.microsoft.com/en-us/library/ms523186) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewStylusButtonUp](http://msdn.microsoft.com/en-us/library/ms599293)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewStylusButtonUp](http://msdn.microsoft.com/en-us/library/ms523189) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewStylusDown](http://msdn.microsoft.com/en-us/library/ms599294)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewStylusDown](http://msdn.microsoft.com/en-us/library/ms523193) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewStylusInAirMove](http://msdn.microsoft.com/en-us/library/ms599295)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewStylusInAirMove](http://msdn.microsoft.com/en-us/library/ms523196) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewStylusInRange](http://msdn.microsoft.com/en-us/library/ms599296)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewStylusInRange](http://msdn.microsoft.com/en-us/library/ms523198) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewStylusMove](http://msdn.microsoft.com/en-us/library/ms599297)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewStylusMove](http://msdn.microsoft.com/en-us/library/ms588440) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewStylusOutOfRange](http://msdn.microsoft.com/en-us/library/ms599298)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewStylusOutOfRange](http://msdn.microsoft.com/en-us/library/ms588441) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewStylusSystemGesture](http://msdn.microsoft.com/en-us/library/ms599299)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewStylusSystemGesture](http://msdn.microsoft.com/en-us/library/ms588442) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewStylusUp](http://msdn.microsoft.com/en-us/library/ms599300)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewStylusUp](http://msdn.microsoft.com/en-us/library/ms588443) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewTextInput](http://msdn.microsoft.com/en-us/library/ms599301)</td>
<td><div class="summary">
Invoked when an unhandled [PreviewTextInput](http://msdn.microsoft.com/en-us/library/ms588471) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewTouchDown](http://msdn.microsoft.com/en-us/library/dd992477)</td>
<td><div class="summary">
Provides class handling for the [PreviewTouchDown](http://msdn.microsoft.com/en-us/library/dd991743) routed event that occurs when a touch presses this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewTouchMove](http://msdn.microsoft.com/en-us/library/dd784544)</td>
<td><div class="summary">
Provides class handling for the [PreviewTouchMove](http://msdn.microsoft.com/en-us/library/dd990490) routed event that occurs when a touch moves while inside this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPreviewTouchUp](http://msdn.microsoft.com/en-us/library/dd783493)</td>
<td><div class="summary">
Provides class handling for the [PreviewTouchUp](http://msdn.microsoft.com/en-us/library/dd783905) routed event that occurs when a touch is released inside this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnPropertyChanged](http://msdn.microsoft.com/en-us/library/ms598246)</td>
<td><div class="summary">
Invoked whenever the effective value of any dependency property on this [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714) has been updated. The specific dependency property that changed is reported in the arguments parameter. Overrides [OnPropertyChanged(DependencyPropertyChangedEventArgs)](http://msdn.microsoft.com/en-us/library/ms597471).
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnQueryContinueDrag](http://msdn.microsoft.com/en-us/library/ms599302)</td>
<td><div class="summary">
Invoked when an unhandled [QueryContinueDrag](http://msdn.microsoft.com/en-us/library/ms596529) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnQueryCursor](http://msdn.microsoft.com/en-us/library/ms599303)</td>
<td><div class="summary">
Invoked when an unhandled [QueryCursor](http://msdn.microsoft.com/en-us/library/ms523171) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnRender](http://msdn.microsoft.com/en-us/library/ms599305)</td>
<td><div class="summary">
When overridden in a derived class, participates in rendering operations that are directed by the layout system. The rendering instructions for this element are not used directly when this method is invoked, and are instead preserved for later asynchronous use by layout and drawing.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnRenderSizeChanged](http://msdn.microsoft.com/en-us/library/ms598248)</td>
<td><div class="summary">
Raises the [SizeChanged](http://msdn.microsoft.com/en-us/library/ms596560) event, using the specified information as part of the eventual event data.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnSourceInitialized](http://msdn.microsoft.com/en-us/library/ms599710)</td>
<td><div class="summary">
Raises the [SourceInitialized](http://msdn.microsoft.com/en-us/library/ms596802) event.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStateChanged](http://msdn.microsoft.com/en-us/library/ms599711)</td>
<td><div class="summary">
Raises the [StateChanged](http://msdn.microsoft.com/en-us/library/ms596803) event.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStyleChanged](http://msdn.microsoft.com/en-us/library/ms598251)</td>
<td><div class="summary">
Invoked when the style in use on this element changes, which will invalidate the layout.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStylusButtonDown](http://msdn.microsoft.com/en-us/library/ms599306)</td>
<td><div class="summary">
Invoked when an unhandled [StylusButtonDown](http://msdn.microsoft.com/en-us/library/ms588445) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStylusButtonUp](http://msdn.microsoft.com/en-us/library/ms599307)</td>
<td><div class="summary">
Invoked when an unhandled [StylusButtonUp](http://msdn.microsoft.com/en-us/library/ms588446) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStylusDown](http://msdn.microsoft.com/en-us/library/ms599308)</td>
<td><div class="summary">
Invoked when an unhandled [StylusDown](http://msdn.microsoft.com/en-us/library/ms588447) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStylusEnter](http://msdn.microsoft.com/en-us/library/ms599309)</td>
<td><div class="summary">
Invoked when an unhandled [StylusEnter](http://msdn.microsoft.com/en-us/library/ms588448) attached event is raised by this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStylusInAirMove](http://msdn.microsoft.com/en-us/library/ms599310)</td>
<td><div class="summary">
Invoked when an unhandled [StylusInAirMove](http://msdn.microsoft.com/en-us/library/ms588449) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStylusInRange](http://msdn.microsoft.com/en-us/library/ms599311)</td>
<td><div class="summary">
Invoked when an unhandled [StylusInRange](http://msdn.microsoft.com/en-us/library/ms588450) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStylusLeave](http://msdn.microsoft.com/en-us/library/ms599312)</td>
<td><div class="summary">
Invoked when an unhandled [StylusLeave](http://msdn.microsoft.com/en-us/library/ms588452) attached event is raised by this element. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStylusMove](http://msdn.microsoft.com/en-us/library/ms599313)</td>
<td><div class="summary">
Invoked when an unhandled [StylusMove](http://msdn.microsoft.com/en-us/library/ms588455) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStylusOutOfRange](http://msdn.microsoft.com/en-us/library/ms599314)</td>
<td><div class="summary">
Invoked when an unhandled [StylusOutOfRange](http://msdn.microsoft.com/en-us/library/ms588460) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStylusSystemGesture](http://msdn.microsoft.com/en-us/library/ms599315)</td>
<td><div class="summary">
Invoked when an unhandled [StylusSystemGesture](http://msdn.microsoft.com/en-us/library/ms588464) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnStylusUp](http://msdn.microsoft.com/en-us/library/ms599316)</td>
<td><div class="summary">
Invoked when an unhandled [StylusUp](http://msdn.microsoft.com/en-us/library/ms588467) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnTemplateChanged](http://msdn.microsoft.com/en-us/library/ms558167)</td>
<td><div class="summary">
Called whenever the control's template changes.
</div>
(Inherited from [Control](http://msdn.microsoft.com/en-us/library/ms609826).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnTextInput](http://msdn.microsoft.com/en-us/library/ms599317)</td>
<td><div class="summary">
Invoked when an unhandled [TextInput](http://msdn.microsoft.com/en-us/library/ms601826) attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnToolTipClosing](http://msdn.microsoft.com/en-us/library/ms598255)</td>
<td><div class="summary">
Invoked whenever an unhandled [ToolTipClosing](http://msdn.microsoft.com/en-us/library/ms596563) routed event reaches this class in its route. Implement this method to add class handling for this event.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnToolTipOpening](http://msdn.microsoft.com/en-us/library/ms598256)</td>
<td><div class="summary">
Invoked whenever the [ToolTipOpening](http://msdn.microsoft.com/en-us/library/ms596564) routed event reaches this class in its route. Implement this method to add class handling for this event.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnTouchDown](http://msdn.microsoft.com/en-us/library/dd991371)</td>
<td><div class="summary">
Provides class handling for the [TouchDown](http://msdn.microsoft.com/en-us/library/dd782616) routed event that occurs when a touch presses inside this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnTouchEnter](http://msdn.microsoft.com/en-us/library/dd782614)</td>
<td><div class="summary">
Provides class handling for the [TouchEnter](http://msdn.microsoft.com/en-us/library/dd990673) routed event that occurs when a touch moves from outside to inside the bounds of this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnTouchLeave](http://msdn.microsoft.com/en-us/library/dd782894)</td>
<td><div class="summary">
Provides class handling for the [TouchLeave](http://msdn.microsoft.com/en-us/library/dd991524) routed event that occurs when a touch moves from inside to outside the bounds of this [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnTouchMove](http://msdn.microsoft.com/en-us/library/dd783255)</td>
<td><div class="summary">
Provides class handling for the [TouchMove](http://msdn.microsoft.com/en-us/library/dd991311) routed event that occurs when a touch moves while inside this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnTouchUp](http://msdn.microsoft.com/en-us/library/dd992297)</td>
<td><div class="summary">
Provides class handling for the [TouchUp](http://msdn.microsoft.com/en-us/library/dd991789) routed event that occurs when a touch is released inside this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnVisualChildrenChanged](http://msdn.microsoft.com/en-us/library/ms608862)</td>
<td><div class="summary">
Called when the [VisualCollection](http://msdn.microsoft.com/en-us/library/ms635644) of the visual object is modified.
</div>
(Inherited from [Visual](http://msdn.microsoft.com/en-us/library/ms635637).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnVisualParentChanged](http://msdn.microsoft.com/en-us/library/ms599713)</td>
<td><div class="summary">
Called when the parent of the window is changed.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ParentLayoutInvalidated](http://msdn.microsoft.com/en-us/library/ms598260)</td>
<td><div class="summary">
Supports incremental layout implementations in specialized subclasses of [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714). [ParentLayoutInvalidated(UIElement)](http://msdn.microsoft.com/en-us/library/ms598260) is invoked when a child element has invalidated a property that is marked in metadata as affecting the parent's measure or arrange passes during layout.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[PointFromScreen](http://msdn.microsoft.com/en-us/library/aa346960)</td>
<td><div class="summary">
Converts a [Point](http://msdn.microsoft.com/en-us/library/ms602977) in screen coordinates into a [Point](http://msdn.microsoft.com/en-us/library/ms602977) that represents the current coordinate system of the [Visual](http://msdn.microsoft.com/en-us/library/ms635637).
</div>
(Inherited from [Visual](http://msdn.microsoft.com/en-us/library/ms635637).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[PointToScreen](http://msdn.microsoft.com/en-us/library/aa346961)</td>
<td><div class="summary">
Converts a [Point](http://msdn.microsoft.com/en-us/library/ms602977) that represents the current coordinate system of the [Visual](http://msdn.microsoft.com/en-us/library/ms635637) into a [Point](http://msdn.microsoft.com/en-us/library/ms602977) in screen coordinates.
</div>
(Inherited from [Visual](http://msdn.microsoft.com/en-us/library/ms635637).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[PredictFocus](http://msdn.microsoft.com/en-us/library/ms598263)</td>
<td><div class="summary">
Determines the next element that would receive focus relative to this element for a provided focus movement direction, but does not actually move the focus.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RaiseEvent](http://msdn.microsoft.com/en-us/library/ms599320)</td>
<td><div class="summary">
Raises a specific routed event. The [RoutedEvent](http://msdn.microsoft.com/en-us/library/ms589739) to be raised is identified within the [RoutedEventArgs](http://msdn.microsoft.com/en-us/library/ms589740) instance that is provided (as the [RoutedEvent](http://msdn.microsoft.com/en-us/library/ms601234) property of that event data).
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
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
<td>[RegisterName](http://msdn.microsoft.com/en-us/library/ms598265)</td>
<td><div class="summary">
Provides an accessor that simplifies access to the [NameScope](http://msdn.microsoft.com/en-us/library/ms602968) registration method.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ReleaseAllTouchCaptures](http://msdn.microsoft.com/en-us/library/dd783351)</td>
<td><div class="summary">
Releases all captured touch devices from this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ReleaseMouseCapture](http://msdn.microsoft.com/en-us/library/ms599321)</td>
<td><div class="summary">
Releases the mouse capture, if this element held the capture.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ReleaseStylusCapture](http://msdn.microsoft.com/en-us/library/ms599322)</td>
<td><div class="summary">
Releases the stylus device capture, if this element held the capture.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ReleaseTouchCapture](http://msdn.microsoft.com/en-us/library/dd990535)</td>
<td><div class="summary">
Attempts to release the specified touch device from this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RemoveHandler](http://msdn.microsoft.com/en-us/library/ms599323)</td>
<td><div class="summary">
Removes the specified routed event handler from this element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[RemoveLogicalChild](http://msdn.microsoft.com/en-us/library/ms598268)</td>
<td><div class="summary">
Removes the provided object from this element's logical tree. [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714) updates the affected logical tree parent pointers to keep in sync with this deletion.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[RemoveVisualChild](http://msdn.microsoft.com/en-us/library/ms608864)</td>
<td><div class="summary">
Removes the parent-child relationship between two visuals.
</div>
(Inherited from [Visual](http://msdn.microsoft.com/en-us/library/ms635637).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[SetBinding(DependencyProperty, BindingBase)](http://msdn.microsoft.com/en-us/library/ms598273)</td>
<td><div class="summary">
Attaches a binding to this element, based on the provided binding object.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[SetBinding(DependencyProperty, String)](http://msdn.microsoft.com/en-us/library/ms598270)</td>
<td><div class="summary">
Attaches a binding to this element, based on the provided source property name as a path qualification to the data source.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
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
<td>[SetResourceReference](http://msdn.microsoft.com/en-us/library/ms557690)</td>
<td><div class="summary">
Searches for a resource with the specified name and sets up a resource reference to it for the specified property.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[SetValue(DependencyProperty, Object)](http://msdn.microsoft.com/en-us/library/ms597473)</td>
<td><div class="summary">
Sets the local value of a dependency property, specified by its dependency property identifier.
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[SetValue(DependencyPropertyKey, Object)](http://msdn.microsoft.com/en-us/library/ms597474)</td>
<td><div class="summary">
Sets the local value of a read-only dependency property, specified by the [DependencyPropertyKey](http://msdn.microsoft.com/en-us/library/ms602348) identifier of the dependency property.
</div>
(Inherited from [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ShouldSerializeCommandBindings](http://msdn.microsoft.com/en-us/library/ms599324)</td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the [CommandBindings](http://msdn.microsoft.com/en-us/library/ms588680) property on instances of this class.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ShouldSerializeContent](http://msdn.microsoft.com/en-us/library/ms601788)</td>
<td><div class="summary">
Indicates whether the [Content](http://msdn.microsoft.com/en-us/library/ms592476) property should be persisted.
</div>
(Inherited from [ContentControl](http://msdn.microsoft.com/en-us/library/ms609797).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ShouldSerializeInputBindings](http://msdn.microsoft.com/en-us/library/ms599325)</td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the [InputBindings](http://msdn.microsoft.com/en-us/library/ms588692) property on instances of this class.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
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
<td>[ShouldSerializeResources](http://msdn.microsoft.com/en-us/library/ms557692)</td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the [Resources](http://msdn.microsoft.com/en-us/library/ms600898) property.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ShouldSerializeStyle](http://msdn.microsoft.com/en-us/library/ms557694)</td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the [Style](http://msdn.microsoft.com/en-us/library/ms600899) property.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ShouldSerializeTriggers](http://msdn.microsoft.com/en-us/library/ms557696)</td>
<td><div class="summary">
Returns whether serialization processes should serialize the contents of the [Triggers](http://msdn.microsoft.com/en-us/library/ms600903) property.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Show](http://msdn.microsoft.com/en-us/library/ms599714)</td>
<td><div class="summary">
Opens a window and returns without waiting for the newly opened window to close.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ShowDialog](http://msdn.microsoft.com/en-us/library/ms599715)</td>
<td><div class="summary">
Opens a window and returns only when the newly opened window is closed.
</div>
(Inherited from [Window](http://msdn.microsoft.com/en-us/library/ms590112).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/ms558168)</td>
<td><div class="summary">
Returns the string representation of a [Control](http://msdn.microsoft.com/en-us/library/ms609826) object.
</div>
(Inherited from [Control](http://msdn.microsoft.com/en-us/library/ms609826).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[TransformToAncestor(Visual)](http://msdn.microsoft.com/en-us/library/ms608865)</td>
<td><div class="summary">
Returns a transform that can be used to transform coordinates from the [Visual](http://msdn.microsoft.com/en-us/library/ms635637) to the specified [Visual](http://msdn.microsoft.com/en-us/library/ms635637) ancestor of the visual object.
</div>
(Inherited from [Visual](http://msdn.microsoft.com/en-us/library/ms635637).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[TransformToAncestor(Visual3D)](http://msdn.microsoft.com/en-us/library/bb763975)</td>
<td><div class="summary">
Returns a transform that can be used to transform coordinates from the [Visual](http://msdn.microsoft.com/en-us/library/ms635637) to the specified [Visual3D](http://msdn.microsoft.com/en-us/library/ms594932) ancestor of the visual object.
</div>
(Inherited from [Visual](http://msdn.microsoft.com/en-us/library/ms635637).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[TransformToDescendant](http://msdn.microsoft.com/en-us/library/ms608866)</td>
<td><div class="summary">
Returns a transform that can be used to transform coordinates from the [Visual](http://msdn.microsoft.com/en-us/library/ms635637) to the specified visual object descendant.
</div>
(Inherited from [Visual](http://msdn.microsoft.com/en-us/library/ms635637).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[TransformToVisual](http://msdn.microsoft.com/en-us/library/ms608867)</td>
<td><div class="summary">
Returns a transform that can be used to transform coordinates from the [Visual](http://msdn.microsoft.com/en-us/library/ms635637) to the specified visual object.
</div>
(Inherited from [Visual](http://msdn.microsoft.com/en-us/library/ms635637).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[TranslatePoint](http://msdn.microsoft.com/en-us/library/ms599326)</td>
<td><div class="summary">
Translates a point relative to this element to coordinates that are relative to the specified element.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[TryFindResource](http://msdn.microsoft.com/en-us/library/ms557698)</td>
<td><div class="summary">
Searches for a resource with the specified key, and returns that resource if found.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[UnregisterName](http://msdn.microsoft.com/en-us/library/ms557700)</td>
<td><div class="summary">
Simplifies access to the [NameScope](http://msdn.microsoft.com/en-us/library/ms602968) de-registration method.
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[UpdateDefaultStyle](http://msdn.microsoft.com/en-us/library/hh534717)</td>
<td><div class="summary">
Reapplies the default style to the current [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).
</div>
(Inherited from [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[UpdateLayout](http://msdn.microsoft.com/en-us/library/ms599327)</td>
<td><div class="summary">
Ensures that all visual child elements of this element are properly updated for layout.
</div>
(Inherited from [UIElement](http://msdn.microsoft.com/en-us/library/ms590078).)</td>
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

[DefaultConfirmationWindow Class](/patterns-practices/reference/defaultconfirmationwindow-class-mspp-interactivity-defaultpopupwindows)<br/>
[Microsoft.Practices.Prism.Interactivity.DefaultPopupWindows Namespace](/patterns-practices/reference/mspp-interactivity-defaultpopupwindows-namespace)<br/>