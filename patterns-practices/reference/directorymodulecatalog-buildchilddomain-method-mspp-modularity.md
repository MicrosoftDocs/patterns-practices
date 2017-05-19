---
TOCTitle: BuildChildDomain Method
Title: 'DirectoryModuleCatalog.BuildChildDomain Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.DirectoryModuleCatalog.BuildChildDomain(System.AppDomain)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405848(v=PandP.50)'
---

Prism Class Library

DirectoryModuleCatalog.BuildChildDomain Method
==================================================

Creates a new child domain and copies the evidence from a parent domain.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected virtual AppDomain BuildChildDomain( AppDomain parentDomain )Protected Overridable Function BuildChildDomain ( parentDomain As AppDomain ) As AppDomain
#### Parameters

parentDomain  
Type: [System.AppDomain](http://msdn2.microsoft.com/en-us/library/w124b5fa)
The parent domain.

#### Return Value

Type: [AppDomain](http://msdn2.microsoft.com/en-us/library/w124b5fa)
The new child domain.

Remarks
-------

<span id="remarksToggle"></span> Grabs the parentDomain evidence and uses it to construct the new [AppDomain](http://msdn2.microsoft.com/en-us/library/w124b5fa) because in a ClickOnce execution environment, creating an [AppDomain](http://msdn2.microsoft.com/en-us/library/w124b5fa) will by default pick up the partial trust environment of the AppLaunch.exe, which was the root executable. The AppLaunch.exe does a create domain and applies the evidence from the ClickOnce manifests to create the domain that the application is actually executing in. This will need to be Full Trust for Prism applications.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                                                        |
|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) is thrown if parentDomain is null. |

See Also
--------


[DirectoryModuleCatalog Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.directorymodulecatalog)

[DirectoryModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.directorymodulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
