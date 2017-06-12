---
TOCTitle: GetEnumerator Method
Title: 'RegionBehaviorCollection.GetEnumerator Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionBehaviorCollection.GetEnumerator'
ms:mtpsurl: 'regionbehaviorcollection-getenumerator-method-mspp-regions.md'
---


# RegionBehaviorCollection.GetEnumerator Method

Returns an enumerator that iterates through the collection.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public IEnumerator<KeyValuePair<string, IRegionBehavior>> GetEnumerator()
```

### Return Value

Type: [IEnumerator](http://msdn.microsoft.com/en-us/library/78dfe2yb)&lt;[KeyValuePair](http://msdn.microsoft.com/en-us/library/5tbh8a42)&lt;[String](http://msdn.microsoft.com/en-us/library/s1wwdcbf), [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)&gt;&gt;  

A [IEnumerable&lt;T&gt;](http://msdn.microsoft.com/en-us/library/78dfe2yb) that can be used to iterate through the collection.

### Implements

[IEnumerable&lt;T&gt;.GetEnumerator()](http://msdn.microsoft.com/en-us/library/s793z9y2)

## Syntax

```VB
'Declaration
Public Function GetEnumerator As IEnumerator(Of KeyValuePair(Of String, IRegionBehavior))
```

### Return Value

Type: [IEnumerator](http://msdn.microsoft.com/en-us/library/78dfe2yb)(Of [KeyValuePair](http://msdn.microsoft.com/en-us/library/5tbh8a42)(Of [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf), [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)))  

A [IEnumerable(Of T)](http://msdn.microsoft.com/en-us/library/78dfe2yb) that can be used to iterate through the collection.

### Implements

[IEnumerable(Of T).GetEnumerator](http://msdn.microsoft.com/en-us/library/s793z9y2)

## See Also

[RegionBehaviorCollection Class](/patterns-practices/reference/regionbehaviorcollection-class-mspp-regions)<br/>
[RegionBehaviorCollection Members](/patterns-practices/reference/regionbehaviorcollection-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>