---
TOCTitle: 'ObservableObject(T) Class'
Title: 'ObservableObject(T) Class (Microsoft.Practices.Prism)'
ms:assetid: 'T:Microsoft.Practices.Prism.ObservableObject\`1'
ms:mtpsurl: 'observableobject-t-class-mspp.md'
---


# ObservableObject&lt;T&gt; Class

Class that wraps an object, so that other classes can notify for Change events. Typically, this class is set as a Dependency Property on DependencyObjects, and allows other classes to observe any changes in the Value.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class ObservableObject<T> : FrameworkElement, 
	INotifyPropertyChanged
```

### Type Parameters

*T*  
        The type of the property that's wrapped in the Observable object

## Remarks

 This class is required, because in Silverlight, it's not possible to receive Change notifications for Dependency properties that you do not own.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [System.Windows.Threading.DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925)  
    [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
      [System.Windows.Media.Visual](http://msdn.microsoft.com/en-us/library/ms635637)  
        [System.Windows.UIElement](http://msdn.microsoft.com/en-us/library/ms590078)  
          [System.Windows.FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)  
            Microsoft.Practices.Prism.ObservableObject&lt;T&gt;

## See Also

[ObservableObject&lt;T&gt; Members](/patterns-practices/reference/observableobject-t-members-mspp)  
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)  

# ObservableObject(Of T) Class

Class that wraps an object, so that other classes can notify for Change events. Typically, this class is set as a Dependency Property on DependencyObjects, and allows other classes to observe any changes in the Value.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Class ObservableObject(Of T)
	Inherits FrameworkElement
	Implements INotifyPropertyChanged
```

### Type Parameters

*T*  
        The type of the property that's wrapped in the Observable object

## Remarks

 This class is required, because in Silverlight, it's not possible to receive Change notifications for Dependency properties that you do not own.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [System.Windows.Threading.DispatcherObject](http://msdn.microsoft.com/en-us/library/ms615925)  
    [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
      [System.Windows.Media.Visual](http://msdn.microsoft.com/en-us/library/ms635637)  
        [System.Windows.UIElement](http://msdn.microsoft.com/en-us/library/ms590078)  
          [System.Windows.FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714)  
            Microsoft.Practices.Prism.ObservableObject(Of T)

## See Also

[ObservableObject(Of T) Members](/patterns-practices/reference/observableobject-t-members-mspp)  
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)  
