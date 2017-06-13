---
TOCTitle: 'DelegateCommand(T) Constructor (Action(T))'
Title: 'DelegateCommand(T) Constructor (Action(T)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.\#ctor(System.Action{\`0})'
ms:mtpsurl: 'delegatecommand-t-constructor-action-t-mspp-commands.md'
---

# DelegateCommand&lt;T&gt; Constructor (Action&lt;T&gt;)

Initializes a new instance of [DelegateCommand&lt;T&gt;](/patterns-practices/reference/delegatecommand-t-class-mspp-commands).

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax
```C#
public DelegateCommand(
	Action<T> executeMethod
)

```
### Parameters

*executeMethod* 

Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands))

Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

## Remarks
[CanExecute(T)](/patterns-practices/reference/delegatecommand-t-canexecute-method-t-mspp-commands) will always return true.

## See Also
[DelegateCommand&lt;T&gt; Class](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)<br/>
[DelegateCommand&lt;T&gt; Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)<br/>
DelegateCommand&lt;T&gt; Overload

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>

# DelegateCommand(Of T) Constructor (Action(Of T))

Initializes a new instance of [DelegateCommand(Of T)](/patterns-practices/reference/delegatecommand-t-class-mspp-commands).

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax
```VB
'Declaration
Public Sub New ( 
	executeMethod As Action(Of T)
)
```

### Parameters

*executeMethod* 

Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands))

Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

## Remarks
[CanExecute(T)](/patterns-practices/reference/delegatecommand-t-canexecute-method-t-mspp-commands) will always return true.

## See Also
[DelegateCommand(Of T) Class](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)<br/>
[DelegateCommand(Of T) Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)<br/>
DelegateCommand(Of T) Overload

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>
