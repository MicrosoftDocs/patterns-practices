---
TOCTitle: ModuleInfoGroup Properties
Title: 'ModuleInfoGroup Properties (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431175(v=PandP.50)'
---

Prism Class Library

ModuleInfoGroup Properties
==========================

Include Protected Members
Include Inherited Members

The [ModuleInfoGroup](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup) type exposes the following members.

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif "Public property")
[Count](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.count)
Gets the number of elements contained in the [ModuleInfoGroup](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup).

![](https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif "Public property")
[InitializationMode](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.initializationmode)
Gets or sets the [InitializationMode](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.initializationmode) for the whole group. Any [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) classes that are added after setting this value will also get this [InitializationMode](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.initializationmode).

![](https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif "Public property")
[IsFixedSize](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.isfixedsize)
Gets a value indicating whether the [ModuleInfoGroup](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup) has a fixed size.

![](https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif "Public property")
[IsReadOnly](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.isreadonly)
Gets a value indicating whether the [ModuleInfoGroup](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup) is read-only.

![](https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif "Public property")
[IsSynchronized](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.issynchronized)
Gets a value indicating whether access to the [ICollection](http://msdn2.microsoft.com/en-us/library/b1ht6113) is synchronized (thread safe).

![](https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif "Public property")
[Item](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.item(system.int32))
Gets or sets the [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) at the specified index.

![](https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif "Public property")
[Ref](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.ref)
Gets or sets the [Ref](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.ref) value for the whole group. Any [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) classes that are added after setting this value will also get this [Ref](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.ref). The ref value will also be used by the [IModuleManager](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulemanager) to determine which [IModuleTypeLoader](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imoduletypeloader) to use. For example, using an "file://" prefix with a valid URL will cause the FileModuleTypeLoader to be used (Only available in the desktop version of CAL).

![](https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif "Public property")
[SyncRoot](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.syncroot)
Gets an object that can be used to synchronize access to the [ICollection](http://msdn2.microsoft.com/en-us/library/b1ht6113).

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleInfoGroup Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
