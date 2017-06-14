---
TOCTitle: 'AddModule Method (ModuleInfoGroup, Type, String[])'
Title: 'ModuleInfoGroupExtensions.AddModule Method (ModuleInfoGroup, Type, String[]) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroupExtensions.AddModule(Microsoft.Practices.Prism.Modularity.ModuleInfoGroup,System.Type,System.String[])'
ms:mtpsurl: 'addmodule-mthd-moduleinfogroup-str-type-str.md'
---

# ModuleInfoGroupExtensions.AddModule Method (ModuleInfoGroup, Type, String[])

Adds a new module that is statically referenced to the specified module info group. 

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) <br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static ModuleInfoGroup AddModule(
	this ModuleInfoGroup moduleInfoGroup,
	Type moduleType,
	params string[] dependsOn
)
```

### Parameters

*moduleInfoGroup*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)<br/>
The group where to add the module info in.

*moduleType*  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)<br/>
The type for the module. This type should be a descendant of [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity).

*dependsOn*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)[]<br/>
The names for the modules that this module depends on.

# ModuleInfoGroupExtensions.AddModule Method (ModuleInfoGroup, Type, String())

Adds a new module that is statically referenced to the specified module info group. 

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) <br/>
**Version:** 5.0.0.0 (5.0.0.0)

```VB
'Declaration
<ExtensionAttribute> 
Public Shared Function AddModule ( 
	moduleInfoGroup As ModuleInfoGroup,
	moduleType As Type,
	ParamArray dependsOn As String()
) As ModuleInfoGroup
```

### Parameters

*moduleInfoGroup*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)<br/>
The group where to add the module info in.

*moduleType*  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)<br/>
The type for the module. This type should be a descendant of [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity).

*dependsOn*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)()<br/>
The names for the modules that this module depends on.

### Return Value

Type: [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)<br/>
Returns the instance of the passed in module info group, to provide a fluid interface.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## Remarks

The name of the module will be the type name.

## See Also

[ModuleInfoGroupExtensions Class](/patterns-practices/reference/moduleinfogroupextensions-class-mspp-modularity)<br/>
[ModuleInfoGroupExtensions Members](/patterns-practices/reference/moduleinfogroupextensions-members-mspp-modularity)<br/>
[AddModule Overload](/patterns-practices/reference/moduleinfogroupextensions-addmodule-method-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>