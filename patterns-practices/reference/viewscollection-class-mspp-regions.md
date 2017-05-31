---
TOCTitle: ViewsCollection Class
Title: 'ViewsCollection Class (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.ViewsCollection'
ms:mtpsurl: 'viewscollection-class-mspp-regions.md'
---

# ViewsCollection Class

Implementation of [IViewsCollection](/patterns-practices/reference/iviewscollection-interface-mspp-regions) that takes an [ObservableCollection&lt;T&gt;](http://msdn.microsoft.com/en-us/library/ms668604) of [ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions) and filters it to display an [INotifyCollectionChanged](http://msdn.microsoft.com/en-us/library/ms668629) collection of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) elements (the items which the [ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions) wraps).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class ViewsCollection : IViewsCollection, 
	IEnumerable<Object>, IEnumerable, INotifyCollectionChanged
``` 

```VB
'Declaration
Public Class ViewsCollection
	Implements IViewsCollection, IEnumerable(Of Object), 
	IEnumerable, INotifyCollectionChanged
```	

Implementation of IViewsCollection that takes an [ObservableCollection(Of T)](http://msdn.microsoft.com/en-us/library/ms668604) of [ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions) and filters it to display an [INotifyCollectionChanged](http://msdn.microsoft.com/en-us/library/ms668629) collection of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) elements (the items which the [ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions) wraps).

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
    Microsoft.Practices.Prism.Regions.ViewsCollection

## See Also

[ViewsCollection Members](/patterns-practices/reference/viewscollection-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)

