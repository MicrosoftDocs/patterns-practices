---
TOCTitle: RegisterTypeIfMissing Method
Title: 'UnityBootstrapper.RegisterTypeIfMissing Method (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.UnityBootstrapper.RegisterTypeIfMissing(System.Type,System.Type,System.Boolean)'
ms:mtpsurl: 'unitybootstrapper-registertypeifmissing-method-mspp-unityextensions.md'
---

# UnityBootstrapper.RegisterTypeIfMissing Method

Registers a type in the container only if that type was not already registered.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions](/patterns-practices/reference/mspp-unityextensions-namespace)  
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
protected void RegisterTypeIfMissing(
	Type fromType,
	Type toType,
	bool registerAsSingleton
)
```
```VB
'Declaration
Protected Sub RegisterTypeIfMissing ( 
	fromType As Type,
	toType As Type,
	registerAsSingleton As Boolean
)
```

### Parameters

*fromType*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The interface type to register.

*toType*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The type implementing the interface.

*registerAsSingleton*     
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Registers the type as a singleton.

## See Also

[UnityBootstrapper Class](/patterns-practices/reference/unitybootstrapper-class-mspp-unityextensions)  
[UnityBootstrapper Members](/patterns-practices/reference/unitybootstrapper-members-mspp-unityextensions)  
[Microsoft.Practices.Prism.UnityExtensions Namespace](/patterns-practices/reference/mspp-unityextensions-namespace)  