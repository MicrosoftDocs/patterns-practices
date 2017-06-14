---
TOCTitle: 'TryResolve(T) Method (IServiceLocator)'
Title: 'ServiceLocatorExtensions.TryResolve(T) Method (IServiceLocator) (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ServiceLocatorExtensions.TryResolve\`\`1(Microsoft.Practices.ServiceLocation.IServiceLocator)'
ms:mtpsurl: 'servicelocatorextensions-tryresolve-t-method-iservicelocator-mspp.md'
---

# ServiceLocatorExtensions.TryResolve&lt;T&gt; Method (IServiceLocator)

Attempts to resolve specified type from the underlying IServiceLocator.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static T TryResolve<T>(
	this IServiceLocator locator
)
where T : class
```

### Parameters

*locator*
  
Type: IServiceLocator

Locator to use in resolving.

## Type Parameters


*T* 
 
Type to resolve.

### Return Value

Type: T

T or null

### Usage Note

In Visual Basic and C#, you can call this method as an instance method on any object of type IServiceLocator. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## Remarks

 This will return null on any ActivationException.

## See Also

[ServiceLocatorExtensions Class](/patterns-practices/reference/servicelocatorextensions-class-mspp)  
[ServiceLocatorExtensions Members](/patterns-practices/reference/servicelocatorextensions-members-mspp)  
[TryResolve Overload](/patterns-practices/reference/servicelocatorextensions-tryresolve-method-iservicelocator-type-mspp)  
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)  

# ServiceLocatorExtensions.TryResolve(Of T) Method (IServiceLocator)

Attempts to resolve specified type from the underlying IServiceLocator.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
<ExtensionAttribute> 
Public Shared Function TryResolve(Of T As Class) ( 
	locator As IServiceLocator
) As T
```

### Parameters

*locator*
  
Type: IServiceLocator

Locator to use in resolving.

## Type Parameters


*T* 
 
Type to resolve.

### Return Value

Type: T

T or null

### Usage Note

In Visual Basic and C#, you can call this method as an instance method on any object of type IServiceLocator. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## Remarks

 This will return null on any ActivationException.

## See Also

[ServiceLocatorExtensions Class](/patterns-practices/reference/servicelocatorextensions-class-mspp)  
[ServiceLocatorExtensions Members](/patterns-practices/reference/servicelocatorextensions-members-mspp)  
[TryResolve Overload](/patterns-practices/reference/servicelocatorextensions-tryresolve-method-iservicelocator-type-mspp)  
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)  