---
TOCTitle: ViewsCollection Class
Title: 'ViewsCollection Class (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.ViewsCollection'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431568(v=PandP.50)'
---

Prism Class Library

# ViewsCollection Class

Implementation of [IViewsCollection](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iviewscollection(v=pandp.50)) that takes an [ObservableCollection&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/ms668604) of [ItemMetadata](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.itemmetadata(v=pandp.50)) and filters it to display an [INotifyCollectionChanged](http://msdn2.microsoft.com/en-us/library/ms668629) collection of [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) elements (the items which the [ItemMetadata](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.itemmetadata(v=pandp.50)) wraps).

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

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

Implementation of IViewsCollection that takes an [ObservableCollection(Of T)](http://msdn2.microsoft.com/en-us/library/ms668604) of [ItemMetadata](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.itemmetadata(v=pandp.50)) and filters it to display an [INotifyCollectionChanged](http://msdn2.microsoft.com/en-us/library/ms668629) collection of [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) elements (the items which the [ItemMetadata](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.itemmetadata(v=pandp.50)) wraps).


## Inheritance Hierarchy

[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)<br/>
    Microsoft.Practices.Prism.Regions.ViewsCollection

## See Also

[ViewsCollection Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.viewscollection_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))






