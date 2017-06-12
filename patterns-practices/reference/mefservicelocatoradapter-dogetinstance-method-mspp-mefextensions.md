---
TOCTitle: DoGetInstance Method
Title: 'MefServiceLocatorAdapter.DoGetInstance Method (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.MefServiceLocatorAdapter.DoGetInstance(System.Type,System.String)'
ms:mtpsurl: 'mefservicelocatoradapter-dogetinstance-method-mspp-mefextensions.md'
---

# MefServiceLocatorAdapter.DoGetInstance Method

Resolves all the instances of the requested service.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions](/patterns-practices/reference/mspp-mefextensions-namespace)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected override Object DoGetInstance(
	Type serviceType,
	string key
)
```
```VB
'Declaration
Protected Overrides Function DoGetInstance ( 
	serviceType As Type,
	key As String
) As Object
```

### Parameters

*serviceType*  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
Type of service requested.

*key*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
Name of registered service you want. May be null.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
Sequence of service instance objects.

## See Also
[MefServiceLocatorAdapter Class](/patterns-practices/reference/mefservicelocatoradapter-class-mspp-mefextensions)<br/>
[MefServiceLocatorAdapter Members](/patterns-practices/reference/mefservicelocatoradapter-members-mspp-mefextensions)<br/>
[Microsoft.Practices.Prism.MefExtensions Namespace](/patterns-practices/reference/mspp-mefextensions-namespace)<br/>