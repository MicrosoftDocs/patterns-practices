---
TOCTitle: Register Method
Title: 'ViewModelLocationProvider.Register Method (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.ViewModelLocationProvider.Register(System.String,System.Func{System.Object})'
ms:mtpsurl: 'viewmodellocationprovider-register-method-mspp-mvvm.md'
---

# ViewModelLocationProvider.Register Method 

Registers the view model factory for the specified view type name.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](/patterns-practices/reference/mspp-mvvm-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax
```C#
public static void Register(
	string viewTypeName,
	Func<Object> factory
)
```

### Parameters

*viewTypeName*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The name of the view type.

*factory*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The viewmodel factory.

## Syntax

```VB
'Declaration
Public Shared Sub Register ( 
	viewTypeName As String,
	factory As Func(Of Object)
)
)
```

### Parameters

*viewTypeName*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The name of the view type.

*factory*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)( Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The viewmodel factory.

## See Also
[ViewModelLocationProvider Class](/patterns-practices/reference/viewmodellocationprovider-class-mspp-mvvm)<br/>
[ViewModelLocationProvider Members](/patterns-practices/reference/viewmodellocationprovider-members-mspp-mvvm)<br/>
[Microsoft.Practices.Prism.Mvvm Namespace](/patterns-practices/reference/mspp-mvvm-namespace)