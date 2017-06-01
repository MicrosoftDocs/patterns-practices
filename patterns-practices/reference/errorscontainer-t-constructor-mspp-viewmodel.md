---
TOCTitle: 'ErrorsContainer(T) Constructor'
Title: 'ErrorsContainer(T) Constructor (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.ErrorsContainer\`1.\#ctor(System.Action{System.String})'
ms:mtpsurl: 'errorscontainer-t-constructor-mspp-viewmodel.md'
---


# ErrorsContainer&lt;T&gt; Constructor

Initializes a new instance of the [ErrorsContainer&lt;T&gt;](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel) class.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](/patterns-practices/reference/mspp-viewmodel-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public ErrorsContainer(
	Action<string> raiseErrorsChanged
)
```
### Parameters

*raiseErrorsChanged*

Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)&gt;

The action that invoked if when errors are added for an object./&gt; event.

## See Also

[ErrorsContainer&lt;T&gt; Class](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel)

[ErrorsContainer&lt;T&gt; Members](/patterns-practices/reference/errorscontainer-t-members-mspp-viewmodel)

[Microsoft.Practices.Prism.ViewModel Namespace](/patterns-practices/reference/mspp-viewmodel-namespace)


# ErrorsContainer(Of T) Constructor

Initializes a new instance of the [ErrorsContainer(Of T)](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel) class.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](/patterns-practices/reference/mspp-viewmodel-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Sub New ( 
	raiseErrorsChanged As Action(Of String)
)
```
### Parameters

*raiseErrorsChanged*

Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf))

The action that invoked if when errors are added for an object./&gt; event.

## See Also

[ErrorsContainer(Of T) Class](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel)

[ErrorsContainer(Of T) Members](/patterns-practices/reference/errorscontainer-t-members-mspp-viewmodel)

[Microsoft.Practices.Prism.ViewModel Namespace](/patterns-practices/reference/mspp-viewmodel-namespace)
