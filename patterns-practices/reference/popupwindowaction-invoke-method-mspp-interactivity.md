---
TOCTitle: Invoke Method
Title: 'PopupWindowAction.Invoke Method (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Interactivity.PopupWindowAction.Invoke(System.Object)'
ms:mtpsurl: 'popupwindowaction-invoke-method-mspp-interactivity.md'
---


# PopupWindowAction.Invoke Method

Displays the child window and collects results for [IInteractionRequest](/patterns-practices/reference/iinteractionrequest-interface-mspp-interactivity-interactionrequest).

**Namespace:** [Microsoft.Practices.Prism.Interactivity](/patterns-practices/reference/mspp-interactivity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
   protected override void Invoke(
	Object parameter
) 
```

```VB
   'Declaration
Protected Overrides Sub Invoke ( 
	parameter As Object
)
```

### Parameters

*parameter*  

Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

The parameter to the action. If the action does not require a parameter, the parameter may be set to a null reference.

## See Also

[PopupWindowAction Class](/patterns-practices/reference/popupwindowaction-class-mspp-interactivity)<br/>
[PopupWindowAction Members](/patterns-practices/reference/popupwindowaction-members-mspp-interactivity)<br/>
[Microsoft.Practices.Prism.Interactivity Namespace](/patterns-practices/reference/mspp-interactivity-namespace)