---
TOCTitle: 'DelegateCommand(T) Constructor (Action(T), Func(T, Boolean))'
Title: 'DelegateCommand(T) Constructor (Action(T), Func(T, Boolean)) (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.DelegateCommand\`1.\#ctor(System.Action{\`0},System.Func{\`0,System.Boolean})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg406162(v=PandP.50)'
---

Prism Class Library

# DelegateCommand&lt;T&gt; Constructor (Action&lt;T&gt;, Func&lt;T, Boolean&gt;)

Initializes a new instance of [DelegateCommand&lt;T&gt;](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50)).

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public DelegateCommand(
	Action<T> executeMethod,
	Func<T, bool> canExecuteMethod
)
```

#### Parameters

*executeMethod*  

	Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;[T](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50))&gt;

	Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

*canExecuteMethod*

	Type: [System.Func](http://msdn2.microsoft.com/en-us/library/bb549151)&lt;[T](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50)), [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)&gt;

	Delegate to execute when CanExecute is called on the command. This can be null.

## Exceptions

| Exception | Condition |
| [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | When both *executeMethod* and *canExecuteMethod* ar **null**a null reference (**Nothing** in Visual Basic). |

## See Also

[DelegateCommand&lt;T&gt; Class](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50))

[DelegateCommand&lt;T&gt; Members](https://msdn.microsoft.com/en-us/library/gg430763(v=pandp.50))

DelegateCommand&lt;T&gt; Overload

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))

# DelegateCommand(Of T) Constructor (Action(Of T), Func(Of T, Boolean))

Initializes a new instance of [DelegateCommand(Of T)](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50)).

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Sub New ( 
	executeMethod As Action(Of T),
	canExecuteMethod As Func(Of T, Boolean)
)
```

#### Parameters

*executeMethod*  

	Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)(Of [T](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50)))

	Delegate to execute when Execute is called on the command. This can be null to just hook up a CanExecute delegate.

*canExecuteMethod*

	Type: [System.Func](http://msdn2.microsoft.com/en-us/library/bb549151)(Of [T](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50)), [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50))

	Delegate to execute when CanExecute is called on the command. This can be null.

## Exceptions

| Exception | Condition |
| [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | When both *executeMethod* and *canExecuteMethod* ar **null**a null reference (**Nothing** in Visual Basic). |

## See Also

[DelegateCommand(Of T) Class](https://msdn.microsoft.com/en-us/library/gg431410(v=pandp.50))

[DelegateCommand(Of T) Members](https://msdn.microsoft.com/en-us/library/gg430763(v=pandp.50))

DelegateCommand(Of T) Overload

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))