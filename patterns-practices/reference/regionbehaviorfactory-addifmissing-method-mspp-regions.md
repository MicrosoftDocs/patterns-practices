---
TOCTitle: AddIfMissing Method
Title: 'RegionBehaviorFactory.AddIfMissing Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionBehaviorFactory.AddIfMissing(System.String,System.Type)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418944(v=PandP.50)'
---

Prism Class Library

RegionBehaviorFactory.AddIfMissing Method
=============================================

Adds a particular type of RegionBehavior if it was not already registered. The behaviorKey string is used to check if the behavior is already present

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public void AddIfMissing( string behaviorKey, Type behaviorType )Public Sub AddIfMissing ( behaviorKey As String, behaviorType As Type )
#### Parameters

behaviorKey  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The behavior key that's used to find if a certain behavior is already added.

behaviorType  
Type: [System.Type](http://msdn2.microsoft.com/en-us/library/42892f65)
Type of the behavior to add.

#### Implements

[IRegionBehaviorFactory.AddIfMissing(String, Type)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregionbehaviorfactory.addifmissing(system.string%2csystem.type))

See Also
--------


[RegionBehaviorFactory Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionbehaviorfactory)

[RegionBehaviorFactory Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionbehaviorfactory)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
