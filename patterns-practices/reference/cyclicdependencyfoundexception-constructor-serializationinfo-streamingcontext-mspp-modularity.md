---
TOCTitle: 'CyclicDependencyFoundException Constructor (SerializationInfo, StreamingContext)'
Title: 'CyclicDependencyFoundException Constructor (SerializationInfo, StreamingContext) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException.\#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)'
ms:mtpsurl: 'cyclicdependencyfoundexception-constructor-mspp-modularity.md'
---

# CyclicDependencyFoundException Constructor (SerializationInfo, StreamingContext)

Initializes a new instance of the [CyclicDependencyFoundException](/patterns-practices/reference/cyclicdependencyfoundexception-class-mspp-modularity) class with the serialization data.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected CyclicDependencyFoundException(
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

[CyclicDependencyFoundException Class](/patterns-practices/reference/cyclicdependencyfoundexception-class-mspp-modularity)  
[CyclicDependencyFoundException Members](/patterns-practices/reference/cyclicdependencyfoundexception-members-mspp-modularity)  
CyclicDependencyFoundException Overload  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  