---
TOCTitle: 'ModuleConfigurationElement Constructor (String, String, String, Boolean)'
Title: 'ModuleConfigurationElement Constructor (String, String, String, Boolean) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleConfigurationElement.\#ctor(System.String,System.String,System.String,System.Boolean)'
ms:mtpsurl: 'moduleconfigurationelement-constructor-mspp-modularity.md'
---

# ModuleConfigurationElement Constructor (String, String, String, Boolean)

Initializes a new instance of [ModuleConfigurationElement](moduleconfigurationelement-class-mspp-modularity).

**Namespace:** [Microsoft.Practices.Prism.Modularity](mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleConfigurationElement(
	string assemblyFile,
	string moduleType,
	string moduleName,
	bool startupLoaded
)
```

```VB
'Declaration
Public Sub New ( 
	assemblyFile As String,
	moduleType As String,
	moduleName As String,
	startupLoaded As Boolean
)
```

### Parameters

*assemblyFile

	Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
	The assembly file where the module is located.

*moduleType 

	Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
	The type of the module.

*moduleName  

	Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
	The name of the module.

*startupLoaded 

	Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
	This attribute specifies whether the module is loaded at startup.

## See Also

[ModuleConfigurationElement Class](moduleconfigurationelement-class-mspp-modularity)

[ModuleConfigurationElement Members](moduleconfigurationelement-members-mspp-modularity)

ModuleConfigurationElement Overload

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace)
