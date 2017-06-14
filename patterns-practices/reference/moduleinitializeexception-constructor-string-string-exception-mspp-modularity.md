---
TOCTitle: 'ModuleInitializeException Constructor (String, String, Exception)'
Title: 'ModuleInitializeException Constructor (String, String, Exception) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInitializeException.\#ctor(System.String,System.String,System.Exception)'
ms:mtpsurl: 'moduleinitializeexception-constructor-mspp-modularity.md'
---

# ModuleInitializeException Constructor (String, String, Exception)

Initializes the exception with a particular module, error message and inner exception that happened.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleInitializeException(
	string moduleName,
	string message,
	Exception innerException
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
Type: [System.Exception](http://msdn2.microsoft.com/en-us/library/c18k6c59)  
The exception that is the cause of the current exception, or a **null**a null reference (**Nothing** in Visual Basic) reference if no inner exception is specified.

## Syntax

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
Type: [System.Exception](http://msdn2.microsoft.com/en-us/library/c18k6c59)  
The exception that is the cause of the current exception, or a **Nothing**a null reference (**Nothing** in Visual Basic) reference if no inner exception is specified.

## See Also

[ModuleInitializeException Class](/patterns-practices/reference/moduleinitializeexception-class-mspp-modularity)  
[ModuleInitializeException Members](/patterns-practices/reference/moduleinitializeexception-members-mspp-modularity)  
ModuleInitializeException Overload

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  
