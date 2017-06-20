---
TOCTitle: ViewModelLocationProvider Methods
Title: 'ViewModelLocationProvider Methods (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Mvvm.ViewModelLocationProvider'
ms:mtpsurl: 'viewmodellocationprovider-methods-mspp-mvvm.md'
---

# ViewModelLocationProvider Methods

The [ViewModelLocationProvider](/patterns-practices/reference/viewmodellocationprovider-class-mspp-mvvm) type exposes the following members.

## Methods

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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[AutoWireViewModelChanged](/patterns-practices/reference/viewmodellocationprovider-autowireviewmodelchanged-method-mspp-mvvm))</td>
<td><div class="summary">
Automatically looks up the viewmodel that corresponds to the current view, using two strategies: It first looks to see if there is a mapping registered for that view, if not it will fallback to the convention based approach.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[Register](/patterns-practices/reference/viewmodellocationprovider-register-method-mspp-mvvm)</td>
<td><div class="summary">
Registers the view model factory for the specified view type name.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[SetDefaultViewModelFactory](/patterns-practices/reference/viewmodellocationprovider-setdefaultviewmodelfactory-method-mspp-mvvm)</td>
<td><div class="summary">
Sets the default view model factory.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[SetDefaultViewTypeToViewModelTypeResolver](/patterns-practices/reference/viewmodellocationprovider-setdefaultviewtypetoviewmodeltyperesolver-method-mspp-mvvm)</td>
<td><div class="summary">
Sets the default view type to view model type resolver.
</div></td>
</tr>
</tbody>
</table>

## See Also

[ViewModelLocationProvider Class](/patterns-practices/reference/viewmodellocationprovider-class-mspp-mvvm)  
[Microsoft.Practices.Prism.Mvvm Namespace](/patterns-practices/reference/mspp-mvvm-namespace)