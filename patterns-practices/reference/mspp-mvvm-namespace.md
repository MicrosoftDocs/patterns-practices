---
TOCTitle: 'Microsoft.Practices.Prism.Mvvm Namespace'
Title: 'Microsoft.Practices.Prism.Mvvm Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Mvvm'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736243(v=PandP.50)'
---

Prism Class Library

Microsoft.Practices.Prism.Mvvm Namespace
========================================

 

Classes
-------

<span id="classToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Dn736243.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.mvvm.bindablebase">BindableBase</a></td>
<td><div class="summary">
Implementation of <a href="http://msdn.microsoft.com/en-us/library/ms133020">INotifyPropertyChanged</a> to simplify models.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn736243.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.mvvm.propertysupport">PropertySupport</a></td>
<td><div class="summary">
Provides support for extracting property information based on a property expression.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn736243.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.mvvm.viewmodellocationprovider">ViewModelLocationProvider</a></td>
<td><div class="summary">
The ViewModelLocationProvider class locates the view model for the view that has the AutoWireViewModelChanged attached property set to true. The view model will be located and injected into the view's DataContext. To locate the view, two strategies are used: First the ViewModelLocationProvider will look to see if there is a view model factory registered for that view, if not it will try to infer the view model using a convention based approach. This class also provide methods for registering the view model factories, and also to override the default view model factory and the default view type to view model type resolver.
</div></td>
</tr>
</tbody>
</table>

Interfaces
----------

<span id="interfaceToggle"></span>
|                                                                                                    | Interface                                                                  | Description |
|----------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|-------------|
| ![](https://msdn.microsoft.com/en-us/Dn736243.pubinterface(en-us,PandP.50).gif "Public interface") | [IView](https://msdn.microsoft.com/t:microsoft.practices.prism.mvvm.iview) |             |
