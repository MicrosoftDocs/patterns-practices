---
TOCTitle: GetErrors Method
Title: 'ErrorsContainer(T).GetErrors Method (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.ErrorsContainer\`1.GetErrors(System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419026(v=PandP.50)'
---

Prism Class Library

ErrorsContainer&lt;(Of &lt;(T&gt;)&gt;).GetErrors Method
============================================================

Gets the validation errors for a specified property.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](https://msdn.microsoft.com/n:microsoft.practices.prism.viewmodel)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


public IEnumerable&lt;T&gt; GetErrors( string propertyName )Public Function GetErrors ( propertyName As String ) As IEnumerable(Of T)

### Parameters

propertyName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The name of the property.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([T](https://msdn.microsoft.com/t:microsoft.practices.prism.viewmodel.errorscontainer%601)&gt;)&gt;)
The validation errors of type T for the property.

See Also
--------


[ErrorsContainer&lt;(Of &lt;(T&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.viewmodel.errorscontainer%601)

[ErrorsContainer&lt;(Of &lt;(T&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.viewmodel.errorscontainer%601)

[Microsoft.Practices.Prism.ViewModel Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.viewmodel)
