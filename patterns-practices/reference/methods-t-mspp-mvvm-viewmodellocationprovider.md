---
TOCTitle: ViewModelLocationProvider Methods
Title: 'ViewModelLocationProvider Methods (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Mvvm.ViewModelLocationProvider'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736106(v=PandP.50)'
---

Prism Class Library

ViewModelLocationProvider Methods
=================================

Include Protected Members
Include Inherited Members

The [ViewModelLocationProvider](https://msdn.microsoft.com/t:microsoft.practices.prism.mvvm.viewmodellocationprovider) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Dn736106.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Dn736106.static(en-us,PandP.50).gif "Static member")
[AutoWireViewModelChanged](https://msdn.microsoft.com/m:microsoft.practices.prism.mvvm.viewmodellocationprovider.autowireviewmodelchanged(microsoft.practices.prism.mvvm.iview))
Automatically looks up the viewmodel that corresponds to the current view, using two strategies: It first looks to see if there is a mapping registered for that view, if not it will fallback to the convention based approach.

![](https://msdn.microsoft.com/en-us/Dn736106.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Dn736106.static(en-us,PandP.50).gif "Static member")
[Register](https://msdn.microsoft.com/m:microsoft.practices.prism.mvvm.viewmodellocationprovider.register(system.string%2csystem.func%7bsystem.object%7d))
Registers the view model factory for the specified view type name.

![](https://msdn.microsoft.com/en-us/Dn736106.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Dn736106.static(en-us,PandP.50).gif "Static member")
[SetDefaultViewModelFactory](https://msdn.microsoft.com/m:microsoft.practices.prism.mvvm.viewmodellocationprovider.setdefaultviewmodelfactory(system.func%7bsystem.type%2csystem.object%7d))
Sets the default view model factory.

![](https://msdn.microsoft.com/en-us/Dn736106.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Dn736106.static(en-us,PandP.50).gif "Static member")
[SetDefaultViewTypeToViewModelTypeResolver](https://msdn.microsoft.com/m:microsoft.practices.prism.mvvm.viewmodellocationprovider.setdefaultviewtypetoviewmodeltyperesolver(system.func%7bsystem.type%2csystem.type%7d))
Sets the default view type to view model type resolver.

See Also
--------

<span id="seeAlsoToggle"></span>
[ViewModelLocationProvider Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mvvm.viewmodellocationprovider)

[Microsoft.Practices.Prism.Mvvm Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mvvm)
