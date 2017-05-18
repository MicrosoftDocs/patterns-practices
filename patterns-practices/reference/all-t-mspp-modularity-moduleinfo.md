---
TOCTitle: ModuleInfo Members
Title: 'ModuleInfo Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.ModuleInfo'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430846(v=PandP.50)'
---

Prism Class Library

ModuleInfo Members
==================

Include Protected Members
Include Inherited Members

The [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430846.pubmethod(en-us,PandP.50).gif "Public method")
[ModuleInfo()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinfo.)
Initializes a new empty instance of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo).

![](https://msdn.microsoft.com/en-us/Gg430846.pubmethod(en-us,PandP.50).gif "Public method")
[ModuleInfo(String, String)](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinfo.)
Initializes a new instance of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo).

![](https://msdn.microsoft.com/en-us/Gg430846.pubmethod(en-us,PandP.50).gif "Public method")
[ModuleInfo(String, String, array&lt;String&gt;\[\]()\[\])](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinfo.)
Initializes a new instance of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo).

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430846.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430846.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430846.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430846.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430846.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430846.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430846.pubproperty(en-us,PandP.50).gif "Public property")
[DependsOn](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.dependson)
Gets or sets the list of modules that this module depends upon.

![](https://msdn.microsoft.com/en-us/Gg430846.pubproperty(en-us,PandP.50).gif "Public property")
[InitializationMode](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.initializationmode)
Specifies on which stage the Module will be initialized.

![](https://msdn.microsoft.com/en-us/Gg430846.pubproperty(en-us,PandP.50).gif "Public property")
[ModuleName](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.modulename)
Gets or sets the name of the module.

![](https://msdn.microsoft.com/en-us/Gg430846.pubproperty(en-us,PandP.50).gif "Public property")
[ModuleType](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.moduletype)
Gets or sets the module [Type](http://msdn2.microsoft.com/en-us/library/42892f65)'s AssemblyQualifiedName.

![](https://msdn.microsoft.com/en-us/Gg430846.pubproperty(en-us,PandP.50).gif "Public property")
[Ref](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.ref)
Reference to the location of the module assembly.
Examples
--------

<span id="exampleToggle"></span>The following are examples of valid [Ref](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.ref) values: file://c:/MyProject/Modules/MyModule.dll for a loose DLL in WPF.

![](https://msdn.microsoft.com/en-us/Gg430846.pubproperty(en-us,PandP.50).gif "Public property")
[State](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.state)
Gets or sets the state of the [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) with regards to the module loading and initialization process.

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleInfo Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
