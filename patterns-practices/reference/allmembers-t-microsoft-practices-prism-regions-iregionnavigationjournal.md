---
TOCTitle: IRegionNavigationJournal Members
Title: 'IRegionNavigationJournal Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegionNavigationJournal'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405482(v=PandP.50)'
---

Prism Class Library

IRegionNavigationJournal Members
================================

Include Protected Members
Include Inherited Members

The [IRegionNavigationJournal](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionnavigationjournal) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg405482.pubmethod(en-us,PandP.50).gif "Public method")
[Clear](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregionnavigationjournal.clear)
Clears the journal of current, back, and forward navigation histories.

![](https://msdn.microsoft.com/en-us/Gg405482.pubmethod(en-us,PandP.50).gif "Public method")
[GoBack](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregionnavigationjournal.goback)
Navigates to the most recent entry in the back navigation history, or does nothing if no entry exists in back navigation.

![](https://msdn.microsoft.com/en-us/Gg405482.pubmethod(en-us,PandP.50).gif "Public method")
[GoForward](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregionnavigationjournal.goforward)
Navigates to the most recent entry in the forward navigation history, or does nothing if no entry exists in forward navigation.

![](https://msdn.microsoft.com/en-us/Gg405482.pubmethod(en-us,PandP.50).gif "Public method")
[RecordNavigation](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregionnavigationjournal.recordnavigation(microsoft.practices.prism.regions.iregionnavigationjournalentry))
Records the navigation to the entry..

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg405482.pubproperty(en-us,PandP.50).gif "Public property")
[CanGoBack](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregionnavigationjournal.cangoback)
Gets a value that indicates whether there is at least one entry in the back navigation history.

![](https://msdn.microsoft.com/en-us/Gg405482.pubproperty(en-us,PandP.50).gif "Public property")
[CanGoForward](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregionnavigationjournal.cangoforward)
Gets a value that indicates whether there is at least one entry in the forward navigation history.

![](https://msdn.microsoft.com/en-us/Gg405482.pubproperty(en-us,PandP.50).gif "Public property")
[CurrentEntry](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregionnavigationjournal.currententry)
Gets the current navigation entry of the content that is currently displayed.

![](https://msdn.microsoft.com/en-us/Gg405482.pubproperty(en-us,PandP.50).gif "Public property")
[NavigationTarget](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregionnavigationjournal.navigationtarget)
Gets or sets the target that implements INavigateAsync.

See Also
--------

<span id="seeAlsoToggle"></span>
[IRegionNavigationJournal Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionnavigationjournal)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
