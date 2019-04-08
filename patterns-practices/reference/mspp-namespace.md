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
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/bootstrapper-class-mspp" data-raw-source="[Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp)">Bootstrapper</a></td>
<td><div class="summary">
Base class that provides a basic bootstrapping sequence and hooks that specific implementations can override
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/collectionextensions-class-mspp" data-raw-source="[CollectionExtensions](/patterns-practices/reference/collectionextensions-class-mspp)">CollectionExtensions</a></td>
<td><div class="summary">
Class that provides extension methods to Collection
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/exceptionextensions-class-mspp" data-raw-source="[ExceptionExtensions](/patterns-practices/reference/exceptionextensions-class-mspp)">ExceptionExtensions</a></td>
<td><div class="summary">
Class that provides extension methods for the Exception class. These extension methods provide a mechanism for developers to get more easily to the root cause of an exception, especially in combination with DI-containers such as Unity.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp" data-raw-source="[ListDictionary(Of TKey, TValue)](/patterns-practices/reference/listdictionary-tkey-tvalue-class-mspp)">ListDictionary(Of TKey, TValue)</a></td>
<td><div class="summary">
A dictionary of lists.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/observableobject-t-class-mspp" data-raw-source="[ObservableObject(Of T)](/patterns-practices/reference/observableobject-t-class-mspp)">ObservableObject(Of T)</a></td>
<td><div class="summary">
Class that wraps an object, so that other classes can notify for Change events. Typically, this class is set as a Dependency Property on DependencyObjects, and allows other classes to observe any changes in the Value.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/servicelocatorextensions-class-mspp" data-raw-source="[ServiceLocatorExtensions](/patterns-practices/reference/servicelocatorextensions-class-mspp)">ServiceLocatorExtensions</a></td>
<td><div class="summary">
Defines extension methods for the ServiceLocator class.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/uriparsinghelper-class-mspp" data-raw-source="[UriParsingHelper](/patterns-practices/reference/uriparsinghelper-class-mspp)">UriParsingHelper</a></td>
<td><div class="summary">
Helper class for parsing <a href="http://msdn.microsoft.com/en-us/library/txt7706a" data-raw-source="[Uri](http://msdn.microsoft.com/en-us/library/txt7706a)">Uri</a> instances.
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
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iactiveaware-class-mspp" data-raw-source="[IActiveAware](/patterns-practices/reference/iactiveaware-class-mspp)">IActiveAware</a></td>
<td><div class="summary">
Interface that defines if the object instance is active and notifies when the activity changes.
</div></td>
</tr>
</tbody>
</table>
