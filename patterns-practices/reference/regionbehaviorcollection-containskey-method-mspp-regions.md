---
TOCTitle: ContainsKey Method
Title: 'RegionBehaviorCollection.ContainsKey Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionBehaviorCollection.ContainsKey(System.String)'
ms:mtpsurl: 'regionbehaviorcollection-containskey-method-mspp-regions.md'
---


# RegionBehaviorCollection.ContainsKey Method

Checks if a [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) with the specified key is already present.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

~~~C#
public bool ContainsKey(
	string key
)
~~~
~~~VB
'Declaration
Public Function ContainsKey ( 
	key As String
) As Boolean
~~~

### Parameters

_key_  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The key to use to find a particular [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions).

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
### Implements

[IRegionBehaviorCollection.ContainsKey(String)](/patterns-practices/reference/iregionbehaviorcollection-containskey-method-mspp-regions)

## See Also

[RegionBehaviorCollection Class](/patterns-practices/reference/regionbehaviorcollection-class-mspp-regions)<br/>
[RegionBehaviorCollection Members](/patterns-practices/reference/regionbehaviorcollection-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>