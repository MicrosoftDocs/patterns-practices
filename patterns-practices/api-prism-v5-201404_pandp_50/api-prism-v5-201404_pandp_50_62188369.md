---
TOCTitle: 'TryResolve(T) Method (IServiceLocator)'
Title: 'ServiceLocatorExtensions.TryResolve(T) Method (IServiceLocator) (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ServiceLocatorExtensions.TryResolve\`\`1(Microsoft.Practices.ServiceLocation.IServiceLocator)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419002(v=PandP.50)'
---

Prism Class Library

ServiceLocatorExtensions..::.TryResolve&lt;(Of &lt;(T&gt;)&gt;) Method (IServiceLocator)
========================================================================================

Attempts to resolve specified type from the underlying IServiceLocator.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/n:microsoft.practices.prism)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public static T TryResolve&lt;T&gt;( this IServiceLocator locator ) where T : class &lt;ExtensionAttribute&gt; Public Shared Function TryResolve(Of T As Class) ( locator As IServiceLocator ) As T
#### Parameters

locator  
Type: IServiceLocator
Locator to use in resolving.

Type Parameters
---------------

<span id="templatesToggle"></span>
T  
Type to resolve.

#### Return Value

Type: T
T or null
#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type IServiceLocator. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

Remarks
-------

<span id="remarksToggle"></span> This will return null on any ActivationException.

See Also
--------

<span id="seeAlsoToggle"></span>
[ServiceLocatorExtensions Class](https://msdn.microsoft.com/t:microsoft.practices.prism.servicelocatorextensions)

[ServiceLocatorExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.servicelocatorextensions)

[TryResolve Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.servicelocatorextensions.tryresolve)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
