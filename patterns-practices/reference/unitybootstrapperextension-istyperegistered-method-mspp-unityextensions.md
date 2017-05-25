---
TOCTitle: IsTypeRegistered Method
Title: 'UnityBootstrapperExtension.IsTypeRegistered Method (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.UnityBootstrapperExtension.IsTypeRegistered(Microsoft.Practices.Unity.IUnityContainer,System.Type)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.unityextensions.unitybootstrapperextension.istyperegistered(v=pandp.50)'
---

Prism Class Library

UnityBootstrapperExtension.IsTypeRegistered Method
======================================================

Evaluates if a specified type was registered in the container.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions)
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public static bool IsTypeRegistered( IUnityContainer container, Type type )Public Shared Function IsTypeRegistered ( container As IUnityContainer, type As Type ) As Boolean

### Parameters

container  
Type: IUnityContainer
The container to check if the type was registered in.

type  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
The type to check if it was registered.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
trueTruetruetrue (True in Visual Basic) if the type was registered with the container.

Remarks
-------

 In order to use this extension, you must first call AddNewExtension\`\`1(IUnityContainer) and specify UnityContainerExtension as the extension type.

See Also
--------


[UnityBootstrapperExtension Class](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.unitybootstrapperextension)

[UnityBootstrapperExtension Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.unityextensions.unitybootstrapperextension)

[Microsoft.Practices.Prism.UnityExtensions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions)
