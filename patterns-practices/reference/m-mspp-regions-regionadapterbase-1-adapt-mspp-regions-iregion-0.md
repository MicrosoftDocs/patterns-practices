---
TOCTitle: Adapt Method
Title: 'RegionAdapterBase(T).Adapt Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionAdapterBase\`1.Adapt(Microsoft.Practices.Prism.Regions.IRegion,\`0)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405991(v=PandP.50)'
---

Prism Class Library

RegionAdapterBase&lt;(Of &lt;(T&gt;)&gt;)..::.Adapt Method
==========================================================

Template method to adapt the object to an [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion).

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected abstract void Adapt( IRegion region, T regionTarget )Protected MustOverride Sub Adapt ( region As IRegion, regionTarget As T )
#### Parameters

region  
Type: [Microsoft.Practices.Prism.Regions..::.IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion)
The new region being used.

<!-- -->

regionTarget  
Type: [T](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionadapterbase%601)
The object to adapt.

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionAdapterBase&lt;(Of &lt;(T&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionadapterbase%601)

[RegionAdapterBase&lt;(Of &lt;(T&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionadapterbase%601)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
