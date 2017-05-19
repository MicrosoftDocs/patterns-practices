---
TOCTitle: GetObservableContext Method
Title: 'RegionContext.GetObservableContext Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionContext.GetObservableContext(System.Windows.DependencyObject)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418951(v=PandP.50)'
---

Prism Class Library

RegionContext.GetObservableContext Method
=============================================

Returns an [ObservableObject&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.observableobject%601) wrapper around the RegionContext value. The RegionContext will be set on any views (dependency objects) that are inside the [Views](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.views) collection by the [BindRegionContextToDependencyObjectBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.bindregioncontexttodependencyobjectbehavior) Behavior. The RegionContext will also be set to the control that hosts the Region, by the [SyncRegionContextWithHostBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.syncregioncontextwithhostbehavior) Behavior. If the [ObservableObject&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.observableobject%601) wrapper does not already exist, an empty one will be created. This way, an observer can notify when the value is set for the first time.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public static ObservableObject&lt;Object&gt; GetObservableContext( DependencyObject view )Public Shared Function GetObservableContext ( view As DependencyObject ) As ObservableObject(Of Object)
#### Parameters

view  
Type: [System.Windows.DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309)
Any view that hold the RegionContext value.

#### Return Value

Type: [ObservableObject](https://msdn.microsoft.com/t:microsoft.practices.prism.observableobject%601)&lt;(Of &lt;([Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)&gt;)&gt;)
Wrapper around the Regioncontext value.

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionContext Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regioncontext)

[RegionContext Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regioncontext)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
