---
TOCTitle: 'ModuleInitializeException Constructor (String, String, String, Exception)'
Title: 'ModuleInitializeException Constructor (String, String, String, Exception) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInitializeException.\#ctor(System.String,System.String,System.String,System.Exception)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405652(v=PandP.50)'
---


# ModuleInitializeException Constructor (String, String, String, Exception)

Initializes the exception with a particular module, error message and inner exception that happened.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public ModuleInitializeException( string moduleName, string moduleAssembly, string message, Exception innerException )Public Sub New ( moduleName As String, moduleAssembly As String, message As String, innerException As Exception )

### Parameters

moduleName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The name of the module.

moduleAssembly  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The assembly where the module is located.

message  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The error message that explains the reason for the exception.

innerException  
Type: [System.Exception](http://msdn.microsoft.com/en-us/library/c18k6c59)
The exception that is the cause of the current exception, or a nullNothingnullptra null reference (Nothing in Visual Basic) reference if no inner exception is specified.

## See Also

[ModuleInitializeException Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinitializeexception)

[ModuleInitializeException Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinitializeexception)

[ModuleInitializeException Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.modularity.moduleinitializeexception.)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
