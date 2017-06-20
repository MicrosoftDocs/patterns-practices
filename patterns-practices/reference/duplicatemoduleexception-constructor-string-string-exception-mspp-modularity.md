---
TOCTitle: 'DuplicateModuleException Constructor (String, String, Exception)'
Title: 'DuplicateModuleException Constructor (String, String, Exception) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.DuplicateModuleException.\#ctor(System.String,System.String,System.Exception)'
ms:mtpsurl: 'duplicatemoduleexception-constructor-mspp-modularity.md'
---


# DuplicateModuleException Constructor (String, String, Exception)

Initializes a new instance of the [DuplicateModuleException](/patterns-practices/reference/duplicatemoduleexception-class-mspp-modularity) class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public DuplicateModuleException(
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

innerException  
Type: [System.Exception](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)

The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified.

## See Also

[DuplicateModuleException Class](/patterns-practices/reference/duplicatemoduleexception-class-mspp-modularity)  
[DuplicateModuleException Members](/patterns-practices/reference/duplicatemoduleexception-members-mspp-modularity)  
DuplicateModuleException Overload  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)