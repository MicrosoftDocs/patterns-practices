---
TOCTitle: Register Method
Title: 'ViewModelLocationProvider.Register Method (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.ViewModelLocationProvider.Register(System.String,System.Func{System.Object})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mvvm.viewmodellocationprovider.register(v=pandp.50)'
---

# ViewModelLocationProvider.Register Method 

Registers the view model factory for the specified view type name.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mvvm(v=pandp.50))

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
[ViewModelLocationProvider Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mvvm.viewmodellocationprovider(v=pandp.50))

[ViewModelLocationProvider Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mvvm.viewmodellocationprovider_members(v=pandp.50))

[Microsoft.Practices.Prism.Mvvm Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mvvm(v=pandp.50))
