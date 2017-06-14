---
TOCTitle: 'RegionCreationException Constructor (String, Exception)'
Title: 'RegionCreationException Constructor (String, Exception) (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Behaviors.RegionCreationException.\#ctor(System.String,System.Exception)'
ms:mtpsurl: 'regioncreationexception-constructor-mspp-regions-behaviors.md'
---

# RegionCreationException Constructor (String, Exception)

Initializes a new instance of the [RegionCreationException](/patterns-practices/reference/regioncreationexception-class-mspp-regions-behaviors) class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public RegionCreationException(
	string message,
	Exception inner
)
```

```VB
''Declaration
Public Sub New ( 
	message As String,
	inner As Exception
)
```

### Parameters

*message*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The error message that explains the reason for the exception.

*inner*  
Type: [System.Exception](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)  
The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified.

## See Also

[RegionCreationException Class](/patterns-practices/reference/regioncreationexception-class-mspp-regions-behaviors)<br/>
[RegionCreationException Members](/patterns-practices/reference/regioncreationexception-members-mspp-regions-behaviors)<br/>
RegionCreationException Overload

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)<br/>