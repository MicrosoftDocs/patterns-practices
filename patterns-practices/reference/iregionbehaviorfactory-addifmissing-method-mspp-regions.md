---
TOCTitle: AddIfMissing Method
Title: 'IRegionBehaviorFactory.AddIfMissing Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionBehaviorFactory.AddIfMissing(System.String,System.Type)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405959(v=PandP.50)'
---

Prism Class Library

IRegionBehaviorFactory.AddIfMissing Method
==============================================

Adds a particular type of RegionBehavior if it was not already registered. the behaviorKey string is used to check if the behavior is already present

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>void AddIfMissing( string behaviorKey, Type behaviorType )Sub AddIfMissing ( behaviorKey As String, behaviorType As Type )
#### Parameters

behaviorKey  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The behavior key that's used to find if a certain behavior is already added.

behaviorType  
Type: [System.Type](http://msdn2.microsoft.com/en-us/library/42892f65)
Type of the behavior to add. .

See Also
--------


[IRegionBehaviorFactory Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehaviorfactory)

[IRegionBehaviorFactory Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.iregionbehaviorfactory)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
