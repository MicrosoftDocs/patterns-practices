---
TOCTitle: MefDelayedRegionCreationBehavior Members
Title: 'MefDelayedRegionCreationBehavior Members (Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefDelayedRegionCreationBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430804(v=PandP.50)'
---

Prism Class Library

MefDelayedRegionCreationBehavior Members
========================================

Include Protected Members
Include Inherited Members

The [MefDelayedRegionCreationBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.regions.behaviors.mefdelayedregioncreationbehavior) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.regions.behaviors.mefdelayedregioncreationbehavior.">MefDelayedRegionCreationBehavior</a></td>
<td><div class="summary">
Initializes a new instance of the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.regions.behaviors.mefdelayedregioncreationbehavior">MefDelayedRegionCreationBehavior</a> class.
</div></td>
</tr>
</tbody>
</table>

Methods
-------

<span id="methodTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.attach">Attach</a></td>
<td><div class="summary">
Start monitoring the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager">RegionManager</a> and the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.targetelement">TargetElement</a> to detect when the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.targetelement">TargetElement</a> becomes part of the Visual Tree. When that happens, the Region will be created and the behavior will <a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.detach">Detach()()()</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior">DelayedRegionCreationBehavior</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.createregion(system.windows.dependencyobject%2csystem.string)">CreateRegion</a></td>
<td><div class="summary">
Method that will create the region, by calling the right <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionadapter">IRegionAdapter</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior">DelayedRegionCreationBehavior</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.detach">Detach</a></td>
<td><div class="summary">
Stop monitoring the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager">RegionManager</a> and the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.targetelement">TargetElement</a>, so that this behavior can be garbage collected.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior">DelayedRegionCreationBehavior</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.onupdatingregions(system.object%2csystem.eventargs)">OnUpdatingRegions</a></td>
<td><div class="summary">
Called when the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager">RegionManager</a> is updating it's <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.regions.regionmanager.regions">Regions</a> collection.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior">DelayedRegionCreationBehavior</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

Properties
----------

<span id="propertyTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.regionmanageraccessor">RegionManagerAccessor</a></td>
<td><div class="summary">
Sets a class that interfaces between the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager">RegionManager</a> 's static properties/events and this behavior, so this behavior can be tested in isolation.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior">DelayedRegionCreationBehavior</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430804.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.targetelement">TargetElement</a></td>
<td><div class="summary">
The element that will host the Region.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior">DelayedRegionCreationBehavior</a>.)</td>
</tr>
</tbody>
</table>

See Also
--------

<span id="seeAlsoToggle"></span>
[MefDelayedRegionCreationBehavior Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.regions.behaviors.mefdelayedregioncreationbehavior)

[Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.regions.behaviors)
