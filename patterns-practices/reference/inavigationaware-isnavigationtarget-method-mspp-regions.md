---
TOCTitle: IsNavigationTarget Method
Title: 'INavigationAware.IsNavigationTarget Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.INavigationAware.IsNavigationTarget(Microsoft.Practices.Prism.Regions.NavigationContext)'
ms:mtpsurl: 'inavigationaware-isnavigationtarget-method-mspp-regions.md'
---

# INavigationAware.IsNavigationTarget Method

Called to determine if this instance can handle the navigation request.

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace.md)

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

Type: [Microsoft.Practices.Prism.Regions.NavigationContext](navigationcontext-class-mspp-regions.md)

The navigation context.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

**trueTrue** (**True** in Visual Basic) if this instance accepts the navigation request; otherwise, **falsefalse** (**False** in Visual Basic).

```VB
'Declaration
Function IsNavigationTarget ( 
	navigationContext As NavigationContext
) As Boolean
```
### Parameters

*navigationContext*  

Type: [Microsoft.Practices.Prism.Regions.NavigationContext](navigationcontext-class-mspp-regions.md)

The navigation context.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

**truetrue** (**True** in Visual Basic) if this instance accepts the navigation request; otherwise, **falsefalse** (**False** in Visual Basic).

## See Also
[INavigationAware Interface](inavigationaware-interface-mspp-regions.md)

[INavigationAware Members](inavigationaware-members-mspp-regions.md)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace.md)
