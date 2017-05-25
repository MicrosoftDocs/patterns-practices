---
TOCTitle: Ref Property
Title: 'ModuleInfoGroup.Ref Property (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.Ref'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431312(v=PandP.50)'
---


# ModuleInfoGroup.Ref Property

Gets or sets the [Ref](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo.ref) value for the whole group. Any [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) classes that are added after setting this value will also get this Ref. The ref value will also be used by the [IModuleManager](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulemanager) to determine which [IModuleTypeLoader](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader) to use. For example, using an "file://" prefix with a valid URL will cause the FileModuleTypeLoader to be used (Only available in the desktop version of CAL).

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public string Ref { get; set; }Public Property Ref As String Get Set
### Property Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The ref value that will be used.

## See Also

[ModuleInfoGroup Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup)

[ModuleInfoGroup Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinfogroup)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
