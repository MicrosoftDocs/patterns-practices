---
TOCTitle: GetElementKey Method
Title: 'ModuleDependencyCollection.GetElementKey Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleDependencyCollection.GetElementKey(System.Configuration.ConfigurationElement)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405898(v=PandP.50)'
---

Prism Class Library

ModuleDependencyCollection.GetElementKey Method
===================================================

Gets the element key for a specified configuration element when overridden in a derived class.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
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


[ModuleDependencyCollection Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduledependencycollection)

[ModuleDependencyCollection Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduledependencycollection)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
