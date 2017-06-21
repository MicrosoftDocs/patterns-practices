---
TOCTitle: 'Microsoft.Practices.Prism Namespace'
Title: 'Microsoft.Practices.Prism Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism'
ms:mtpsurl: 'mspp-namespace.md'
---

# Microsoft.Practices.Prism Namespace

## Classes

<table>

<thead>
<tr class="header">
<th> </th>
<th>Class</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp)</td>
<td><div class="summary">
Base class that provides a basic bootstrapping sequence and hooks that specific implementations can override
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[CollectionExtensions](/patterns-practices/reference/collectionextensions-class-mspp)</td>
<td><div class="summary">
Class that provides extension methods to Collection
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ExceptionExtensions](/patterns-practices/reference/exceptionextensions-class-mspp)</td>
<td><div class="summary">
Class that provides extension methods for the Exception class. These extension methods provide a mechanism for developers to get more easily to the root cause of an exception, especially in combination with DI-containers such as Unity.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ListDictionary(Of TKey, TValue)](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)</td>
<td><div class="summary">
A dictionary of lists.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ObservableObject(Of T)](/patterns-practices/reference/observableobject-t-class-mspp)</td>
<td><div class="summary">
Class that wraps an object, so that other classes can notify for Change events. Typically, this class is set as a Dependency Property on DependencyObjects, and allows other classes to observe any changes in the Value.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ServiceLocatorExtensions](/patterns-practices/reference/servicelocatorextensions-class-mspp)</td>
<td><div class="summary">
Defines extension methods for the ServiceLocator class.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[UriParsingHelper](/patterns-practices/reference/uriparsinghelper-class-mspp)</td>
<td><div class="summary">
Helper class for parsing [Uri](http://msdn.microsoft.com/en-us/library/txt7706a) instances.
</div></td>
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
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IActiveAware](/patterns-practices/reference/iactiveaware-class-mspp)</td>
<td><div class="summary">
Interface that defines if the object instance is active and notifies when the activity changes.
</div></td>
</tr>
</tbody>
</table>
