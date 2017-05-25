---
TOCTitle: 'ObservableObject(T) Class'
Title: 'ObservableObject(T) Class (Microsoft.Practices.Prism)'
ms:assetid: 'T:Microsoft.Practices.Prism.ObservableObject\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431509(v=PandP.50)'
---


# ObservableObject&lt;(Of &lt;(T&gt;)&gt;) Class

Class that wraps an object, so that other classes can notify for Change events. Typically, this class is set as a Dependency Property on DependencyObjects, and allows other classes to observe any changes in the Value.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/library/microsoft.practices.prism)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public class ObservableObject&lt;T&gt; : FrameworkElement, INotifyPropertyChanged Public Class ObservableObject(Of T) Inherits FrameworkElement Implements INotifyPropertyChanged
## Type Parameters

<span id="templatesToggle"></span>
T  
The type of the property that's wrapped in the Observable object

## Remarks

 This class is required, because in Silverlight, it's not possible to receive Change notifications for Dependency properties that you do not own.

## Inheritance Hierarchy

<span id="familyToggle"></span>[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  [System.Windows.Threading.DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925)
    [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)
      [System.Windows.Media.Visual](http://msdn.microsoft.com/en-us/library/ms635637)
        [System.Windows.UIElement](http://msdn.microsoft.com/en-us/library/ms590078)
          [System.Windows.FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)
            Microsoft.Practices.Prism.ObservableObject&lt;(Of &lt;(T&gt;)&gt;)

## See Also

[ObservableObject&lt;(Of &lt;(T&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.observableobject%601)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism)
