---
TOCTitle: ForwardValues Method
Title: 'ModuleInfoGroup.ForwardValues Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.ForwardValues(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405908(v=PandP.50)'
---


# ModuleInfoGroup.ForwardValues Method

Forwards [InitializationMode](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup.initializationmode(v=pandp.50)) and [Ref](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup.ref(v=pandp.50)) properties from this [ModuleInfoGroup](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup(v=pandp.50)) to moduleInfo.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected void ForwardValues(
	ModuleInfo moduleInfo
)
```

### Parameters

*moduleInfo*  

Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50))

The module info to forward values to.

```VB
'Declaration
Protected Sub ForwardValues ( 
	moduleInfo As ModuleInfo
)
```

### Parameters

*moduleInfo*  

Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50))

The module info to forward values to.

## Exceptions

 Exception                                                                              Condition                                                                                                                                            
 
 [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)  An [ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) is thrown if *moduleInfo* is **nulla** null reference (**Nothing** in Visual Basic).

## See Also

[ModuleInfoGroup Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup(v=pandp.50))

[ModuleInfoGroup Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup_members(v=pandp.50))

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))
