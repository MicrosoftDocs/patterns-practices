---
TOCTitle: RegisterRequiredPrismServicesIfMissing Method
Title: 'DefaultPrismServiceRegistrar.RegisterRequiredPrismServicesIfMissing Method (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.DefaultPrismServiceRegistrar.RegisterRequiredPrismServicesIfMissing(System.ComponentModel.Composition.Hosting.AggregateCatalog)'
ms:mtpsurl: 'defaultprismserviceregistrar-registerrequiredprismservicesifmissing-method-mspp-mefextensions.md'
---

# DefaultPrismServiceRegistrar.RegisterRequiredPrismServicesIfMissing Method

Registers the required Prism types that are not already registered in the [AggregateCatalog](http://msdn.microsoft.com/en-us/library/dd833165).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions](/patterns-practices/reference/mspp-mefextensions-namespace)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static AggregateCatalog RegisterRequiredPrismServicesIfMissing(
	AggregateCatalog aggregateCatalog
)
```
```VB
'Declaration
Public Shared Function RegisterRequiredPrismServicesIfMissing ( 
	aggregateCatalog As AggregateCatalog
) As AggregateCatalog
```
### Parameters

*aggregateCatalog*  
   Type: [System.ComponentModel.Composition.Hosting.AggregateCatalog](http://msdn.microsoft.com/en-us/library/dd833165)
   
   The [AggregateCatalog](http://msdn.microsoft.com/en-us/library/dd833165) to register the required types in, if they are not already registered.

### Return Value

Type: [AggregateCatalog](http://msdn.microsoft.com/en-us/library/dd833165)

## See Also
[DefaultPrismServiceRegistrar Class](/patterns-practices/reference/defaultprismserviceregistrar-class-mspp-mefextensions)

[DefaultPrismServiceRegistrar Members](/patterns-practices/reference/defaultprismserviceregistrar-members-mspp-mefextensions)

[Microsoft.Practices.Prism.MefExtensions Namespace](/patterns-practices/reference/mspp-mefextensions-namespace)
