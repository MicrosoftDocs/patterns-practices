---
TOCTitle: 'ModuleInfo Constructor (String, String, String[])'
Title: 'ModuleInfo Constructor (String, String, String[]) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfo.\#ctor(System.String,System.String,System.String[])'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405645(v=PandP.50)'
---

Prism Class Library

ModuleInfo Constructor (String, String, array&lt;String&gt;)
======================================================================

Initializes a new instance of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo).

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public ModuleInfo( string name, string type, params string[] dependsOn )Public Sub New ( name As String, type As String, ParamArray dependsOn As String() )

### Parameters

name  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The module's name.

type  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The module [Type](http://msdn2.microsoft.com/en-us/library/42892f65)'s AssemblyQualifiedName.

dependsOn  
Type: array&lt;[System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)&gt;
The modules this instance depends on.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                                                                                                             |
|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) is thrown if dependsOn is nullNothingnullptra null reference (Nothing in Visual Basic). |

See Also
--------


[ModuleInfo Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)

[ModuleInfo Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinfo)

[ModuleInfo Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.modularity.moduleinfo.)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
