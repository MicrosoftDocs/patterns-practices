---
TOCTitle: ModuleInfoGroup Properties
Title: 'ModuleInfoGroup Properties (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup'
ms:mtpsurl: 'moduleinfogroup-properties-mspp-modularity.md'
---


# ModuleInfoGroup Properties

The [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) type exposes the following members.

## Properties


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
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Count](/patterns-practices/reference/moduleinfogroup-count-property-mspp-modularity)</td>
<td><div class="summary">
Gets the number of elements contained in the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity).
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[InitializationMode](/patterns-practices/reference/moduleinfogroup-initializationmode-property-mspp-modularity)</td>
<td><div class="summary">
Gets or sets the [InitializationMode](/patterns-practices/reference/moduleinfo-initializationmode-property-mspp-modularity) for the whole group. Any [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) classes that are added after setting this value will also get this [InitializationMode](/patterns-practices/reference/moduleinfogroup-initializationmode-property-mspp-modularity).
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[IsFixedSize](/patterns-practices/reference/moduleinfogroup-isfixedsize-property-mspp-modularity)</td>
<td><div class="summary">
Gets a value indicating whether the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) has a fixed size.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[IsReadOnly](/patterns-practices/reference/moduleinfogroup-isreadonly-property-mspp-modularity)</td>
<td><div class="summary">
Gets a value indicating whether the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) is read-only.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[IsSynchronized](/patterns-practices/reference/moduleinfogroup-issynchronized-property-mspp-modularity)</td>
<td><div class="summary">
Gets a value indicating whether access to the [ICollection](http://msdn.microsoft.com/en-us/library/b1ht6113) is synchronized (thread safe).
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Item](/patterns-practices/reference/moduleinfogroup-item-property-mspp-modularity)</td>
<td><div class="summary">
Gets or sets the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) at the specified index.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Ref](/patterns-practices/reference/moduleinfogroup-ref-property-mspp-modularity)</td>
<td><div class="summary">
Gets or sets the [Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity) value for the whole group. Any [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) classes that are added after setting this value will also get this [Ref](/patterns-practices/reference/moduleinfogroup-ref-property-mspp-modularity). The ref value will also be used by the [IModuleManager](/patterns-practices/reference/imodulemanager-interface-mspp-modularity) to determine which [IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity) to use. For example, using an &quot;file://&quot; prefix with a valid URL will cause the FileModuleTypeLoader to be used (Only available in the desktop version of CAL).
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[SyncRoot](/patterns-practices/reference/moduleinfogroup-syncroot-property-mspp-modularity)</td>
<td><div class="summary">
Gets an object that can be used to synchronize access to the [ICollection](http://msdn.microsoft.com/en-us/library/b1ht6113).
</div></td>
</tr>
</tbody>
</table>

## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
