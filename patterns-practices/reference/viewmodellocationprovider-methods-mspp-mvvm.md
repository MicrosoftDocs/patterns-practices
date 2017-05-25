---
TOCTitle: ViewModelLocationProvider Methods
Title: 'ViewModelLocationProvider Methods (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Mvvm.ViewModelLocationProvider'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736106(v=PandP.50)'
---

Prism Class Library

ViewModelLocationProvider Methods
=================================

The [ViewModelLocationProvider](https://msdn.microsoft.com/library/microsoft.practices.prism.mvvm.viewmodellocationprovider) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Dn736106.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mvvm.viewmodellocationprovider.autowireviewmodelchanged(microsoft.practices.prism.mvvm.iview)">AutoWireViewModelChanged</a></td>
<td><div class="summary">
Automatically looks up the viewmodel that corresponds to the current view, using two strategies: It first looks to see if there is a mapping registered for that view, if not it will fallback to the convention based approach.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Dn736106.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mvvm.viewmodellocationprovider.register(system.string%2csystem.func%7bsystem.object%7d)">Register</a></td>
<td><div class="summary">
Registers the view model factory for the specified view type name.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Dn736106.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mvvm.viewmodellocationprovider.setdefaultviewmodelfactory(system.func%7bsystem.type%2csystem.object%7d)">SetDefaultViewModelFactory</a></td>
<td><div class="summary">
Sets the default view model factory.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Dn736106.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mvvm.viewmodellocationprovider.setdefaultviewtypetoviewmodeltyperesolver(system.func%7bsystem.type%2csystem.type%7d)">SetDefaultViewTypeToViewModelTypeResolver</a></td>
<td><div class="summary">
Sets the default view type to view model type resolver.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[ViewModelLocationProvider Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mvvm.viewmodellocationprovider)

[Microsoft.Practices.Prism.Mvvm Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mvvm)
