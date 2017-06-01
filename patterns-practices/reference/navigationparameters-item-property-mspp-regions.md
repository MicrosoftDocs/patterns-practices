---
TOCTitle: Item Property
Title: 'NavigationParameters.Item Property (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.NavigationParameters.Item(System.String)'
ms:mtpsurl: 'navigationparameters-item-property-mspp-regions.md'
---

# NavigationParameters.Item Property

Gets the [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf) with the specified key.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public Object this[
	string key
] { get; }
```

### Parameters

*key*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

The value for the specified key, or **null**a null reference (**Nothing** in Visual Basic) if the query does not contain such a key.

```VB
'Declaration
Public ReadOnly Default Property Item ( 
	key As String
) As Object
	Get
```

### Parameters

*key*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

The value for the specified key, or **Nothing**a null reference (**Nothing** in Visual Basic) if the query does not contain such a key.

## See Also

[NavigationParameters Class](/patterns-practices/reference/navigationparameters-class-mspp-regions)

[NavigationParameters Members](/patterns-practices/reference/navigationparameters-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)
