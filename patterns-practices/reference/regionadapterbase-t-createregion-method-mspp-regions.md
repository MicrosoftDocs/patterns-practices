---
TOCTitle: CreateRegion Method
Title: 'RegionAdapterBase(T).CreateRegion Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionAdapterBase\`1.CreateRegion'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418935(v=PandP.50)'
---

Prism Class Library

RegionAdapterBase(Of T).CreateRegion Method
=================================================================

Template method to create a new instance of [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50)) that will be used to adapt the object.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

Syntax
------

```C#
    protected abstract IRegion CreateRegion()
```
```VB
    'Declaration
    Protected MustOverride Function CreateRegion As IRegion
```

#### Return Value

Type: [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50))

A new instance of [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50)).

See Also
--------


[RegionAdapterBase(Of T) Class](https://msdn.microsoft.com/en-us/library/gg431546(v=pandp.50))

[RegionAdapterBase(Of T) Members](https://msdn.microsoft.com/en-us/library/gg405501(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
