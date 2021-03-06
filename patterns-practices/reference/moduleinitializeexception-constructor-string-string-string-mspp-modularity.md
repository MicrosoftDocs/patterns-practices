---
TOCTitle: 'ModuleInitializeException Constructor (String, String, String)'
Title: 'ModuleInitializeException Constructor (String, String, String) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInitializeException.\#ctor(System.String,System.String,System.String)'
ms:mtpsurl: 'moduleinitializeexception-constructor-mspp-modularity.md'
---

# ModuleInitializeException Constructor (String, String, String)

Initializes the exception with a particular module and error message.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleInitializeException(
	string moduleName,
	string moduleAssembly,
	string message
)
```

```VB
'Declaration
Public Sub New ( 
	moduleName As String,
	moduleAssembly As String,
	message As String
)
```

### Parameters

*moduleName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The name of the module.

*moduleAssembly*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The assembly where the module is located.

*message*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The error message that explains the reason for the exception.

## See Also

[ModuleInitializeException Class](/patterns-practices/reference/moduleinitializeexception-class-mspp-modularity)  
[ModuleInitializeException Members](/patterns-practices/reference/moduleinitializeexception-members-mspp-modularity)  
ModuleInitializeException Overload  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  