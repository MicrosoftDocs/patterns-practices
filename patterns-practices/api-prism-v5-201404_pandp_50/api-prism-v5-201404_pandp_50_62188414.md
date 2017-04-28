---
TOCTitle: IsNavigationTarget Method
Title: 'INavigationAware.IsNavigationTarget Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.INavigationAware.IsNavigationTarget(Microsoft.Practices.Prism.Regions.NavigationContext)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405953(v=PandP.50)'
---

Prism Class Library

INavigationAware..::.IsNavigationTarget Method
==============================================

Called to determine if this instance can handle the navigation request.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>bool IsNavigationTarget( NavigationContext navigationContext )Function IsNavigationTarget ( navigationContext As NavigationContext ) As Boolean
#### Parameters

navigationContext  
Type: [Microsoft.Practices.Prism.Regions..::.NavigationContext](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationcontext)
The navigation context.

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
trueTruetruetrue (True in Visual Basic) if this instance accepts the navigation request; otherwise, falseFalsefalsefalse (False in Visual Basic).

See Also
--------

<span id="seeAlsoToggle"></span>
[INavigationAware Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.inavigationaware)

[INavigationAware Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.inavigationaware)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
