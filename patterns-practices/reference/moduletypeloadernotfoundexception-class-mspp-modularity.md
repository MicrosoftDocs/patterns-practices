---
TOCTitle: ModuleTypeLoaderNotFoundException Class
Title: 'ModuleTypeLoaderNotFoundException Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.ModuleTypeLoaderNotFoundException'
ms:mtpsurl: 'moduletypeloadernotfoundexception-class-mspp-modularity.md'
---


# ModuleTypeLoaderNotFoundException Class

Exception that's thrown when there is no [IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity) registered in [ModuleTypeLoaders](/patterns-practices/reference/modulemanager-moduletypeloaders-property-mspp-modularity) that can handle this particular type of module.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
[SerializableAttribute]
public class ModuleTypeLoaderNotFoundException : ModularityException
```

```VB
'Declaration
<SerializableAttribute>
Public Class ModuleTypeLoaderNotFoundException
	Inherits ModularityException
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
[System.Exception](http://msdn2.microsoft.com/en-us/library/c18k6c59)  
[Microsoft.Practices.Prism.Modularity.ModularityException](/patterns-practices/reference/modularityexception-class-mspp-modularity)  
Microsoft.Practices.Prism.Modularity.ModuleTypeLoaderNotFoundException

## See Also

[ModuleTypeLoaderNotFoundException Members](/patterns-practices/reference/moduletypeloadernotfoundexception-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>