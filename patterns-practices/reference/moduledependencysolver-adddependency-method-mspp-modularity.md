---
TOCTitle: AddDependency Method
Title: 'ModuleDependencySolver.AddDependency Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleDependencySolver.AddDependency(System.String,System.String)'
ms:mtpsurl: 'moduledependencysolver-adddependency-method-mspp-modularity.md'
---

# ModuleDependencySolver.AddDependency Method

Adds a module dependency between the modules specified by dependingModule and dependentModule.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void AddDependency(
	string dependingModule,
	string dependentModule
)
```

```VB
'Declaration
Public Sub AddDependency ( 
	dependingModule As String,
	dependentModule As String
)
```

### Parameters

*dependingModule*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
The name of the module with the dependency.

*dependentModule*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The name of the module dependingModule depends on.

## See Also

[ModuleDependencySolver Class](/patterns-practices/reference/moduledependencysolver-class-mspp-modularity)<br/>
[ModuleDependencySolver Members](/patterns-practices/reference/moduledependencysolver-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>