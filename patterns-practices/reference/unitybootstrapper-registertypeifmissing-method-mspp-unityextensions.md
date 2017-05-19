---
TOCTitle: RegisterTypeIfMissing Method
Title: 'UnityBootstrapper.RegisterTypeIfMissing Method (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.UnityBootstrapper.RegisterTypeIfMissing(System.Type,System.Type,System.Boolean)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419010(v=PandP.50)'
---

Prism Class Library

UnityBootstrapper.RegisterTypeIfMissing Method
==================================================

Registers a type in the container only if that type was not already registered.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions](https://msdn.microsoft.com/n:microsoft.practices.prism.unityextensions)
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


protected void RegisterTypeIfMissing( Type fromType, Type toType, bool registerAsSingleton )Protected Sub RegisterTypeIfMissing ( fromType As Type, toType As Type, registerAsSingleton As Boolean )

### Parameters

fromType  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
The interface type to register.

toType  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
The type implementing the interface.

registerAsSingleton  
Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
Registers the type as a singleton.

See Also
--------


[UnityBootstrapper Class](https://msdn.microsoft.com/t:microsoft.practices.prism.unityextensions.unitybootstrapper)

[UnityBootstrapper Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.unityextensions.unitybootstrapper)

[Microsoft.Practices.Prism.UnityExtensions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.unityextensions)
