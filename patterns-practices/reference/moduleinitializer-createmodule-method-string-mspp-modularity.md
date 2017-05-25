---
TOCTitle: 'CreateModule Method (String)'
Title: 'ModuleInitializer.CreateModule Method (String) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInitializer.CreateModule(System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405922(v=PandP.50)'
---


# ModuleInitializer.CreateModule Method (String)

Uses the container to resolve a new [IModule](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodule) by specifying its [Type](http://msdn.microsoft.com/en-us/library/42892f65).

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

protected virtual IModule CreateModule( string typeName )Protected Overridable Function CreateModule ( typeName As String ) As IModule

### Parameters

typeName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The type name to resolve. This type must implement [IModule](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodule).

### Return Value

Type: [IModule](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodule)
A new instance of typeName.

## See Also

[ModuleInitializer Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinitializer)

[ModuleInitializer Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinitializer)

[CreateModule Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.modularity.moduleinitializer.createmodule)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
