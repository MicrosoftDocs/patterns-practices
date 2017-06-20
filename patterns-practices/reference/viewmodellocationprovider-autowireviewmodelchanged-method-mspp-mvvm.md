---
TOCTitle: AutoWireViewModelChanged Method
Title: 'ViewModelLocationProvider.AutoWireViewModelChanged Method (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.ViewModelLocationProvider.AutoWireViewModelChanged(Microsoft.Practices.Prism.Mvvm.IView)'
ms:mtpsurl: 'viewmodellocationprovider-autowireviewmodelchanged-method-mspp-mvvm.md'
---

# ViewModelLocationProvider.AutoWireViewModelChanged Method

Automatically looks up the viewmodel that corresponds to the current view, using two strategies: It first looks to see if there is a mapping registered for that view, if not it will fallback to the convention based approach.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax
```C#
public static void AutoWireViewModelChanged(
	IView view
)
```

```VB
'Declaration
Public Shared Sub AutoWireViewModelChanged ( 
	view As IView
)
```

### Parameters

*view*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Mvvm.IView](/patterns-practices/reference/mspp-mvvm-namespace.iview)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The dependency object, typically a view.

## See Also

[ViewModelLocationProvider Class](/patterns-practices/reference/viewmodellocationprovider-class-mspp-mvvm)  
[ViewModelLocationProvider Members](/patterns-practices/reference/viewmodellocationprovider-class-mspp-mvvm_members)  
[Microsoft.Practices.Prism.Mvvm Namespace](/patterns-practices/reference/mspp-mvvm-namespace)