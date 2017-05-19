---
TOCTitle: RegisterRequiredPrismServicesIfMissing Method
Title: 'DefaultPrismServiceRegistrar.RegisterRequiredPrismServicesIfMissing Method (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.DefaultPrismServiceRegistrar.RegisterRequiredPrismServicesIfMissing(System.ComponentModel.Composition.Hosting.AggregateCatalog)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405820(v=PandP.50)'
---

Prism Class Library

# DefaultPrismServiceRegistrar.RegisterRequiredPrismServicesIfMissing Method

Registers the required Prism types that are not already registered in the [AggregateCatalog](http://msdn2.microsoft.com/en-us/library/dd833165).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions(v=pandp.50))

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

#### Parameters

*aggregateCatalog*  
   Type: [System.ComponentModel.Composition.Hosting.AggregateCatalog](http://msdn2.microsoft.com/en-us/library/dd833165)
   
   The [AggregateCatalog](http://msdn2.microsoft.com/en-us/library/dd833165) to register the required types in, if they are not already registered.

#### Return Value

Type: [AggregateCatalog](http://msdn2.microsoft.com/en-us/library/dd833165)

## See Also


[DefaultPrismServiceRegistrar Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.defaultprismserviceregistrar(v=pandp.50))

[DefaultPrismServiceRegistrar Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.defaultprismserviceregistrar_members(v=pandp.50))

[Microsoft.Practices.Prism.MefExtensions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions(v=pandp.50))
