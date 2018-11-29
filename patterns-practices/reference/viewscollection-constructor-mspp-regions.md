---
TOCTitle: ViewsCollection Constructor
Title: 'ViewsCollection Constructor (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.ViewsCollection.\#ctor(System.Collections.ObjectModel.ObservableCollection{Microsoft.Practices.Prism.Regions.ItemMetadata},System.Predicate{Microsoft.Practices.Prism.Regions.ItemMetadata})'
ms:mtpsurl: 'viewscollection-constructor-mspp-regions.md'
---

# ViewsCollection Constructor

Initializes a new instance of the [ViewsCollection](/patterns-practices/reference/viewscollection-class-mspp-regions) class.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ViewsCollection(
	ObservableCollection<ItemMetadata> list,
	Predicate<ItemMetadata> filter
)
```

### Parameters

*list*  
Type: [System.Collections.ObjectModel.ObservableCollection](http://msdn.microsoft.com/en-us/library/ms668604)&lt;[ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions)&gt;  
The list to wrap and filter.

*filter*  
Type: [System.Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)&lt;[ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions)&gt;  
A predicate to filter the list collection.

## Syntax

```VB
'Declaration
Public Sub New ( 
	list As ObservableCollection(Of ItemMetadata),
	filter As Predicate(Of ItemMetadata)
)
```

### Parameters

*list*  
Type: [System.Collections.ObjectModel.ObservableCollection](http://msdn.microsoft.com/en-us/library/ms668604)(Of [ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions))  
The list to wrap and filter.

*filter*  
Type: [System.Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)(Of [ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions))  
A predicate to filter the list collection.

## See Also

[ViewsCollection Class](/patterns-practices/reference/viewscollection-class-mspp-regions)  
[ViewsCollection Members](/patterns-practices/reference/viewscollection-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  