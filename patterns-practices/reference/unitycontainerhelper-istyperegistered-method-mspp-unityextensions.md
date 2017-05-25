---
TOCTitle: IsTypeRegistered Method
Title: 'UnityContainerHelper.IsTypeRegistered Method (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.UnityContainerHelper.IsTypeRegistered(Microsoft.Practices.Unity.IUnityContainer,System.Type)'
ms:mtpsurl: 'unitycontainerhelper-istyperegistered-method-mspp-unityextensions.md'
---

Prism Class Library

UnityContainerHelper.IsTypeRegistered Method
================================================

Returns whether a specified type has a type mapping registered in the container.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions)
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public static bool IsTypeRegistered( this IUnityContainer container, Type type )&lt;ExtensionAttribute&gt; Public Shared Function IsTypeRegistered ( container As IUnityContainer, type As Type ) As Boolean

### Parameters

container  
Type: IUnityContainer
The IUnityContainer to check for the type mapping.

type  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
The type to check if there is a type mapping for.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
trueTruetruetrue (True in Visual Basic) if there is a type mapping registered for type.
### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type IUnityContainer. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

Remarks
-------

In order to use this extension method, you first need to add the IUnityContainer extension to the [UnityBootstrapperExtension](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapperextension).

See Also
--------


[UnityContainerHelper Class](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitycontainerhelper)

[UnityContainerHelper Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.unityextensions.unitycontainerhelper)

[Microsoft.Practices.Prism.UnityExtensions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions)
