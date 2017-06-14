---
TOCTitle: 'TryResolve Method (IUnityContainer, Type)'
Title: 'UnityContainerHelper.TryResolve Method (IUnityContainer, Type) (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.UnityContainerHelper.TryResolve(Microsoft.Practices.Unity.IUnityContainer,System.Type)'
ms:mtpsurl: 'unitycontainerhelper-tryresolve-method-iunitycontainer-type-mspp-unityextensions.md'
---

# UnityContainerHelper.TryResolve Method (IUnityContainer, Type)

Utility method to try to resolve a service from the container avoiding an exception if the container cannot build the type.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions](/patterns-practices/reference/mspp-unityextensions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public static Object TryResolve(
	this IUnityContainer container,
	Type typeToResolve
)
```
```VB
'Declaration
<ExtensionAttribute> 
Public Shared Function TryResolve ( 
	container As IUnityContainer,
	typeToResolve As Type
) As Object
```

### Parameters

*container*  
Type: IUnityContainer   
The cointainer that will be used to resolve the type.

*typeToResolve*  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)   
The type to resolve.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)   
The instance of typeToResolve built up by the container.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type IUnityContainer. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[UnityContainerHelper Class](/patterns-practices/reference/unitycontainerhelper-class-mspp-unityextensions)<br/>
[UnityContainerHelper Members](/patterns-practices/reference/unitycontainerhelper-members-mspp-unityextensions)<br/>
[TryResolve Overload](/patterns-practices/reference/unitycontainerhelper-tryresolve-method-mspp-unityextensions)<br/>
[Microsoft.Practices.Prism.UnityExtensions Namespace](/patterns-practices/reference/mspp-unityextensions-namespace)<br/>