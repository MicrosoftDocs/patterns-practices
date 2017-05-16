---
TOCTitle: RegionContext Members
Title: 'RegionContext Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.RegionContext'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405506(v=PandP.50)'
---

Prism Class Library

RegionContext Members
=====================

Include Protected Members
Include Inherited Members

The [RegionContext](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regioncontext) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg405506.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405506.static(en-us,PandP.50).gif "Static member")
[GetObservableContext](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regioncontext.getobservablecontext(system.windows.dependencyobject))
Returns an [ObservableObject&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.observableobject%601) wrapper around the RegionContext value. The RegionContext will be set on any views (dependency objects) that are inside the [Views](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.views) collection by the [BindRegionContextToDependencyObjectBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.bindregioncontexttodependencyobjectbehavior) Behavior. The RegionContext will also be set to the control that hosts the Region, by the [SyncRegionContextWithHostBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.syncregioncontextwithhostbehavior) Behavior. If the [ObservableObject&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.observableobject%601) wrapper does not already exist, an empty one will be created. This way, an observer can notify when the value is set for the first time.

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionContext Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regioncontext)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
