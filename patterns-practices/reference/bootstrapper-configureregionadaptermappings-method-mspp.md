---
TOCTitle: ConfigureRegionAdapterMappings Method
Title: 'Bootstrapper.ConfigureRegionAdapterMappings Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.Bootstrapper.ConfigureRegionAdapterMappings'
ms:mtpsurl: 'bootstrapper-configureregionadaptermappings-method-mspp.md'
---

# Bootstrapper.ConfigureRegionAdapterMappings Method

Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.

**Namespace:** [Microsoft.Practices.Prism](mspp-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual RegionAdapterMappings ConfigureRegionAdapterMappings()
```

```VB
'Declaration
Protected Overridable Function ConfigureRegionAdapterMappings As RegionAdapterMappings
```

### Return Value

Type: [RegionAdapterMappings](regionadaptermappings-class-mspp-regions)<br/>
The [RegionAdapterMappings](regionadaptermappings-class-mspp-regions) instance containing all the mappings.

## See Also

[Bootstrapper Class](bootstrapper-class-mspp)

[Bootstrapper Members](bootstrapper-members-mspp)

[Microsoft.Practices.Prism Namespace](mspp-namespace)