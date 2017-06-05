---
TOCTitle: LoadAssemblyFrom Method
Title: 'AssemblyResolver.LoadAssemblyFrom Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.AssemblyResolver.LoadAssemblyFrom(System.String)'
ms:mtpsurl: 'assemblyresolver-loadassemblyfrom-method-mspp-modularity.md'
---

# AssemblyResolver.LoadAssemblyFrom Method

Registers the specified assembly and resolves the types in it when the AppDomain requests for it.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void LoadAssemblyFrom(
	string assemblyFilePath
)
```
```VB
'Declaration
Public Sub LoadAssemblyFrom ( 
	assemblyFilePath As String
)
```

### Parameters

*assemblyFilePath*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The path to the assemly to load in the LoadFrom context.

### Implements

[IAssemblyResolver.LoadAssemblyFrom(String)](/patterns-practices/reference/iassemblyresolver-loadassemblyfrom-method-mspp-modularity)

## Remarks

This method does not load the assembly immediately, but lazily until someone requests a [Type](http://msdn.microsoft.com/en-us/library/42892f65) declared in the assembly.

## See Also

[AssemblyResolver Class](/patterns-practices/reference/assemblyresolver-class-mspp-modularity)  
[AssemblyResolver Members](/patterns-practices/reference/assemblyresolver-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
