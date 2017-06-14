---
TOCTitle: IsTypeRegistered Method
Title: 'UnityBootstrapperExtension.IsTypeRegistered Method (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.UnityBootstrapperExtension.IsTypeRegistered(Microsoft.Practices.Unity.IUnityContainer,System.Type)'
ms:mtpsurl: 'unitybootstrapperextension-istyperegistered-method-mspp-unityextensions.md'
---

# UnityBootstrapperExtension.IsTypeRegistered Method

Evaluates if a specified type was registered in the container.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions](/patterns-practices/reference/mspp-unityextensions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public static bool IsTypeRegistered(
	IUnityContainer container,
	Type type
)
```
```VB
'Declaration
Public Shared Function IsTypeRegistered ( 
	container As IUnityContainer,
	type As Type
) As Boolean
```

### Parameters

*container*  
Type: IUnityContainer   
The container to check if the type was registered in.

*type*  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)   
The type to check if it was registered.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)   
trueTruetruetrue (True in Visual Basic) if the type was registered with the container.

## Remarks

 In order to use this extension, you must first call AddNewExtension\`\`1(IUnityContainer) and specify UnityContainerExtension as the extension type.

## See Also

[UnityBootstrapperExtension Class](/patterns-practices/reference/unitybootstrapperextension-class-mspp-unityextensions)<br/>
[UnityBootstrapperExtension Members](/patterns-practices/reference/unitybootstrapperextension-members-mspp-unityextensions)<br/>
[Microsoft.Practices.Prism.UnityExtensions Namespace](/patterns-practices/reference/mspp-unityextensions-namespace)<br/>