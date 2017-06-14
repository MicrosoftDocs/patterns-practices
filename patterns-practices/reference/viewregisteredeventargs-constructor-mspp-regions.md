---
TOCTitle: ViewRegisteredEventArgs Constructor
Title: 'ViewRegisteredEventArgs Constructor (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.ViewRegisteredEventArgs.\#ctor(System.String,System.Func{System.Object})'
ms:mtpsurl: 'viewregisteredeventargs-constructor-mspp-regions.md'
---

# ViewRegisteredEventArgs Constructor

Initializes the ViewRegisteredEventArgs class.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ViewRegisteredEventArgs(
	string regionName,
	Func<Object> getViewDelegate
)
```

### Parameters

*regionName* 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The region name to which the content was registered.

*getViewDelegate*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The content which was registered.

## Syntax

```VB
'Declaration
Public Sub New ( 
	regionName As String,
	getViewDelegate As Func(Of Object)
)
```

### Parameters

*regionName* 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The region name to which the content was registered.

*getViewDelegate*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The content which was registered.


## See Also

[ViewRegisteredEventArgs Class](/patterns-practices/reference/viewregisteredeventargs-class-mspp-regions)  
[ViewRegisteredEventArgs Members](/patterns-practices/reference/viewregisteredeventargs-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  