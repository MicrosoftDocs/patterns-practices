---
TOCTitle: ConfigureRegionAdapterMappings Method
Title: 'Bootstrapper.ConfigureRegionAdapterMappings Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.Bootstrapper.ConfigureRegionAdapterMappings'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431148(v=PandP.50)'
---

# Bootstrapper.ConfigureRegionAdapterMappings Method

Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual RegionAdapterMappings ConfigureRegionAdapterMappings()
```

```VB
'Declaration
Protected Overridable Function ConfigureRegionAdapterMappings As RegionAdapterMappings
```

#### Return Value

Type: [RegionAdapterMappings](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionadaptermappings(v=pandp.50))<br/>
The [RegionAdapterMappings](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionadaptermappings(v=pandp.50)) instance containing all the mappings.

## See Also

[Bootstrapper Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper(v=pandp.50))

[Bootstrapper Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper_members(v=pandp.50))

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism(v=pandp.50))