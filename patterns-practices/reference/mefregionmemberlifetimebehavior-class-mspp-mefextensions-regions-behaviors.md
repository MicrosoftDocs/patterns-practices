---
TOCTitle: MefRegionMemberLifetimeBehavior Class
Title: 'MefRegionMemberLifetimeBehavior Class (Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionMemberLifetimeBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431457(v=PandP.50)'
---

# MefRegionMemberLifetimeBehavior Class

Exports the AutoPopulateRegionBehavior using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions.behaviors(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefRegionMemberLifetimeBehavior : RegionMemberLifetimeBehavior
```

```VB
'Declaration
Public Class MefRegionMemberLifetimeBehavior
	Inherits RegionMemberLifetimeBehavior
```

## Remarks

 This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)<br/>
  [Microsoft.Practices.Prism.Regions.RegionBehavior](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionbehavior(v=pandp.50))<br/>
    [Microsoft.Practices.Prism.Regions.Behaviors.RegionMemberLifetimeBehavior](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors.regionmemberlifetimebehavior(v=pandp.50))<br/>
      Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionMemberLifetimeBehavior

## See Also

[MefRegionMemberLifetimeBehavior Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions.behaviors.mefregionmemberlifetimebehavior_members(v=pandp.50))

[Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions.behaviors(v=pandp.50))