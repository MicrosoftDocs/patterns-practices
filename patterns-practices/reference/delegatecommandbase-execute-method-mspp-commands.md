---
TOCTitle: Execute Method
Title: 'DelegateCommandBase.Execute Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommandBase.Execute(System.Object)'
ms:mtpsurl: 'delegatecommandbase-execute-method-mspp-commands.md'
---

# DelegateCommandBase.Execute Method

Executes the command with the provided parameter by invoking the [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) supplied during construction.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)<br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
protected Task Execute(
	Object parameter
)
```

### Parameters

*parameter*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

### Return Value

Type: [Task](http://msdn.microsoft.com/en-us/library/dd235678)

# DelegateCommandBase.Execute Method

Executes the command with the provided parameter by invoking the [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) supplied during construction.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)<br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Protected Function Execute ( 
	parameter As Object
) As Task
```

### Parameters

*parameter*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

### Return Value

Type: [Task](http://msdn.microsoft.com/en-us/library/dd235678)

## See Also

[DelegateCommandBase Class](/patterns-practices/reference/delegatecommandbase-class-mspp-commands)<br/>
[DelegateCommandBase Members](/patterns-practices/reference/delegatecommandbase-members-mspp-commands)<br/>
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>