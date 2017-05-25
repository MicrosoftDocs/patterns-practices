---
TOCTitle: LoadAssemblyFrom Method
Title: 'AssemblyResolver.LoadAssemblyFrom Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.AssemblyResolver.LoadAssemblyFrom(System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.assemblyresolver.loadassemblyfrom(v=pandp.50)'
---

Prism Class Library

AssemblyResolver.LoadAssemblyFrom Method
============================================

Registers the specified assembly and resolves the types in it when the AppDomain requests for it.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public void LoadAssemblyFrom( string assemblyFilePath )Public Sub LoadAssemblyFrom ( assemblyFilePath As String )

### Parameters

assemblyFilePath  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The path to the assemly to load in the LoadFrom context.

### Implements

[IAssemblyResolver.LoadAssemblyFrom(String)](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.iassemblyresolver.loadassemblyfrom(system.string))

Remarks
-------

This method does not load the assembly immediately, but lazily until someone requests a [Type](http://msdn.microsoft.com/en-us/library/42892f65) declared in the assembly.

See Also
--------


[AssemblyResolver Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.assemblyresolver)

[AssemblyResolver Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.assemblyresolver)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
