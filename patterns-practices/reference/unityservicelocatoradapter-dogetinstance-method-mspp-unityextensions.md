---
TOCTitle: DoGetInstance Method
Title: 'UnityServiceLocatorAdapter.DoGetInstance Method (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.UnityServiceLocatorAdapter.DoGetInstance(System.Type,System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419016(v=PandP.50)'
---

Prism Class Library

UnityServiceLocatorAdapter.DoGetInstance Method
===================================================

Resolves the instance of the requested service.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions](https://msdn.microsoft.com/n:microsoft.practices.prism.unityextensions)
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>protected override Object DoGetInstance( Type serviceType, string key )Protected Overrides Function DoGetInstance ( serviceType As Type, key As String ) As Object

### Parameters

serviceType  
Type: [System.Type](http://msdn2.microsoft.com/en-us/library/42892f65)
Type of instance requested.

key  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
Name of registered service you want. May be null.

### Return Value

Type: [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
The requested service instance.

See Also
--------


[UnityServiceLocatorAdapter Class](https://msdn.microsoft.com/t:microsoft.practices.prism.unityextensions.unityservicelocatoradapter)

[UnityServiceLocatorAdapter Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.unityextensions.unityservicelocatoradapter)

[Microsoft.Practices.Prism.UnityExtensions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.unityextensions)
