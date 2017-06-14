---
TOCTitle: IsNavigationTarget Method
Title: 'INavigationAware.IsNavigationTarget Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.INavigationAware.IsNavigationTarget(Microsoft.Practices.Prism.Regions.NavigationContext)'
ms:mtpsurl: 'inavigationaware-isnavigationtarget-method-mspp-regions.md'
---

# INavigationAware.IsNavigationTarget Method

Called to determine if this instance can handle the navigation request.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
bool IsNavigationTarget(
	NavigationContext navigationContext
)
```

### Parameters

*navigationContext*<br/>
Type: [Microsoft.Practices.Prism.Regions.NavigationContext](/patterns-practices/reference/navigationcontext-class-mspp-regions)<br/>
The navigation context.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)<br/>
**truetrue** (**True** in Visual Basic) if this instance accepts the navigation request; otherwise, **falsefalse** (**False** in Visual Basic).


```VB
'Declaration
Function IsNavigationTarget ( 
	navigationContext As NavigationContext
) As Boolean
```

### Parameters

*navigationContext*<br/>
Type: [Microsoft.Practices.Prism.Regions.NavigationContext](/patterns-practices/reference/navigationcontext-class-mspp-regions)<br/>
The navigation context.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)<br/>
**Truetrue** (**True** in Visual Basic) if this instance accepts the navigation request; otherwise, **Falsefalse** (**False** in Visual Basic).

## See Also

[INavigationAware Interface](/patterns-practices/reference/inavigationaware-interface-mspp-regions)<br/>
[INavigationAware Members](/patterns-practices/reference/inavigationaware-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>