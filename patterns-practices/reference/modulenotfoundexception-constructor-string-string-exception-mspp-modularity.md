---
TOCTitle: 'ModuleNotFoundException Constructor (String, String, Exception)'
Title: 'ModuleNotFoundException Constructor (String, String, Exception) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleNotFoundException.\#ctor(System.String,System.String,System.Exception)'
ms:mtpsurl: 'modulenotfoundexception-constructor-mspp-modularity.md'
---

# ModuleNotFoundException Constructor (String, String, Exception)

Initializes a new instance of the [ModuleNotFoundException](/patterns-practices/reference/modulenotfoundexception-class-mspp-modularity) class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleNotFoundException(
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
The exception that is the cause of the current exception, or a null reference if no inner exception is specified.

## See Also

[ModuleNotFoundException Class](/patterns-practices/reference/modulenotfoundexception-class-mspp-modularity)

[ModuleNotFoundException Members](/patterns-practices/reference/modulenotfoundexception-members-mspp-modularity)

ModuleNotFoundException Overload

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
