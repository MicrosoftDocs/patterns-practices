---
TOCTitle: OnViewRegistered Method
Title: 'AutoPopulateRegionBehavior.OnViewRegistered Method (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Behaviors.AutoPopulateRegionBehavior.OnViewRegistered(System.Object,Microsoft.Practices.Prism.Regions.ViewRegisteredEventArgs)'
ms:mtpsurl: 'autopopulateregionbehavior-onviewregistered-method-mspp-regions-behaviors.md'
---

# AutoPopulateRegionBehavior.OnViewRegistered Method

Handler of the event that fires when a new viewtype is registered to the registry.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](mspp-regions-behaviors-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public virtual void OnViewRegistered(
	Object sender,
	ViewRegisteredEventArgs e
)
```

```VB
'Declaration
Public Overridable Sub OnViewRegistered ( 
	sender As Object,
	e As ViewRegisteredEventArgs
)
```
### Parameters

sender

    Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

*e*

    Type: [Microsoft.Practices.Prism.Regions.ViewRegisteredEventArgs](viewregisteredeventargs-class-mspp-regions)

## Remarks

Although this is a public method to support Weak Delegates in Silverlight, it should not be called by the user.

## See Also

[AutoPopulateRegionBehavior Class](autopopulateregionbehavior-class-mspp-regions-behaviors)

[AutoPopulateRegionBehavior Members](autopopulateregionbehavior-members-mspp-regions-behaviors)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](mspp-regions-behaviors-namespace)
