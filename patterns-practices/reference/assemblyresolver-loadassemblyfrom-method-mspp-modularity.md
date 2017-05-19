---
TOCTitle: LoadAssemblyFrom Method
Title: 'AssemblyResolver.LoadAssemblyFrom Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.AssemblyResolver.LoadAssemblyFrom(System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405845(v=PandP.50)'
---

Prism Class Library

AssemblyResolver.LoadAssemblyFrom Method
============================================

Registers the specified assembly and resolves the types in it when the AppDomain requests for it.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public void LoadAssemblyFrom( string assemblyFilePath )Public Sub LoadAssemblyFrom ( assemblyFilePath As String )
#### Parameters

assemblyFilePath  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The path to the assemly to load in the LoadFrom context.

#### Implements

[IAssemblyResolver.LoadAssemblyFrom(String)](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.iassemblyresolver.loadassemblyfrom(system.string))

Remarks
-------

<span id="remarksToggle"></span>This method does not load the assembly immediately, but lazily until someone requests a [Type](http://msdn2.microsoft.com/en-us/library/42892f65) declared in the assembly.

See Also
--------

<span id="seeAlsoToggle"></span>
[AssemblyResolver Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.assemblyresolver)

[AssemblyResolver Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.assemblyresolver)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
