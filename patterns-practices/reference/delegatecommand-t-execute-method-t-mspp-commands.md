---
TOCTitle: 'Execute Method (T)'
Title: 'DelegateCommand(T).Execute Method (T) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.Execute(\`0)'
ms:mtpsurl: 'delegatecommand-t-execute-method-t-mspp-commands.md'
---

# DelegateCommand&lt;T&gt;.Execute Method (T)

Executes the command and invokes the [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) provided during construction.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual Task Execute(
	T parameter
)
```

### Parameters

*parameter*  
Type: [T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)

Data used by the command.

### Return Value

Type: [Task](http://msdn.microsoft.com/en-us/library/dd235678)

## See Also

[DelegateCommand&lt;T&gt; Class](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)

[DelegateCommand&lt;T&gt; Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)

[Execute Overload](/patterns-practices/reference/delegatecommand-t-execute-method-mspp-commands)

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)


# DelegateCommand(Of T).Execute Method (T)

Executes the command and invokes the [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) provided during construction.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Overridable Function Execute ( 
	parameter As T
) As Task
```

### Parameters

*parameter*  
Type: [T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)

Data used by the command.

### Return Value

Type: [Task](http://msdn.microsoft.com/en-us/library/dd235678)

## See Also

[DelegateCommand(Of T) Class](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)

[DelegateCommand(Of T) Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)

[Execute Overload](/patterns-practices/reference/delegatecommand-t-execute-method-mspp-commands)

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)
