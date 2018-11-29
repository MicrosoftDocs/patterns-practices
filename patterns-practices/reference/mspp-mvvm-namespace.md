---
TOCTitle: 'Microsoft.Practices.Prism.Mvvm Namespace'
Title: 'Microsoft.Practices.Prism.Mvvm Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Mvvm'
ms:mtpsurl: 'mspp-mvvm-namespace.md'
---

# Microsoft.Practices.Prism.Mvvm Namespace

## Classes

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Class</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/bindablebase-class-mspp-mvvm" data-raw-source="[BindableBase](/patterns-practices/reference/bindablebase-class-mspp-mvvm)">BindableBase</a></td>
<td><div class="summary">
Implementation of <a href="http://msdn.microsoft.com/en-us/library/ms133020" data-raw-source="[INotifyPropertyChanged](http://msdn.microsoft.com/en-us/library/ms133020)">INotifyPropertyChanged</a> to simplify models.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/propertysupport-class-mspp-mvvm" data-raw-source="[PropertySupport](/patterns-practices/reference/propertysupport-class-mspp-mvvm)">PropertySupport</a></td>
<td><div class="summary">
Provides support for extracting property information based on a property expression.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/viewmodellocationprovider-class-mspp-mvvm" data-raw-source="[ViewModelLocationProvider](/patterns-practices/reference/viewmodellocationprovider-class-mspp-mvvm)">ViewModelLocationProvider</a></td>
<td>
 The ViewModelLocationProvider class locates the view model for the view that has the AutoWireViewModelChanged attached property set to true. The view model will be located and injected into the view&#39;s DataContext. To locate the view, two strategies are used: First the ViewModelLocationProvider will look to see if there is a view model factory registered for that view, if not it will try to infer the view model using a convention based approach. This class also provide methods for registering the view model factories, and also to override the default view model factory and the default view type to view model type resolver. 
</td>
</tr>
</tbody>
</table>

## Interfaces

<table>
<thead>
<tr class="header">
<th> </th>
<th>Interface</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iview-interface-mspp-mvvm" data-raw-source="[IView](/patterns-practices/reference/iview-interface-mspp-mvvm)">IView</a></td>
<td></td>
</tr>
</tbody>
</table>