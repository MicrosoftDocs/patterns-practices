---
TOCTitle: Register Method
Title: 'ViewModelLocationProvider.Register Method (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.ViewModelLocationProvider.Register(System.String,System.Func{System.Object})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683961(v=PandP.50)'
---

Prism Class Library

ViewModelLocationProvider..::.Register Method
=============================================

Registers the view model factory for the specified view type name.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](https://msdn.microsoft.com/n:microsoft.practices.prism.mvvm)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public static void Register( string viewTypeName, Func&lt;Object&gt; factory )Public Shared Sub Register ( viewTypeName As String, factory As Func(Of Object) )
#### Parameters

viewTypeName  
Type: [System..::.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The name of the view type.

<!-- -->

factory  
Type: [System..::.Func](http://msdn2.microsoft.com/en-us/library/bb534960)&lt;(Of &lt;([Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)&gt;)&gt;)
The viewmodel factory.

See Also
--------

<span id="seeAlsoToggle"></span>
[ViewModelLocationProvider Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mvvm.viewmodellocationprovider)

[ViewModelLocationProvider Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mvvm.viewmodellocationprovider)

[Microsoft.Practices.Prism.Mvvm Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mvvm)
