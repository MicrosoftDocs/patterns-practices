---
TOCTitle: OnUpdatingRegions Method
Title: 'DelayedRegionCreationBehavior.OnUpdatingRegions Method (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior.OnUpdatingRegions(System.Object,System.EventArgs)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405941(v=PandP.50)'
---

Prism Class Library

DelayedRegionCreationBehavior..::.OnUpdatingRegions Method
==========================================================

Called when the [RegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager) is updating it's [Regions](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.regionmanager.regions) collection.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public void OnUpdatingRegions( Object sender, EventArgs e )Public Sub OnUpdatingRegions ( sender As Object, e As EventArgs )
#### Parameters

sender  
Type: [System..::.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
The [RegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager).

<!-- -->

e  
Type: [System..::.EventArgs](http://msdn2.microsoft.com/en-us/library/118wxtk3)
The [EventArgs](http://msdn2.microsoft.com/en-us/library/118wxtk3) instance containing the event data.

Remarks
-------

<span id="remarksToggle"></span> This method has to be public, because it has to be callable using weak references in silverlight and other partial trust environments.

See Also
--------

<span id="seeAlsoToggle"></span>
[DelayedRegionCreationBehavior Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior)

[DelayedRegionCreationBehavior Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
