---
TOCTitle: ConfirmNavigationRequest Method
Title: 'IConfirmNavigationRequest.ConfirmNavigationRequest Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IConfirmNavigationRequest.ConfirmNavigationRequest(Microsoft.Practices.Prism.Regions.NavigationContext,System.Action{System.Boolean})'
ms:mtpsurl: 'iconfirmnavigationrequest-confirmnavigationrequest-method-mspp-regions.md'
---

# IConfirmNavigationRequest.ConfirmNavigationRequest Method

Determines whether this instance accepts being navigated away from.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespaces)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
void ConfirmNavigationRequest(
	NavigationContext navigationContext,
	Action<bool> continuationCallback
)
```

### Parameters

*navigationContext*  
Type: [Microsoft.Practices.Prism.Regions.NavigationContext](/patterns-practices/reference/navigationcontext-class-mspp-regions)  
The navigation context.

*continuationCallback*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)&gt;  
The callback to indicate when navigation can proceed.



```VB
'Declaration
Sub ConfirmNavigationRequest ( 
	navigationContext As NavigationContext,
	continuationCallback As Action(Of Boolean)
)
```

### Parameters

*navigationContext*  
Type: [Microsoft.Practices.Prism.Regions.NavigationContext](/patterns-practices/reference/navigationcontext-class-mspp-regions)  
The navigation context.

*continuationCallback*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50))  
The callback to indicate when navigation can proceed.

## Remarks

 Implementors of this method do not need to invoke the callback before this method is completed, but they must ensure the callback is eventually invoked.

## See Also

[IConfirmNavigationRequest Interface](/patterns-practices/reference/iconfirmnavigationrequest-interface-mspp-regions)

[IConfirmNavigationRequest Members](/patterns-practices/reference/iconfirmnavigationrequest-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespaces)
