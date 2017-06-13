---
TOCTitle: GetErrors Method
Title: 'ErrorsContainer(T).GetErrors Method (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.ErrorsContainer\`1.GetErrors(System.String)'
ms:mtpsurl: 'errorscontainer-t-geterrors-method-mspp-viewmodel.md'
---

# ErrorsContainer&lt;T&gt;.GetErrors Method

Gets the validation errors for a specified property.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](/patterns-practices/reference/mspp-viewmodel-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public IEnumerable<T> GetErrors(
	string propertyName
)
```

### Parameters

*propertyName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)   
The name of the property.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[T](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel)&gt;  
The validation errors of type T for the property.

## See Also

[ErrorsContainer&lt;T&gt; Class](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel)<br/>
[ErrorsContainer&lt;T&gt; Members](/patterns-practices/reference/errorscontainer-t-members-mspp-viewmodel)<br/>
[Microsoft.Practices.Prism.ViewModel Namespace](/patterns-practices/reference/mspp-viewmodel-namespace)<br/>


# ErrorsContainer(Of T).GetErrors Method

Gets the validation errors for a specified property.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](/patterns-practices/reference/mspp-viewmodel-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Function GetErrors ( 
	propertyName As String
) As IEnumerable(Of T)
```

### Parameters

*propertyName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)   
The name of the property.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [T](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel))  
The validation errors of type T for the property.

## See Also

[ErrorsContainer(Of T) Class](/patterns-practices/reference/errorscontainer-t-class-mspp-viewmodel)<br/>
[ErrorsContainer(Of T) Members](/patterns-practices/reference/errorscontainer-t-members-mspp-viewmodel)<br/>
[Microsoft.Practices.Prism.ViewModel Namespace](/patterns-practices/reference/mspp-viewmodel-namespace)