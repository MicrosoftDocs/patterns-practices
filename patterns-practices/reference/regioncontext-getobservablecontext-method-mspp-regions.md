---
TOCTitle: GetObservableContext Method
Title: 'RegionContext.GetObservableContext Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionContext.GetObservableContext(System.Windows.DependencyObject)'
ms:mtpsurl: 'regioncontext-getobservablecontext-method-mspp-regions.md'
---


# RegionContext.GetObservableContext Method

Returns an [ObservableObject&lt;T&gt;](/patterns-practices/reference/observableobject-t-class-mspp) wrapper around the RegionContext value. The RegionContext will be set on any views (dependency objects) that are inside the [Views](/patterns-practices/reference/iregion-views-property-mspp-regions) collection by the [BindRegionContextToDependencyObjectBehavior](/patterns-practices/reference/bindregioncontexttodependencyobjectbehavior-class-mspp-regions-behaviors) Behavior. The RegionContext will also be set to the control that hosts the Region, by the [SyncRegionContextWithHostBehavior](/patterns-practices/reference/syncregioncontextwithhostbehavior-class-mspp-regions-behaviors) Behavior. If the [ObservableObject&lt;T&gt;](/patterns-practices/reference/observableobject-t-class-mspp) wrapper does not already exist, an empty one will be created. This way, an observer can notify when the value is set for the first time.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static ObservableObject<Object> GetObservableContext(
	DependencyObject view
)
```

### Parameters

*view*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Any view that hold the RegionContext value.

### Return Value

Type: [ObservableObject](/patterns-practices/reference/observableobject-t-class-mspp)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;  
Wrapper around the Regioncontext value.


Returns an [ObservableObject(Of T)](/patterns-practices/reference/observableobject-t-class-mspp) wrapper around the RegionContext value. The RegionContext will be set on any views (dependency objects) that are inside the [Views](/patterns-practices/reference/iregion-views-property-mspp-regions) collection by the [BindRegionContextToDependencyObjectBehavior](/patterns-practices/reference/bindregioncontexttodependencyobjectbehavior-class-mspp-regions-behaviors) Behavior. The RegionContext will also be set to the control that hosts the Region, by the [SyncRegionContextWithHostBehavior](/patterns-practices/reference/syncregioncontextwithhostbehavior-class-mspp-regions-behaviors) Behavior. If the [ObservableObject(Of T)](/patterns-practices/reference/observableobject-t-class-mspp) wrapper does not already exist, an empty one will be created. This way, an observer can notify when the value is set for the first time.



# RegionContext.GetObservableContext Method

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Shared Function GetObservableContext ( 
	view As DependencyObject
) As ObservableObject(Of Object)
```

### Parameters

*view*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Any view that hold the RegionContext value.

### Return Value

Type: [ObservableObject](/patterns-practices/reference/observableobject-t-class-mspp)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))  
Wrapper around the Regioncontext value.

## See Also

[RegionContext Class](/patterns-practices/reference/regioncontext-class-mspp-regions)<br/>
[RegionContext Members](/patterns-practices/reference/regioncontext-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>