---
TOCTitle: 'SetErrors Method (String, IEnumerable(T))'
Title: 'ErrorsContainer(T).SetErrors Method (String, IEnumerable(T)) (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.ErrorsContainer\`1.SetErrors(System.String,System.Collections.Generic.IEnumerable{\`0})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419027(v=PandP.50)'
---

Prism Class Library

# ErrorsContainer&lt;T&gt;.SetErrors Method (String, IEnumerable&lt;T&gt;)

Sets the validation errors for the specified property.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public void SetErrors(
	string propertyName,
	IEnumerable<T> newValidationResults
)
```


#### Parameters

*propertyName* 

	Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
	
	The name of the property.

*newValidationResults*  

	Type: [System.Collections.Generic.IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)<[T](https://msdn.microsoft.com/en-us/library/gg431577(v=pandp.50))>
	
	The new validation errors.

## Remarks

If a change is detected then the errors changed event is raised.

## See Also

[ErrorsContainer&lt;T&gt; Class](https://msdn.microsoft.com/en-us/library/gg431577(v=pandp.50))

[ErrorsContainer&lt;T&gt; Members](https://msdn.microsoft.com/en-us/library/gg405531(v=pandp.50))

[SetErrors Overload](https://msdn.microsoft.com/en-us/library/gg419152(v=pandp.50))

[Microsoft.Practices.Prism.ViewModel Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel(v=pandp.50))



# ErrorsContainer(Of T).SetErrors Method (String, IEnumerable(Of T))

Sets the validation errors for the specified property.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB
	'Declaration
Public Sub SetErrors ( 
	propertyName As String,
	newValidationResults As IEnumerable(Of T)
)
``` 
#### Parameters

*propertyName* 

	Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
	
	The name of the property.

*newValidationResults*  

	Type: [System.Collections.Generic.IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)(Of [T](https://msdn.microsoft.com/en-us/library/gg431577(v=pandp.50)))
	
	The new validation errors.

## Remarks
If a change is detected then the errors changed event is raised.

## See Also
[ErrorsContainer(Of T) Class](https://msdn.microsoft.com/en-us/library/gg431577(v=pandp.50))<br/>
[ErrorsContainer(Of T) Members](https://msdn.microsoft.com/en-us/library/gg405531(v=pandp.50))<br/>
[SetErrors Overload](https://msdn.microsoft.com/en-us/library/gg419152(v=pandp.50))<br/>
[Microsoft.Practices.Prism.ViewModel Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.viewmodel(v=pandp.50))
