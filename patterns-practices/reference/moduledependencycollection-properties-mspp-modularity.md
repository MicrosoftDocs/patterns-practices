---
TOCTitle: ModuleDependencyCollection Properties
Title: 'ModuleDependencyCollection Properties (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Modularity.ModuleDependencyCollection'
ms:mtpsurl: 'moduledependencycollection-properties-mspp-modularity.md'
---

# ModuleDependencyCollection Properties

The [ModuleDependencyCollection](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduledependencycollection) type exposes the following members.

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
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[AddElementName](http://msdn.microsoft.com/en-us/library/ms134167)</td>
<td><div class="summary">
Gets or sets the name of the [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3) to associate with the add operation in the [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et) when overridden in a derived class.
</div>
(Inherited from [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et).)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ClearElementName](http://msdn.microsoft.com/en-us/library/ms134168)</td>
<td><div class="summary">
Gets or sets the name for the [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3) to associate with the clear operation in the [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et) when overridden in a derived class.
</div>
(Inherited from [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[CollectionType](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduledependencycollection.collectiontype)</td>
<td><div class="summary">
Gets the type of the [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et).
</div>
(Overrides [ConfigurationElementCollection..::.CollectionType](http://msdn.microsoft.com/en-us/library/x4skd9kd).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Count](http://msdn.microsoft.com/en-us/library/yf0s34t1)</td>
<td><div class="summary">
Gets the number of elements in the collection.
</div>
(Inherited from [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[CurrentConfiguration](http://msdn.microsoft.com/en-us/library/dd412601)</td>
<td><div class="summary">
Gets a reference to the top-level [Configuration](http://msdn.microsoft.com/en-us/library/s7kc101z) instance that represents the configuration hierarchy that the current [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3) instance belongs to.
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ElementInformation](http://msdn.microsoft.com/en-us/library/ms134142)</td>
<td><div class="summary">
Gets an [ElementInformation](http://msdn.microsoft.com/en-us/library/ms134413) object that contains the non-customizable information and functionality of the [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3) object.
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="odd">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ElementName](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduledependencycollection.elementname)</td>
<td><div class="summary">
Gets the name used to identify this collection of elements in the configuration file when overridden in a derived class.
</div>
(Overrides [ConfigurationElementCollection..::.ElementName](http://msdn.microsoft.com/en-us/library/8f06bh6s).)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ElementProperty](http://msdn.microsoft.com/en-us/library/ms134143)</td>
<td><div class="summary">
Gets the [ConfigurationElementProperty](http://msdn.microsoft.com/en-us/library/ms134174) object that represents the [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3) object itself.
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[EmitClear](http://msdn.microsoft.com/en-us/library/adedfexe)</td>
<td><div class="summary">
Gets or sets a value that specifies whether the collection has been cleared.
</div>
(Inherited from [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et).)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[EvaluationContext](http://msdn.microsoft.com/en-us/library/ms134144)</td>
<td><div class="summary">
Gets the [ContextInformation](http://msdn.microsoft.com/en-us/library/ms134368) object for the [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3) object.
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="odd">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[HasContext](http://msdn.microsoft.com/en-us/library/hh136640)</td>
<td><div class="summary">
Gets a value that indicates whether the [CurrentConfiguration](http://msdn.microsoft.com/en-us/library/dd412601) property is null.
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[IsSynchronized](http://msdn.microsoft.com/en-us/library/ms134169)</td>
<td><div class="summary">
Gets a value indicating whether access to the collection is synchronized.
</div>
(Inherited from [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et).)</td>
</tr>
<tr class="odd">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[Item[([(ConfigurationProperty])])](http://msdn.microsoft.com/en-us/library/es150ftc)</td>
<td><div class="summary">
Gets or sets a property or attribute of this configuration element.
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[Item[([(String])])](http://msdn.microsoft.com/en-us/library/c8693ks1)</td>
<td><div class="summary">
Gets or sets a property, attribute, or child element of this configuration element.
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Item[([(Int32])])](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduledependencycollection.item(system.int32))</td>
<td><div class="summary">
Gets the [ModuleDependencyConfigurationElement](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduledependencyconfigurationelement) located at the specified index in the collection.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[LockAllAttributesExcept](http://msdn.microsoft.com/en-us/library/ms134146)</td>
<td><div class="summary">
Gets the collection of locked attributes.
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[LockAllElementsExcept](http://msdn.microsoft.com/en-us/library/ms134147)</td>
<td><div class="summary">
Gets the collection of locked elements.
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[LockAttributes](http://msdn.microsoft.com/en-us/library/ms134148)</td>
<td><div class="summary">
Gets the collection of locked attributes
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[LockElements](http://msdn.microsoft.com/en-us/library/ms134149)</td>
<td><div class="summary">
Gets the collection of locked elements.
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[LockItem](http://msdn.microsoft.com/en-us/library/ms134150)</td>
<td><div class="summary">
Gets or sets a value indicating whether the element is locked.
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="odd">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[Properties](http://msdn.microsoft.com/en-us/library/3kx8tt8d)</td>
<td><div class="summary">
Gets the collection of properties.
</div>
(Inherited from [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3).)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[RemoveElementName](http://msdn.microsoft.com/en-us/library/ms134170)</td>
<td><div class="summary">
Gets or sets the name of the [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3) to associate with the remove operation in the [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et) when overridden in a derived class.
</div>
(Inherited from [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[SyncRoot](http://msdn.microsoft.com/en-us/library/ms134171)</td>
<td><div class="summary">
Gets an object used to synchronize access to the [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et).
</div>
(Inherited from [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et).)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ThrowOnDuplicate](http://msdn.microsoft.com/en-us/library/ea6s6hb8)</td>
<td><div class="summary">
Gets a value indicating whether an attempt to add a duplicate [ConfigurationElement](http://msdn.microsoft.com/en-us/library/kyx77cz3) to the [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et) will cause an exception to be thrown.
</div>
(Inherited from [ConfigurationElementCollection](http://msdn.microsoft.com/en-us/library/a35we8et).)</td>
</tr>
</tbody>
</table>

## See Also
[ModuleDependencyCollection Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduledependencycollection)  
[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)  