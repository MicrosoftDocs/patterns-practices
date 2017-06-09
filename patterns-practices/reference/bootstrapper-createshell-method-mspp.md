---
TOCTitle: CreateShell Method
Title: 'Bootstrapper.CreateShell Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.Bootstrapper.CreateShell'
ms:mtpsurl: 'bootstrapper-createshell-method-mspp.md'
---


# Bootstrapper.CreateShell Method

Creates the shell or main window of the application.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected abstract DependencyObject CreateShell()
``` 

```VB
'Declaration
Protected MustOverride Function CreateShell As DependencyObject
```    

### Return Value

Type: [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)

The shell of the application.

## Remarks

 If the returned instance is a [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309), the [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp) will attach the default [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) of the application in its [RegionManagerProperty](/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions) attached property in order to be able to add regions by using the [RegionNameProperty](/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions) attached property from XAML.

## See Also

[Bootstrapper Class](/patterns-practices/reference/bootstrapper-class-mspp)

[Bootstrapper Members](/patterns-practices/reference/bootstrapper-members-mspp)

[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)
