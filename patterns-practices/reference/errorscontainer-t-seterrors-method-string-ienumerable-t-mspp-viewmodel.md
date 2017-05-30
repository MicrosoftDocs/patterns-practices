---
TOCTitle: 'SetErrors Method (String, IEnumerable(T))'
Title: 'ErrorsContainer(T).SetErrors Method (String, IEnumerable(T)) (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.ErrorsContainer\`1.SetErrors(System.String,System.Collections.Generic.IEnumerable{\`0})'
ms:mtpsurl: 'errorscontainer-t-seterrors-method-string-ienumerable-t-mspp-viewmodel.md'
---

# ErrorsContainer&lt;T&gt;.SetErrors Method (String, IEnumerable&lt;T&gt;)

Sets the validation errors for the specified property.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](mspp-viewmodel-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public void SetErrors(
	string propertyName,
	IEnumerable<T> newValidationResults
)
```
### Parameters

*propertyName* 

	Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
	
	The name of the property.

*newValidationResults*  

	Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)<[T](errorscontainer-t-class-mspp-viewmodel)>
	
	The new validation errors.

## Remarks

If a change is detected then the errors changed event is raised.

## See Also

[ErrorsContainer&lt;T&gt; Class](errorscontainer-t-class-mspp-viewmodel)

[ErrorsContainer&lt;T&gt; Members](errorscontainer-t-members-mspp-viewmodel)

[SetErrors Overload](errorscontainer-t-seterrors-method-mspp-viewmodel)

[Microsoft.Practices.Prism.ViewModel Namespace](mspp-viewmodel-namespace)

# ErrorsContainer(Of T).SetErrors Method (String, IEnumerable(Of T))

Sets the validation errors for the specified property.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](mspp-viewmodel-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB
	'Declaration
Public Sub SetErrors ( 
	propertyName As String,
	newValidationResults As IEnumerable(Of T)
)
``` 

### Parameters

*propertyName* 

	Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
	
	The name of the property.

*newValidationResults*  

	Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [T](errorscontainer-t-class-mspp-viewmodel))
	
	The new validation errors.

## Remarks
If a change is detected then the errors changed event is raised.

## See Also
[ErrorsContainer(Of T) Class](errorscontainer-t-class-mspp-viewmodel)<br/>
[ErrorsContainer(Of T) Members](errorscontainer-t-members-mspp-viewmodel)<br/>
[SetErrors Overload](errorscontainer-t-seterrors-method-mspp-viewmodel)<br/>
[Microsoft.Practices.Prism.ViewModel Namespace](mspp-viewmodel-namespace)
