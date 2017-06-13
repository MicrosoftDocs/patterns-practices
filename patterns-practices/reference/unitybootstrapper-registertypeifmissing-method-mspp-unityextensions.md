---
TOCTitle: RegisterTypeIfMissing Method
Title: 'UnityBootstrapper.RegisterTypeIfMissing Method (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.UnityBootstrapper.RegisterTypeIfMissing(System.Type,System.Type,System.Boolean)'
ms:mtpsurl: 'unitybootstrapper-registertypeifmissing-method-mspp-unityextensions.md'
---


# UnityBootstrapper.RegisterTypeIfMissing Method

Registers a type in the container only if that type was not already registered.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions](/patterns-practices/reference/mspp-unityextensions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)<br/>
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
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)   
The interface type to register.

*toType*  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)   
The type implementing the interface.

*registerAsSingleton*     
Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)   
Registers the type as a singleton.

## See Also

[UnityBootstrapper Class](/patterns-practices/reference/unitybootstrapper-class-mspp-unityextensions)<br/>
[UnityBootstrapper Members](/patterns-practices/reference/unitybootstrapper-members-mspp-unityextensions)<br/>
[Microsoft.Practices.Prism.UnityExtensions Namespace](/patterns-practices/reference/mspp-unityextensions-namespace)<br/>