---
TOCTitle: GetObservableRegion Method
Title: 'RegionManager.GetObservableRegion Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManager.GetObservableRegion(System.Windows.DependencyObject)'
ms:mtpsurl: 'regionmanager-getobservableregion-method-mspp-regions.md'
---

# RegionManager.GetObservableRegion Method

Returns an [ObservableObject&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.observableobject%601) wrapper that can hold an [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion). Using this wrapper you can detect when an [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion) has been created by the [RegionAdapterBase&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionadapterbase%601). If the [ObservableObject&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.observableobject%601) wrapper does not yet exist, a new wrapper will be created. When the region gets created and assigned to the wrapper, you can use the [PropertyChanged](https://msdn.microsoft.com/library/microsoft.practices.prism.observableobject%601.propertychanged) event to get notified of that change.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
public static ObservableObject&lt;IRegion&gt; GetObservableRegion( DependencyObject view )Public Shared Function GetObservableRegion ( view As DependencyObject ) As ObservableObject(Of IRegion)

### Parameters

view  
Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)
The view that will host the region.

### Return Value

Type: [ObservableObject](https://msdn.microsoft.com/library/microsoft.practices.prism.observableobject%601)&lt;(Of &lt;([IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion)&gt;)&gt;)
Wrapper that can hold an [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion) value and can notify when the [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion) value changes.

## See Also
[RegionManager Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanager)

[RegionManager Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanager)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
