---
TOCTitle: DoGetAllInstances Method
Title: 'MefServiceLocatorAdapter.DoGetAllInstances Method (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.MefServiceLocatorAdapter.DoGetAllInstances(System.Type)'
ms:mtpsurl: 'mefservicelocatoradapter-dogetallinstances-method-mspp-mefextensions.md'
---

# MefServiceLocatorAdapter.DoGetAllInstances Method

Resolves the instance of the requested service.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions](/patterns-practices/reference/mspp-mefextensions-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected override IEnumerable<Object> DoGetAllInstances(
	Type serviceType
)
```
### Parameters

*serviceType*    
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
Type of instance requested.

### Return Value
Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)[&lt;Object&gt;](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
The requested service instance.

## Syntax

```VB
'Declaration
Protected Overrides Function DoGetAllInstances ( 
	serviceType As Type
) As IEnumerable(Of Object)
```
### Parameters

*serviceType*    
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
Type of instance requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))  
The requested service instance.

## See Also
[MefServiceLocatorAdapter Class](/patterns-practices/reference/mefservicelocatoradapter-class-mspp-mefextensions)  
[MefServiceLocatorAdapter Members](/patterns-practices/reference/mefservicelocatoradapter-members-mspp-mefextensions)  
[Microsoft.Practices.Prism.MefExtensions Namespace](/patterns-practices/reference/mspp-mefextensions-namespace)  