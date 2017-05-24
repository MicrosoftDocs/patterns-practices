---
TOCTitle: FileModuleTypeLoader Members
Title: 'FileModuleTypeLoader Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.FileModuleTypeLoader'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430827(v=PandP.50)'
---

Prism Class Library

FileModuleTypeLoader Members
============================

Include Protected Members
Include Inherited Members

The [FileModuleTypeLoader](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.filemoduletypeloader) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430827.pubmethod(en-us,PandP.50).gif "Public method")
[FileModuleTypeLoader()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.filemoduletypeloader.)
Initializes a new instance of the [FileModuleTypeLoader](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.filemoduletypeloader) class.

![](https://msdn.microsoft.com/en-us/Gg430827.pubmethod(en-us,PandP.50).gif "Public method")
[FileModuleTypeLoader(IAssemblyResolver)](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.filemoduletypeloader.)
Initializes a new instance of the [FileModuleTypeLoader](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.filemoduletypeloader) class.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430827.pubmethod(en-us,PandP.50).gif "Public method")
[CanLoadModuleType](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.filemoduletypeloader.canloadmoduletype(microsoft.practices.prism.modularity.moduleinfo))
Evaluates the [Ref](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.ref) property to see if the current typeloader will be able to retrieve the moduleInfo. Returns true if the [Ref](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.ref) property starts with "file://", because this indicates that the file is a local file.

![](https://msdn.microsoft.com/en-us/Gg430827.pubmethod(en-us,PandP.50).gif "Public method")
[Dispose()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.filemoduletypeloader.dispose)
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

![](https://msdn.microsoft.com/en-us/Gg430827.protmethod(en-us,PandP.50).gif "Protected method")
[Dispose(Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.filemoduletypeloader.dispose(system.boolean))
Disposes the associated [AssemblyResolver](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.assemblyresolver).

![](https://msdn.microsoft.com/en-us/Gg430827.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430827.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430827.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430827.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430827.pubmethod(en-us,PandP.50).gif "Public method")
[LoadModuleType](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.filemoduletypeloader.loadmoduletype(microsoft.practices.prism.modularity.moduleinfo))
Retrieves the moduleInfo.

![](https://msdn.microsoft.com/en-us/Gg430827.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430827.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)

Events
------

<span id="eventTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430827.pubevent(en-us,PandP.50).gif "Public event")
[LoadModuleCompleted](https://msdn.microsoft.com/e:microsoft.practices.prism.modularity.filemoduletypeloader.loadmodulecompleted)
Raised when a module is loaded or fails to load.

![](https://msdn.microsoft.com/en-us/Gg430827.pubevent(en-us,PandP.50).gif "Public event")
[ModuleDownloadProgressChanged](https://msdn.microsoft.com/e:microsoft.practices.prism.modularity.filemoduletypeloader.moduledownloadprogresschanged)
Raised repeatedly to provide progress as modules are loaded in the background.

See Also
--------

<span id="seeAlsoToggle"></span>
[FileModuleTypeLoader Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.filemoduletypeloader)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
