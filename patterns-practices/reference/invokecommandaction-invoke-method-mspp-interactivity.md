---
TOCTitle: Invoke Method
Title: 'InvokeCommandAction.Invoke Method (Microsoft.Practices.Prism.Interactivity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Interactivity.InvokeCommandAction.Invoke(System.Object)'
ms:mtpsurl: 'invokecommandaction-invoke-method-mspp-interactivity.md'
---

# InvokeCommandAction.Invoke Method

Executes the command

**Namespace:** [Microsoft.Practices.Prism.Interactivity](/patterns-practices/reference/mspp-interactivity-namespace)

**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll)

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

This parameter is passed to the command; the CommandParameter specified in the CommandParameterProperty is used for command invocation if not null.

## See Also

[InvokeCommandAction Class](/patterns-practices/reference/invokecommandaction-class-mspp-interactivity)<br/>
[InvokeCommandAction Members](/patterns-practices/reference/invokecommandaction-members-mspp-interactivity)<br/>
[Microsoft.Practices.Prism.Interactivity Namespace](/patterns-practices/reference/mspp-interactivity-namespace)