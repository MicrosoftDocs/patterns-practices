---
TOCTitle: ModuleExportAttribute Properties
Title: 'ModuleExportAttribute Properties (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.MefExtensions.Modularity.ModuleExportAttribute'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419179(v=PandP.50)'
---

Prism Class Library

ModuleExportAttribute Properties
================================

Include Protected Members
Include Inherited Members

The [ModuleExportAttribute](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.moduleexportattribute) type exposes the following members.

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif "Public property")
[ContractName](http://msdn2.microsoft.com/en-us/library/dd235084)
Gets the contract name that is used to export the type or member marked with this attribute.

(Inherited from [ExportAttribute](http://msdn2.microsoft.com/en-us/library/dd234971).)
![](https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif "Public property")
[ContractType](http://msdn2.microsoft.com/en-us/library/dd833425)
Gets the contract type that is exported by the member that this attribute is attached to.

(Inherited from [ExportAttribute](http://msdn2.microsoft.com/en-us/library/dd234971).)
![](https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif "Public property")
[DependsOnModuleNames](https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.modularity.moduleexportattribute.dependsonmodulenames)
Gets or sets the contract names of modules this module depends upon.

![](https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif "Public property")
[InitializationMode](https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.modularity.moduleexportattribute.initializationmode)
Gets or sets when the module should have Initialize() called.

![](https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif "Public property")
[ModuleName](https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.modularity.moduleexportattribute.modulename)
Gets the contract name of the module.

![](https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif "Public property")
[ModuleType](https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.modularity.moduleexportattribute.moduletype)
Gets concrete type of the module being exported. Not typeof(IModule).

![](https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif "Public property")
[TypeId](http://msdn2.microsoft.com/en-us/library/sa1bf03e)
When implemented in a derived class, gets a unique identifier for this [Attribute](http://msdn2.microsoft.com/en-us/library/e8kc3626).

(Inherited from [Attribute](http://msdn2.microsoft.com/en-us/library/e8kc3626).)

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleExportAttribute Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.moduleexportattribute)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.modularity)
