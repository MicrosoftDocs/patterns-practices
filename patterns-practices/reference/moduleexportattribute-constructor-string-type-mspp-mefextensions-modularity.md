---
TOCTitle: 'ModuleExportAttribute Constructor (String, Type)'
Title: 'ModuleExportAttribute Constructor (String, Type) (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.ModuleExportAttribute.\#ctor(System.String,System.Type)'
ms:mtpsurl: 'moduleexportattribute-constructor-mspp-mefextensions-modularity.md'
---

# ModuleExportAttribute Constructor (String, Type)

Initializes a new instance of the [ModuleExportAttribute](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.moduleexportattribute(v=pandp.50)) class.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleExportAttribute(
	string moduleName,
	Type moduleType
)
```

```VB
'Declaration
Public Sub New ( 
	moduleName As String,
	moduleType As Type
)
```
public ModuleExportAttribute( string moduleName, Type moduleType )Public Sub New ( moduleName As String, moduleType As Type )

### Parameters

*moduleName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)   
The contract name of the module.

*moduleType*   
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)   
The concrete type of the module being exported. Not typeof(IModule).

## See Also

[ModuleExportAttribute Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.moduleexportattribute(v=pandp.50))

[ModuleExportAttribute Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.moduleexportattribute_members(v=pandp.50))

ModuleExportAttribute Overload

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity(v=pandp.50))
