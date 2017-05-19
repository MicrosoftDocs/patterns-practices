---
TOCTitle: 'AddRange(T) Method'
Title: 'CollectionExtensions.AddRange(T) Method (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.CollectionExtensions.AddRange\`\`1(System.Collections.ObjectModel.Collection{\`\`0},System.Collections.Generic.IEnumerable{\`\`0})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405741(v=PandP.50)'
---

Prism Class Library

CollectionExtensions.AddRange&lt;(Of &lt;(T&gt;)&gt;) Method
================================================================

Add a range of items to a collection.

**Namespace:** [Microsoft.Practices.Prism](https://msdn.microsoft.com/n:microsoft.practices.prism)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public static Collection&lt;T&gt; AddRange&lt;T&gt;( this Collection&lt;T&gt; collection, IEnumerable&lt;T&gt; items ) &lt;ExtensionAttribute&gt; Public Shared Function AddRange(Of T) ( collection As Collection(Of T), items As IEnumerable(Of T) ) As Collection(Of T)
#### Parameters

collection  
Type: [System.Collections.ObjectModel.Collection](http://msdn2.microsoft.com/en-us/library/ms132397)&lt;(Of &lt;(T&gt;)&gt;)
The collection to add items to.

items  
Type: [System.Collections.Generic.IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;(T&gt;)&gt;)
The items to add to the collection.

Type Parameters
---------------

<span id="templatesToggle"></span>
T  
Type of objects within the collection.

#### Return Value

Type: [Collection](http://msdn2.microsoft.com/en-us/library/ms132397)&lt;(Of &lt;(T&gt;)&gt;)
The collection.
#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [Collection](http://msdn2.microsoft.com/en-us/library/ms132397)&lt;(Of &lt;(T&gt;)&gt;). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                                                                                                                       |
|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) is thrown if collection or items is nullNothingnullptra null reference (Nothing in Visual Basic). |

See Also
--------


[CollectionExtensions Class](https://msdn.microsoft.com/t:microsoft.practices.prism.collectionextensions)

[CollectionExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.collectionextensions)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
