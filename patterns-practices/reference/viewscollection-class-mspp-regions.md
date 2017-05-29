---
TOCTitle: ViewsCollection Class
Title: 'ViewsCollection Class (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.ViewsCollection'
ms:mtpsurl: 'viewscollection-class-mspp-regions.md'
---

# ViewsCollection Class

Implementation of [IViewsCollection](iviewscollection-interface-mspp-regions.md) that takes an [ObservableCollection&lt;T&gt;](http://msdn.microsoft.com/en-us/library/ms668604) of [ItemMetadata](itemmetadata-class-mspp-regions.md) and filters it to display an [INotifyCollectionChanged](http://msdn.microsoft.com/en-us/library/ms668629) collection of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) elements (the items which the [ItemMetadata](itemmetadata-class-mspp-regions.md) wraps).

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace.md)

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

Implementation of IViewsCollection that takes an [ObservableCollection(Of T)](http://msdn.microsoft.com/en-us/library/ms668604) of [ItemMetadata](itemmetadata-class-mspp-regions.md) and filters it to display an [INotifyCollectionChanged](http://msdn.microsoft.com/en-us/library/ms668629) collection of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) elements (the items which the [ItemMetadata](itemmetadata-class-mspp-regions.md) wraps).

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
    Microsoft.Practices.Prism.Regions.ViewsCollection

## See Also

[ViewsCollection Members](viewscollection-members-mspp-regions.md)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace.md)

