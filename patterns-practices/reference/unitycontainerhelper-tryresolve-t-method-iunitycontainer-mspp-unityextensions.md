---
TOCTitle: 'TryResolve(T) Method (IUnityContainer)'
Title: 'UnityContainerHelper.TryResolve(T) Method (IUnityContainer) (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.UnityContainerHelper.TryResolve\`\`1(Microsoft.Practices.Unity.IUnityContainer)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419014(v=PandP.50)'
---

Prism Class Library

UnityContainerHelper.TryResolve&lt;(Of &lt;(T&gt;)&gt;) Method (IUnityContainer)
====================================================================================

Utility method to try to resolve a service from the container avoiding an exception if the container cannot build the type.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions](https://msdn.microsoft.com/n:microsoft.practices.prism.unityextensions)
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public static T TryResolve&lt;T&gt;( this IUnityContainer container ) &lt;ExtensionAttribute&gt; Public Shared Function TryResolve(Of T) ( container As IUnityContainer ) As T

### Parameters

container  
Type: IUnityContainer
The cointainer that will be used to resolve the type.

Type Parameters
---------------

<span id="templatesToggle"></span>
T  
The type to resolve.

### Return Value

Type: T
The instance of T built up by the container.
### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type IUnityContainer. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

See Also
--------


[UnityContainerHelper Class](https://msdn.microsoft.com/t:microsoft.practices.prism.unityextensions.unitycontainerhelper)

[UnityContainerHelper Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.unityextensions.unitycontainerhelper)

[TryResolve Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.unityextensions.unitycontainerhelper.tryresolve)

[Microsoft.Practices.Prism.UnityExtensions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.unityextensions)
