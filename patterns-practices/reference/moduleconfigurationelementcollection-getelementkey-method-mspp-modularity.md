---
TOCTitle: GetElementKey Method
Title: 'ModuleConfigurationElementCollection.GetElementKey Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleConfigurationElementCollection.GetElementKey(System.Configuration.ConfigurationElement)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleconfigurationelementcollection.getelementkey(v=pandp.50)'
---

Prism Class Library

ModuleConfigurationElementCollection.GetElementKey Method
=============================================================

Gets the element key for a specified configuration element when overridden in a derived class.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


protected override Object GetElementKey( ConfigurationElement element )Protected Overrides Function GetElementKey ( element As ConfigurationElement ) As Object

### Parameters

element  
Type: [System.Configuration.ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3)
The [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3) to return the key for.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
An [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) that acts as the key for the specified [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).

See Also
--------


[ModuleConfigurationElementCollection Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleconfigurationelementcollection)

[ModuleConfigurationElementCollection Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleconfigurationelementcollection)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
