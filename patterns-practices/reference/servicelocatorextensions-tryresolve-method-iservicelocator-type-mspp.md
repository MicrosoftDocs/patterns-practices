---
TOCTitle: 'TryResolve Method (IServiceLocator, Type)'
Title: 'ServiceLocatorExtensions.TryResolve Method (IServiceLocator, Type) (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ServiceLocatorExtensions.TryResolve(Microsoft.Practices.ServiceLocation.IServiceLocator,System.Type)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419001(v=PandP.50)'
---

Prism Class Library

ServiceLocatorExtensions.TryResolve Method (IServiceLocator, Type)
======================================================================

Attempts to resolve specified type from the underlying IServiceLocator.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/library/microsoft.practices.prism)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public static Object TryResolve( this IServiceLocator locator, Type type )&lt;ExtensionAttribute&gt; Public Shared Function TryResolve ( locator As IServiceLocator, type As Type ) As Object

### Parameters

locator  
Type: IServiceLocator
Locator to use in resolving.

type  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
Type to resolve.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
T or null
### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type IServiceLocator. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

Remarks
-------

<span id="remarksToggle"></span> This will return null on any ActivationException.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                            |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | Thrown when locator is nullNothingnullptra null reference (Nothing in Visual Basic). |

See Also
--------


[ServiceLocatorExtensions Class](https://msdn.microsoft.com/library/microsoft.practices.prism.servicelocatorextensions)

[ServiceLocatorExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.servicelocatorextensions)

[TryResolve Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.servicelocatorextensions.tryresolve)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism)
