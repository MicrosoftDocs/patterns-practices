---
TOCTitle: 'ModuleNotFoundException Constructor (String, Exception)'
Title: 'ModuleNotFoundException Constructor (String, Exception) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleNotFoundException.\#ctor(System.String,System.Exception)'
ms:mtpsurl: 'modulenotfoundexception-constructor-mspp-modularity.md'
---
# ModuleNotFoundException Constructor (String, Exception)

Initializes a new instance of the [ModuleNotFoundException](/patterns-practices/reference/modulenotfoundexception-class-mspp-modularity) class with a specified error message.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  <br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleNotFoundException(
	string message,
	Exception innerException
)
```

```VB
'Declaration
Public Sub New ( 
	message As String,
	innerException As Exception
)
```

### Parameters

*message*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The message that describes the error.

*innerException*  
Type: [System.Exception](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)  
The inner exception

## See Also

[ModuleNotFoundException Class](/patterns-practices/reference/modulenotfoundexception-class-mspp-modularity)  
[ModuleNotFoundException Members](/patterns-practices/reference/modulenotfoundexception-members-mspp-modularity)  
ModuleNotFoundException Overload  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>

