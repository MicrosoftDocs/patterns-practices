---
TOCTitle: OnUpdatingRegions Method
Title: 'RegionManagerRegistrationBehavior.OnUpdatingRegions Method (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Behaviors.RegionManagerRegistrationBehavior.OnUpdatingRegions(System.Object,System.EventArgs)'
ms:mtpsurl: 'regionmanagerregistrationbehavior-onupdatingregions-method-mspp-regions-behaviors.md'
---

# RegionManagerRegistrationBehavior.OnUpdatingRegions Method

This event handler gets called when a RegionManager is requering the instances of a region to be registered if they are not already.

### Remarks

Although this is a public method to support Weak Delegates in Silverlight, it should not be called by the user.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](mspp-regions-behaviors-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void OnUpdatingRegions(
	Object sender,
	EventArgs e
)
```

```VB
'Declaration
Public Sub OnUpdatingRegions ( 
	sender As Object,
	e As EventArgs
)
```


### Parameters

*sender*

	Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
	The sender.

*e*

	Type: [System.EventArgs](http://msdn.microsoft.com/en-us/library/118wxtk3)
	The arguments.

## See Also

[RegionManagerRegistrationBehavior Class](regionmanagerregistrationbehavior-class-mspp-regions-behaviors.md)

[RegionManagerRegistrationBehavior Members](regionmanagerregistrationbehavior-members-mspp-regions-behaviors.md)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](mspp-regions-behaviors-namespace.md)
