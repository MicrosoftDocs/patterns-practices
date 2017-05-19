---
TOCTitle: IsNavigationTarget Method
Title: 'INavigationAware.IsNavigationTarget Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.INavigationAware.IsNavigationTarget(Microsoft.Practices.Prism.Regions.NavigationContext)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405953(v=PandP.50)'
---

Prism Class Library

# INavigationAware.IsNavigationTarget Method

Called to determine if this instance can handle the navigation request.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
bool IsNavigationTarget(
	NavigationContext navigationContext
)
```


### Parameters

*navigationContext*  

Type: [Microsoft.Practices.Prism.Regions.NavigationContext](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationcontext(v=pandp.50))

The navigation context.

### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)

**trueTrue** (**True** in Visual Basic) if this instance accepts the navigation request; otherwise, **falsefalse** (**False** in Visual Basic).

```VB
'Declaration
Function IsNavigationTarget ( 
	navigationContext As NavigationContext
) As Boolean
```


### Parameters

*navigationContext*  

Type: [Microsoft.Practices.Prism.Regions.NavigationContext](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationcontext(v=pandp.50))

The navigation context.

### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)

**truetrue** (**True** in Visual Basic) if this instance accepts the navigation request; otherwise, **falsefalse** (**False** in Visual Basic).

## See Also


[INavigationAware Interface](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.inavigationaware(v=pandp.50))

[INavigationAware Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.inavigationaware_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
