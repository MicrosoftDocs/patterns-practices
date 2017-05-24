---
TOCTitle: 'SetErrors Method (String, IEnumerable(T))'
Title: 'ErrorsContainer(T).SetErrors Method (String, IEnumerable(T)) (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'M:Microsoft.Practices.Prism.ViewModel.ErrorsContainer\`1.SetErrors(System.String,System.Collections.Generic.IEnumerable{\`0})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419027(v=PandP.50)'
---

Prism Class Library

ErrorsContainer&lt;(Of &lt;(T&gt;)&gt;)..::.SetErrors Method (String, IEnumerable&lt;(Of &lt;(T&gt;)&gt;))
==========================================================================================================

Sets the validation errors for the specified property.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](https://msdn.microsoft.com/n:microsoft.practices.prism.viewmodel)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public void SetErrors( string propertyName, IEnumerable&lt;T&gt; newValidationResults )Public Sub SetErrors ( propertyName As String, newValidationResults As IEnumerable(Of T) )
#### Parameters

propertyName  
Type: [System..::.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The name of the property.

<!-- -->

newValidationResults  
Type: [System.Collections.Generic..::.IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([T](https://msdn.microsoft.com/t:microsoft.practices.prism.viewmodel.errorscontainer%601)&gt;)&gt;)
The new validation errors.

Remarks
-------

<span id="remarksToggle"></span> If a change is detected then the errors changed event is raised.

See Also
--------

<span id="seeAlsoToggle"></span>
[ErrorsContainer&lt;(Of &lt;(T&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.viewmodel.errorscontainer%601)

[ErrorsContainer&lt;(Of &lt;(T&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.viewmodel.errorscontainer%601)

[SetErrors Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.viewmodel.errorscontainer%601.seterrors)

[Microsoft.Practices.Prism.ViewModel Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.viewmodel)
