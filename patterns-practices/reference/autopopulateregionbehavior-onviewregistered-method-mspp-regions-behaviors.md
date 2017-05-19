---
TOCTitle: OnViewRegistered Method
Title: 'AutoPopulateRegionBehavior.OnViewRegistered Method (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Behaviors.AutoPopulateRegionBehavior.OnViewRegistered(System.Object,Microsoft.Practices.Prism.Regions.ViewRegisteredEventArgs)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405936(v=PandP.50)'
---

# AutoPopulateRegionBehavior.OnViewRegistered Method

Handler of the event that fires when a new viewtype is registered to the registry.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors(v=pandp.50))

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

#### Parameters

sender

    Type: [System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)

*e*

    Type: [Microsoft.Practices.Prism.Regions.ViewRegisteredEventArgs](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.viewregisteredeventargs(v=pandp.50))

## Remarks

Although this is a public method to support Weak Delegates in Silverlight, it should not be called by the user.

## See Also

[AutoPopulateRegionBehavior Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors.autopopulateregionbehavior(v=pandp.50))

[AutoPopulateRegionBehavior Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors.autopopulateregionbehavior_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors(v=pandp.50))
