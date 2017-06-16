---
TOCTitle: GetObservableRegion Method
Title: 'RegionManager.GetObservableRegion Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManager.GetObservableRegion(System.Windows.DependencyObject)'
ms:mtpsurl: 'regionmanager-getobservableregion-method-mspp-regions.md'
---

# RegionManager.GetObservableRegion Method

Returns an [ObservableObject&lt;T&gt;](/patterns-practices/reference/observableobject-t-class-mspp) wrapper that can hold an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions). Using this wrapper you can detect when an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) has been created by the [RegionAdapterBase&lt;T&gt;](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions). If the [ObservableObject&lt;T&gt;](/patterns-practices/reference/observableobject-t-class-mspp) wrapper does not yet exist, a new wrapper will be created. When the region gets created and assigned to the wrapper, you can use the [PropertyChanged](/patterns-practices/reference/observableobject-t-propertychanged-event-mspp) event to get notified of that change.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static ObservableObject<IRegion> GetObservableRegion(
	DependencyObject view
)
```

### Parameters

*view*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The view that will host the region.

### Return Value

Type: [ObservableObject](/patterns-practices/reference/observableobject-t-class-mspp)&lt;[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)&gt;  
Wrapper that can hold an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) value and can notify when the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) value changes.

# RegionManager.GetObservableRegion Method

Returns an [ObservableObject(Of T)](/patterns-practices/reference/observableobject-t-class-mspp) wrapper that can hold an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions). Using this wrapper you can detect when an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) has been created by the [RegionAdapterBase(Of T)](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions). If the [ObservableObject(Of T)](/patterns-practices/reference/observableobject-t-class-mspp) wrapper does not yet exist, a new wrapper will be created. When the region gets created and assigned to the wrapper, you can use the [PropertyChanged](/patterns-practices/reference/observableobject-t-propertychanged-event-mspp) event to get notified of that change.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Shared Function GetObservableRegion ( 
	view As DependencyObject
) As ObservableObject(Of IRegion)
```

### Parameters

*view*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The view that will host the region.

### Return Value

Type: [ObservableObject](/patterns-practices/reference/observableobject-t-class-mspp)(Of [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions))  
Wrapper that can hold an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) value and can notify when the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) value changes.

## See Also

[RegionManager Class](/patterns-practices/reference/regionmanager-class-mspp-regions)  
[RegionManager Members](/patterns-practices/reference/regionmanager-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  