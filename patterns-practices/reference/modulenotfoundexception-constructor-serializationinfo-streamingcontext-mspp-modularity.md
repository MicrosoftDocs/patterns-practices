---
TOCTitle: 'ModuleNotFoundException Constructor (SerializationInfo, StreamingContext)'
Title: 'ModuleNotFoundException Constructor (SerializationInfo, StreamingContext) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleNotFoundException.\#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)'
ms:mtpsurl: 'modulenotfoundexception-constructor-mspp-modularity.md'
---


# ModuleNotFoundException Constructor (SerializationInfo, StreamingContext)

Initializes a new instance of the [ModuleNotFoundException](/patterns-practices/reference/modulenotfoundexception-class-mspp-modularity) class with the serialization data.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected ModuleNotFoundException(
	SerializationInfo info,
	StreamingContext context
)
```

```VB
'Declaration
Protected Sub New ( 
	info As SerializationInfo,
	context As StreamingContext
)
```

### Parameters

*info* 
 
   Type: [System.Runtime.Serialization.SerializationInfo](http://msdn.microsoft.com/en-us/library/a9b6042e)
	
   Holds the serialized object data about the exception being thrown.

*context*

   Type: [System.Runtime.Serialization.StreamingContext](http://msdn.microsoft.com/en-us/library/t16abws5)
	
   Contains contextual information about the source or destination.

## See Also

[ModuleNotFoundException Class](/patterns-practices/reference/modulenotfoundexception-class-mspp-modularity)<br/>
[ModuleNotFoundException Members](/patterns-practices/reference/modulenotfoundexception-members-mspp-modularity)<br/>
ModuleNotFoundException Overload

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>