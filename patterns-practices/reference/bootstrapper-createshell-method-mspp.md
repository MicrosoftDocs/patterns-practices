---
TOCTitle: CreateShell Method
Title: 'Bootstrapper.CreateShell Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.Bootstrapper.CreateShell'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431152(v=PandP.50)'
---

Prism Class Library

Bootstrapper.CreateShell Method
===================================

Creates the shell or main window of the application.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/n:microsoft.practices.prism)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>protected abstract DependencyObject CreateShell()Protected MustOverride Function CreateShell As DependencyObject
#### Return Value

Type: [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309)
The shell of the application.

Remarks
-------

<span id="remarksToggle"></span> If the returned instance is a [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309), the [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper) will attach the default [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) of the application in its [RegionManagerProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionmanagerproperty) attached property in order to be able to add regions by using the [RegionNameProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionnameproperty) attached property from XAML.

See Also
--------


[Bootstrapper Class](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper)

[Bootstrapper Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.bootstrapper)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
