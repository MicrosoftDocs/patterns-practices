---
TOCTitle: AssemblyResolver Class
Title: 'AssemblyResolver Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.AssemblyResolver'
ms:mtpsurl: 'assemblyresolver-class-mspp-modularity.md'
---

# AssemblyResolver Class

Handles AppDomain's AssemblyResolve event to be able to load assemblies dynamically in the LoadFrom context, but be able to reference the type from assemblies loaded in the Load context.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class AssemblyResolver : IAssemblyResolver, 
	IDisposable
```

```VB
'Declaration
Public Class AssemblyResolver
	Implements IAssemblyResolver, IDisposable
```

## Inheritance Hierarchy

&nbsp;&nbsp;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.Modularity.AssemblyResolver

## See Also

[AssemblyResolver Members](/patterns-practices/reference/assemblyresolver-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)