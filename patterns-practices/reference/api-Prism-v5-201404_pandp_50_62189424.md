---
TOCTitle: 'SetProperty(T) Method'
Title: 'BindableBase.SetProperty(T) Method (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.BindableBase.SetProperty\`\`1(\`\`0@,\`\`0,System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736263(v=PandP.50)'
---

Prism Class Library

BindableBase..::.SetProperty&lt;(Of &lt;(T&gt;)&gt;) Method
===========================================================

Checks if a property already matches a desired value. Sets the property and notifies listeners only when necessary.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](https://msdn.microsoft.com/n:microsoft.practices.prism.mvvm)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected virtual bool SetProperty&lt;T&gt;( ref T storage, T value, string propertyName = null ) Protected Overridable Function SetProperty(Of T) ( ByRef storage As T, value As T, Optional propertyName As String = Nothing ) As Boolean
#### Parameters

storage  
Type: T%
Reference to a property with both getter and setter.

<!-- -->

value  
Type: T
Desired value for the property.

<!-- -->

propertyName (Optional)  
Type: [System..::.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
Name of the property used to notify listeners. This value is optional and can be provided automatically when invoked from compilers that support CallerMemberName.

Type Parameters
---------------

<span id="templatesToggle"></span>
T  
Type of the property.

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
True if the value was changed, false if the existing value matched the desired value.

See Also
--------

<span id="seeAlsoToggle"></span>
[BindableBase Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mvvm.bindablebase)

[BindableBase Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mvvm.bindablebase)

[Microsoft.Practices.Prism.Mvvm Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mvvm)
