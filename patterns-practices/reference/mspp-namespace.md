---
TOCTitle: 'Microsoft.Practices.Prism Namespace'
Title: 'Microsoft.Practices.Prism Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419033(v=PandP.50)'
---

Prism Class Library

Microsoft.Practices.Prism Namespace
===================================

 

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
<td><img src="https://msdn.microsoft.com/en-us/Gg419033.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper">Bootstrapper</a></td>
<td><div class="summary">
Base class that provides a basic bootstrapping sequence and hooks that specific implementations can override
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419033.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.collectionextensions">CollectionExtensions</a></td>
<td><div class="summary">
Class that provides extension methods to Collection
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419033.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.exceptionextensions">ExceptionExtensions</a></td>
<td><div class="summary">
Class that provides extension methods for the Exception class. These extension methods provide a mechanism for developers to get more easily to the root cause of an exception, especially in combination with DI-containers such as Unity.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419033.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.listdictionary%602">ListDictionary&lt;(Of &lt;(TKey, TValue&gt;)&gt;)</a></td>
<td><div class="summary">
A dictionary of lists.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419033.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.observableobject%601">ObservableObject&lt;(Of &lt;(T&gt;)&gt;)</a></td>
<td><div class="summary">
Class that wraps an object, so that other classes can notify for Change events. Typically, this class is set as a Dependency Property on DependencyObjects, and allows other classes to observe any changes in the Value.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419033.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.servicelocatorextensions">ServiceLocatorExtensions</a></td>
<td><div class="summary">
Defines extension methods for the ServiceLocator class.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419033.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.uriparsinghelper">UriParsingHelper</a></td>
<td><div class="summary">
Helper class for parsing <a href="http://msdn.microsoft.com/en-us/library/txt7706a">Uri</a> instances.
</div></td>
</tr>
</tbody>
</table>

Interfaces
----------

<span id="interfaceToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Interface</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419033.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.iactiveaware">IActiveAware</a></td>
<td><div class="summary">
Interface that defines if the object instance is active and notifies when the activity changes.
</div></td>
</tr>
</tbody>
</table>
