---
TOCTitle: IsTypeRegistered Method
Title: 'UnityContainerHelper.IsTypeRegistered Method (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.UnityContainerHelper.IsTypeRegistered(Microsoft.Practices.Unity.IUnityContainer,System.Type)'
ms:mtpsurl: 'unitycontainerhelper-istyperegistered-method-mspp-unityextensions.md'
---

# UnityContainerHelper.IsTypeRegistered Method

Returns whether a specified type has a type mapping registered in the container.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions](/patterns-practices/reference/mspp-unityextensions-namespace)  
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public static bool IsTypeRegistered(
	this IUnityContainer container,
	Type type
)
```
```VB
'Declaration
<ExtensionAttribute> 
Public Shared Function IsTypeRegistered ( 
	container As IUnityContainer,
	type As Type
) As Boolean
```

### Parameters

*container*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: IUnityContainer   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The IUnityContainer to check for the type mapping.

*type*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The type to check if there is a type mapping for.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)   
**truetrue** (**True** in Visual Basic) if there is a type mapping registered for *type*.
### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type IUnityContainer. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## Remarks

In order to use this extension method, you first need to add the IUnityContainer extension to the [UnityBootstrapperExtension](/patterns-practices/reference/unitybootstrapperextension-class-mspp-unityextensions).

## See Also

[UnityContainerHelper Class](/patterns-practices/reference/unitycontainerhelper-class-mspp-unityextensions)  
[UnityContainerHelper Members](/patterns-practices/reference/unitycontainerhelper-members-mspp-unityextensions)  
[Microsoft.Practices.Prism.UnityExtensions Namespace](/patterns-practices/reference/mspp-unityextensions-namespace)  