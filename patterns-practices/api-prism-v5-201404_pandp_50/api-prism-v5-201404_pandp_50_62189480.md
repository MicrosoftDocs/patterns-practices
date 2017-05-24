---
TOCTitle: IRegion Methods
Title: 'IRegion Methods (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.IRegion'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431084(v=PandP.50)'
---

Prism Class Library

IRegion Methods
===============

Include Protected Members
Include Inherited Members

The [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif "Public method")
[Activate](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.activate(system.object))
Marks the specified view as active.

![](https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif "Public method")
[Add(Object)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.add(system.object))
Adds a new view to the region.

![](https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif "Public method")
[Add(Object, String)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.add(system.object%2csystem.string))
Adds a new view to the region.

![](https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif "Public method")
[Add(Object, String, Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.add(system.object%2csystem.string%2csystem.boolean))
Adds a new view to the region.

![](https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif "Public method")
[Deactivate](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.deactivate(system.object))
Marks the specified view as inactive.

![](https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif "Public method")
[GetView](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.getview(system.string))
Returns the view instance that was added to the region using a specific name.

![](https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif "Public method")
[Remove](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.remove(system.object))
Removes the specified view from the region.

![](https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif "Public method")
[RequestNavigate(Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.inavigateasync.requestnavigate(system.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d))
Initiates navigation to the target specified by the [Uri](http://msdn2.microsoft.com/en-us/library/txt7706a).

(Inherited from [INavigateAsync](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.inavigateasync).)
![](https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif "Public method")
[RequestNavigate(Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.inavigateasync.requestnavigate(system.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters))
Initiates navigation to the target specified by the [Uri](http://msdn2.microsoft.com/en-us/library/txt7706a).

(Inherited from [INavigateAsync](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.inavigateasync).)

Extension Methods
-----------------

<span id="extensionMethodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg431084.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string))
Overloaded.
Initiates navigation to the target specified by the target.

(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions).)
![](https://msdn.microsoft.com/en-us/Gg431084.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(Uri)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.uri))
Overloaded.
Initiates navigation to the target specified by the [Uri](http://msdn2.microsoft.com/en-us/library/txt7706a).

(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions).)
![](https://msdn.microsoft.com/en-us/Gg431084.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d))
Overloaded.
Initiates navigation to the target specified by the target.

(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions).)
![](https://msdn.microsoft.com/en-us/Gg431084.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(Uri, NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.uri%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
Initiates navigation to the target specified by the target.

(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions).)
![](https://msdn.microsoft.com/en-us/Gg431084.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
Initiates navigation to the target specified by the target.

(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions).)
![](https://msdn.microsoft.com/en-us/Gg431084.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
Initiates navigation to the target specified by the target.

(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions).)

See Also
--------

<span id="seeAlsoToggle"></span>
[IRegion Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
