---
TOCTitle: SetDefaultViewTypeToViewModelTypeResolver Method
Title: 'ViewModelLocationProvider.SetDefaultViewTypeToViewModelTypeResolver Method (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.ViewModelLocationProvider.SetDefaultViewTypeToViewModelTypeResolver(System.Func{System.Type,System.Type})'
ms:mtpsurl: 'viewmodellocationprovider-setdefaultviewtypetoviewmodeltyperesolver-method-mspp-mvvm.md'
---


# ViewModelLocationProvider.SetDefaultViewTypeToViewModelTypeResolver Method

Sets the default view type to view model type resolver.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](/patterns-practices/reference/mspp-mvvm-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public static void SetDefaultViewTypeToViewModelTypeResolver(
	Func<Type, Type> viewTypeToViewModelTypeResolver
)
```

```VB
'Declaration
Public Shared Sub SetDefaultViewTypeToViewModelTypeResolver ( 
	viewTypeToViewModelTypeResolver As Func(Of Type, Type)
)
```

### Parameters

*viewTypeToViewModelTypeResolver*

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)(Of ([Type](http://msdn.microsoft.com/en-us/library/42892f65), [Type](http://msdn.microsoft.com/en-us/library/42892f65)))

The view type to view model type resolver.

## See Also

[ViewModelLocationProvider Class](/patterns-practices/reference/viewmodellocationprovider-class-mspp-mvvm)

[ViewModelLocationProvider Members](/patterns-practices/reference/viewmodellocationprovider-members-mspp-mvvm)

[Microsoft.Practices.Prism.Mvvm Namespace](/patterns-practices/reference/mspp-mvvm-namespace)
