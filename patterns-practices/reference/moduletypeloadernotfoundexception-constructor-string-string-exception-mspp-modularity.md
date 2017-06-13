---
TOCTitle: 'ModuleTypeLoaderNotFoundException Constructor (String, String, Exception)'
Title: 'ModuleTypeLoaderNotFoundException Constructor (String, String, Exception) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleTypeLoaderNotFoundException.\#ctor(System.String,System.String,System.Exception)'
ms:mtpsurl: 'moduletypeloadernotfoundexception-constructor-mspp-modularity.md'
---

# ModuleTypeLoaderNotFoundException Constructor (String, String, Exception)

Initializes the exception with a particular module, error message and inner exception that happened.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public ModuleTypeLoaderNotFoundException(
	string moduleName,
	string message,
	Exception innerException
)
```

```VB
'Declaration
Public Sub New ( 
	moduleName As String,
	message As String,
	innerException As Exception
)
```

### Parameters

*moduleName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The name of the module.

*message*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The error message that explains the reason for the exception.

*innerException*  
Type: [System.Exception](http://msdn.microsoft.com/en-us/library/c18k6c59)  
The exception that is the cause of the current exception, or a **null**a null reference (**Nothing** in Visual Basic) reference if no inner exception is specified.


## See Also

[ModuleTypeLoaderNotFoundException Class](/patterns-practices/reference/moduletypeloadernotfoundexception-class-mspp-modularity)<br/>
[ModuleTypeLoaderNotFoundException Members](/patterns-practices/reference/moduletypeloadernotfoundexception-members-mspp-modularity)<br/>
ModuleTypeLoaderNotFoundException Overload

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>