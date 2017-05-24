---
TOCTitle: GetObjectData Method
Title: 'ModularityException.GetObjectData Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModularityException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405866(v=PandP.50)'
---

Prism Class Library

ModularityException..::.GetObjectData Method
============================================

Sets the [SerializationInfo](http://msdn2.microsoft.com/en-us/library/a9b6042e) with information about the exception.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public override void GetObjectData( SerializationInfo info, StreamingContext context )Public Overrides Sub GetObjectData ( info As SerializationInfo, context As StreamingContext )
#### Parameters

info  
Type: [System.Runtime.Serialization..::.SerializationInfo](http://msdn2.microsoft.com/en-us/library/a9b6042e)
The [SerializationInfo](http://msdn2.microsoft.com/en-us/library/a9b6042e) that holds the serialized object data about the exception being thrown.

<!-- -->

context  
Type: [System.Runtime.Serialization..::.StreamingContext](http://msdn2.microsoft.com/en-us/library/t16abws5)
The [StreamingContext](http://msdn2.microsoft.com/en-us/library/t16abws5) that contains contextual information about the source or destination.

#### Implements

[ISerializable..::.GetObjectData(SerializationInfo, StreamingContext)](http://msdn2.microsoft.com/en-us/library/27cxsdk6)
[\_Exception..::.GetObjectData(SerializationInfo, StreamingContext)](http://msdn2.microsoft.com/en-us/library/854b9522)

See Also
--------

<span id="seeAlsoToggle"></span>
[ModularityException Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modularityexception)

[ModularityException Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modularityexception)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
