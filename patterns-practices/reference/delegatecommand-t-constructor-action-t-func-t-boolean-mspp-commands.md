---
TOCTitle: 'DelegateCommand(T) Constructor (Action(T), Func(T, Boolean))'
Title: 'DelegateCommand(T) Constructor (Action(T), Func(T, Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.\#ctor(System.Action{\`0},System.Func{\`0,System.Boolean})'
ms:mtpsurl: 'delegatecommand-t-constructor-action-t-func-t-boolean-mspp-commands.md'
---


# DelegateCommand&lt;T&gt; Constructor (Action&lt;T&gt;, Func&lt;T, Boolean&gt;)

Initializes a new instance of [DelegateCommand&lt;T&gt;](/patterns-practices/reference/delegatecommand-t-class-mspp-commands).

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public DelegateCommand(
	Action<T> executeMethod,
	Func<T, bool> canExecuteMethod
)
```

### Parameters

*executeMethod*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)&gt;  
Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

*canExecuteMethod*  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)&lt;[T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands), [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)&gt;  
Delegate to execute when CanExecute is called on the command. This can be null.

## Exceptions

<table>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)</td>
<td>When both *executeMethod* and *canExecuteMethod* ar **null**a null reference (**Nothing** in Visual Basic).</td>
</tr>
</tbody>
</table>

## See Also

[DelegateCommand&lt;T&gt; Class](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)  
[DelegateCommand&lt;T&gt; Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)  
DelegateCommand&lt;T&gt; Overload  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  

# DelegateCommand(Of T) Constructor (Action(Of T), Func(Of T, Boolean))

Initializes a new instance of [DelegateCommand(Of T)](/patterns-practices/reference/delegatecommand-t-class-mspp-commands).

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Sub New ( 
	executeMethod As Action(Of T),
	canExecuteMethod As Func(Of T, Boolean)
)
```

### Parameters

*executeMethod*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands))  
Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

*canExecuteMethod*  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb549151)(Of [T](/patterns-practices/reference/delegatecommand-t-class-mspp-commands), [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50))  
Delegate to execute when CanExecute is called on the command. This can be null.

## Exceptions

<table>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)</td>
<td>When both *executeMethod* and *canExecuteMethod* ar **Nothing**a null reference (**Nothing** in Visual Basic).</td>
</tr>
</tbody>
</table>


## See Also

[DelegateCommand(Of T) Class](/patterns-practices/reference/delegatecommand-t-class-mspp-commands)  
[DelegateCommand(Of T) Members](/patterns-practices/reference/delegatecommand-t-members-mspp-commands)  
DelegateCommand(Of T) Overload  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)