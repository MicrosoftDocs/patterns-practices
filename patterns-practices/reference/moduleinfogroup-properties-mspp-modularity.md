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
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfogroup-count-property-mspp-modularity" data-raw-source="[Count](/patterns-practices/reference/moduleinfogroup-count-property-mspp-modularity)">Count</a></td>
<td><div class="summary">
Gets the number of elements contained in the <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity" data-raw-source="[ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)">ModuleInfoGroup</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfogroup-initializationmode-property-mspp-modularity" data-raw-source="[InitializationMode](/patterns-practices/reference/moduleinfogroup-initializationmode-property-mspp-modularity)">InitializationMode</a></td>
<td><div class="summary">
Gets or sets the <a href="/patterns-practices/reference/moduleinfo-initializationmode-property-mspp-modularity" data-raw-source="[InitializationMode](/patterns-practices/reference/moduleinfo-initializationmode-property-mspp-modularity)">InitializationMode</a> for the whole group. Any <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a> classes that are added after setting this value will also get this <a href="/patterns-practices/reference/moduleinfogroup-initializationmode-property-mspp-modularity" data-raw-source="[InitializationMode](/patterns-practices/reference/moduleinfogroup-initializationmode-property-mspp-modularity)">InitializationMode</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfogroup-isfixedsize-property-mspp-modularity" data-raw-source="[IsFixedSize](/patterns-practices/reference/moduleinfogroup-isfixedsize-property-mspp-modularity)">IsFixedSize</a></td>
<td><div class="summary">
Gets a value indicating whether the <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity" data-raw-source="[ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)">ModuleInfoGroup</a> has a fixed size.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfogroup-isreadonly-property-mspp-modularity" data-raw-source="[IsReadOnly](/patterns-practices/reference/moduleinfogroup-isreadonly-property-mspp-modularity)">IsReadOnly</a></td>
<td><div class="summary">
Gets a value indicating whether the <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity" data-raw-source="[ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)">ModuleInfoGroup</a> is read-only.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfogroup-issynchronized-property-mspp-modularity" data-raw-source="[IsSynchronized](/patterns-practices/reference/moduleinfogroup-issynchronized-property-mspp-modularity)">IsSynchronized</a></td>
<td><div class="summary">
Gets a value indicating whether access to the <a href="http://msdn.microsoft.com/en-us/library/b1ht6113" data-raw-source="[ICollection](http://msdn.microsoft.com/en-us/library/b1ht6113)">ICollection</a> is synchronized (thread safe).
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfogroup-item-property-mspp-modularity" data-raw-source="[Item](/patterns-practices/reference/moduleinfogroup-item-property-mspp-modularity)">Item</a></td>
<td><div class="summary">
Gets or sets the <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a> at the specified index.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfogroup-ref-property-mspp-modularity" data-raw-source="[Ref](/patterns-practices/reference/moduleinfogroup-ref-property-mspp-modularity)">Ref</a></td>
<td><div class="summary">
Gets or sets the <a href="/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity" data-raw-source="[Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity)">Ref</a> value for the whole group. Any <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a> classes that are added after setting this value will also get this <a href="/patterns-practices/reference/moduleinfogroup-ref-property-mspp-modularity" data-raw-source="[Ref](/patterns-practices/reference/moduleinfogroup-ref-property-mspp-modularity)">Ref</a>. The ref value will also be used by the <a href="/patterns-practices/reference/imodulemanager-interface-mspp-modularity" data-raw-source="[IModuleManager](/patterns-practices/reference/imodulemanager-interface-mspp-modularity)">IModuleManager</a> to determine which <a href="/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity" data-raw-source="[IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)">IModuleTypeLoader</a> to use. For example, using an &quot;file://&quot; prefix with a valid URL will cause the FileModuleTypeLoader to be used (Only available in the desktop version of CAL).
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfogroup-syncroot-property-mspp-modularity" data-raw-source="[SyncRoot](/patterns-practices/reference/moduleinfogroup-syncroot-property-mspp-modularity)">SyncRoot</a></td>
<td><div class="summary">
Gets an object that can be used to synchronize access to the <a href="http://msdn.microsoft.com/en-us/library/b1ht6113" data-raw-source="[ICollection](http://msdn.microsoft.com/en-us/library/b1ht6113)">ICollection</a>.
</div></td>
</tr>
</tbody>
</table>

## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  