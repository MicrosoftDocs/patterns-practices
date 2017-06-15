---
TOCTitle: MefModuleInitializer Members
Title: 'MefModuleInitializer Members (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleInitializer'
ms:mtpsurl: 'mefmoduleinitializer-members-mspp-mefextensions-modularity.md'
---

# MefModuleInitializer Members

The [MefModuleInitializer](/patterns-practices/reference/mefmoduleinitializer-class-mspp-mefextensions-modularity) type exposes the following members.

## Constructors

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>MefModuleInitializer</td>
<td>Initializes a new instance of the [MefModuleInitializer](/patterns-practices/reference/mefmoduleinitializer-class-mspp-mefextensions-modularity) class.</td>
</tr>
</tbody>
</table>

## Methods

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateModule(String)](/patterns-practices/reference/moduleinitializer-createmodule-method-string-mspp-modularity)</td>
<td>Uses the container to resolve a new [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity) by specifying its [Type](http://msdn.microsoft.com/en-us/library/42892f65).
(Inherited from [ModuleInitializer](/patterns-practices/reference/moduleinitializer-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateModule(ModuleInfo)](/patterns-practices/reference/mefmoduleinitializer-createmodule-method-moduleinfo-mspp-mefextensions-modularity)</td>
<td>Uses the container to resolve a new [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity) by specifying its [Type](http://msdn.microsoft.com/en-us/library/42892f65).
(Overrides [ModuleInitializer.CreateModule(ModuleInfo)](/patterns-practices/reference/moduleinitializer-createmodule-method-moduleinfo-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td>Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td>Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td>Serves as a hash function for a particular type.
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td>Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[HandleModuleInitializationError](/patterns-practices/reference/moduleinitializer-handlemoduleinitializationerror-method-mspp-modularity)</td>
<td>Handles any exception occurred in the module Initialization process, logs the error using the [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) and throws a [ModuleInitializeException](/patterns-practices/reference/moduleinitializeexception-class-mspp-modularity). This method can be overridden to provide a different behavior.
(Inherited from [ModuleInitializer](/patterns-practices/reference/moduleinitializer-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Initialize](/patterns-practices/reference/moduleinitializer-initialize-method-mspp-modularity)</td>
<td>Initializes the specified module.
(Inherited from [ModuleInitializer](/patterns-practices/reference/moduleinitializer-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td>Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td>Returns a string that represents the current object.
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
</tbody>
</table>

## See Also

[MefModuleInitializer Class](/patterns-practices/reference/mefmoduleinitializer-class-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
