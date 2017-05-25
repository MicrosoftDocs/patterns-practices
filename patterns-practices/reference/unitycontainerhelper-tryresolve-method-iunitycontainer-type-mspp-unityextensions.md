---
TOCTitle: 'TryResolve Method (IUnityContainer, Type)'
Title: 'UnityContainerHelper.TryResolve Method (IUnityContainer, Type) (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.UnityContainerHelper.TryResolve(Microsoft.Practices.Unity.IUnityContainer,System.Type)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419013(v=PandP.50)'
---


# UnityContainerHelper.TryResolve Method (IUnityContainer, Type)

Utility method to try to resolve a service from the container avoiding an exception if the container cannot build the type.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions)
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public static Object TryResolve( this IUnityContainer container, Type typeToResolve )&lt;ExtensionAttribute&gt; Public Shared Function TryResolve ( container As IUnityContainer, typeToResolve As Type ) As Object

### Parameters

container  
Type: IUnityContainer
The cointainer that will be used to resolve the type.

typeToResolve  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
The type to resolve.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
The instance of typeToResolve built up by the container.
### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type IUnityContainer. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[UnityContainerHelper Class](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitycontainerhelper)

[UnityContainerHelper Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.unityextensions.unitycontainerhelper)

[TryResolve Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.unityextensions.unitycontainerhelper.tryresolve)

[Microsoft.Practices.Prism.UnityExtensions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions)
