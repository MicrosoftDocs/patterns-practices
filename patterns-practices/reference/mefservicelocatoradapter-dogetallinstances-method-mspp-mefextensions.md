---
TOCTitle: DoGetAllInstances Method
Title: 'MefServiceLocatorAdapter.DoGetAllInstances Method (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.MefServiceLocatorAdapter.DoGetAllInstances(System.Type)'
ms:mtpsurl: 'mefservicelocatoradapter-dogetallinstances-method-mspp-mefextensions.md'
---

# MefServiceLocatorAdapter.DoGetAllInstances Method

Resolves the instance of the requested service.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
protected override IEnumerable&lt;Object&gt; DoGetAllInstances( Type serviceType )Protected Overrides Function DoGetAllInstances ( serviceType As Type ) As IEnumerable(Of Object)

### Parameters

serviceType  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
Type of instance requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;)&gt;)
The requested service instance.

## See Also
[MefServiceLocatorAdapter Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefservicelocatoradapter)

[MefServiceLocatorAdapter Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.mefservicelocatoradapter)

[Microsoft.Practices.Prism.MefExtensions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions)
