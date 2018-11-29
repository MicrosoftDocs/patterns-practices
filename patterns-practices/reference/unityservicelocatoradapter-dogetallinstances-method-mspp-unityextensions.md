---
TOCTitle: DoGetAllInstances Method
Title: 'UnityServiceLocatorAdapter.DoGetAllInstances Method (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.UnityServiceLocatorAdapter.DoGetAllInstances(System.Type)'
ms:mtpsurl: 'unityservicelocatoradapter-dogetallinstances-method-mspp-unityextensions.md'
---

# UnityServiceLocatorAdapter.DoGetAllInstances Method

Resolves all the instances of the requested service.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions](/patterns-practices/reference/mspp-unityextensions-namespace)  
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)  
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
Type of service requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;  
Sequence of service instance objects.

```VB
'Declaration
Protected Overrides Function DoGetAllInstances ( 
	serviceType As Type
) As IEnumerable(Of Object)
```

### Parameters

*serviceType*  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)   
Type of service requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))   
Sequence of service instance objects.

## See Also

[UnityServiceLocatorAdapter Class](/patterns-practices/reference/unityservicelocatoradapter-class-mspp-unityextensions)  
[UnityServiceLocatorAdapter Members](/patterns-practices/reference/unityservicelocatoradapter-members-mspp-unityextensions)  
[Microsoft.Practices.Prism.UnityExtensions Namespace](/patterns-practices/reference/mspp-unityextensions-namespace)
