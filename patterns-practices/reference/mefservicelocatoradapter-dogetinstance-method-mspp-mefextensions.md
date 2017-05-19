---
TOCTitle: DoGetInstance Method
Title: 'MefServiceLocatorAdapter.DoGetInstance Method (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.MefServiceLocatorAdapter.DoGetInstance(System.Type,System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405832(v=PandP.50)'
---

Prism Class Library

MefServiceLocatorAdapter.DoGetInstance Method
=================================================

Resolves all the instances of the requested service.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>protected override Object DoGetInstance( Type serviceType, string key )Protected Overrides Function DoGetInstance ( serviceType As Type, key As String ) As Object
#### Parameters

serviceType  
Type: [System.Type](http://msdn2.microsoft.com/en-us/library/42892f65)
Type of service requested.

key  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
Name of registered service you want. May be null.

#### Return Value

Type: [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
Sequence of service instance objects.

See Also
--------


[MefServiceLocatorAdapter Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.mefservicelocatoradapter)

[MefServiceLocatorAdapter Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.mefservicelocatoradapter)

[Microsoft.Practices.Prism.MefExtensions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions)
