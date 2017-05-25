---
TOCTitle: 'Microsoft.Practices.Prism.Regions Namespace'
Title: 'Microsoft.Practices.Prism.Regions Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Regions'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419044(v=PandP.50)'
---

Prism Class Library

Microsoft.Practices.Prism.Regions Namespace
===========================================

 

Classes
-------

<span id="classToggle"></span>
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
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.allactiveregion">AllActiveRegion</a></td>
<td><div class="summary">
Region that keeps all the views in it as active. Deactivation of views is not allowed.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.contentcontrolregionadapter">ContentControlRegionAdapter</a></td>
<td><div class="summary">
Adapter that creates a new <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.singleactiveregion">SingleActiveRegion</a> and monitors its active view to set it on the adapted <a href="http://msdn.microsoft.com/en-us/library/ms609797">ContentControl</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.itemmetadata">ItemMetadata</a></td>
<td><div class="summary">
Defines a class that wraps an item and adds metadata for it.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.itemscontrolregionadapter">ItemsControlRegionAdapter</a></td>
<td><div class="summary">
Adapter that creates a new <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.allactiveregion">AllActiveRegion</a> and binds all the views to the adapted <a href="http://msdn.microsoft.com/en-us/library/ms611045">ItemsControl</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a></td>
<td><div class="summary">
Provides additional methods to the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync">INavigateAsync</a> interface.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationcontext">NavigationContext</a></td>
<td><div class="summary">
Encapsulates information about a navigation request.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationparameters">NavigationParameters</a></td>
<td><div class="summary">
Represents Navigation parameters.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationresult">NavigationResult</a></td>
<td><div class="summary">
Represents the result of navigating to a URI.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region">Region</a></td>
<td><div class="summary">
Implementation of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion">IRegion</a> that allows multiple active views.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionadapterbase%601">RegionAdapterBase&lt;(Of &lt;(T&gt;)&gt;)</a></td>
<td><div class="summary">
Base class to facilitate the creation of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionadapter">IRegionAdapter</a> implementations.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionadaptermappings">RegionAdapterMappings</a></td>
<td><div class="summary">
This class maps <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> with <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionadapter">IRegionAdapter</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionbehavior">RegionBehavior</a></td>
<td><div class="summary">
Provides a base class for region's behaviors.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionbehaviorcollection">RegionBehaviorCollection</a></td>
<td><div class="summary">
A collection of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior">IRegionBehavior</a> instances, that are stored and retrieved by Key.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionbehaviorfactory">RegionBehaviorFactory</a></td>
<td><div class="summary">
Defines a factory that allows the registration of the default set of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior">IRegionBehavior</a>, that will be added to the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorcollection">IRegionBehaviorCollection</a> of all <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion">IRegion</a>s, unless overridden on a 'per-region' basis.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regioncontext">RegionContext</a></td>
<td><div class="summary">
Class that holds methods to Set and Get the RegionContext from a DependencyObject. RegionContext allows sharing of contextual information between the view that's hosting a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion">IRegion</a> and any views that are inside the Region.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanager">RegionManager</a></td>
<td><div class="summary">
This class is responsible for maintaining a collection of regions and attaching regions to controls.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a></td>
<td><div class="summary">
Class that creates a fluent interface for the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager">IRegionManager</a> class, with respect to adding views to regions (View Injection pattern), registering view types to regions (View Discovery pattern)
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmemberlifetimeattribute">RegionMemberLifetimeAttribute</a></td>
<td><div class="summary">
When <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmemberlifetimeattribute">RegionMemberLifetimeAttribute</a> is applied to class provides data the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.regionmemberlifetimebehavior">RegionMemberLifetimeBehavior</a> can use to determine if the instance should be removed when it is deactivated.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionnavigationcontentloader">RegionNavigationContentLoader</a></td>
<td><div class="summary">
Implementation of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationcontentloader">IRegionNavigationContentLoader</a> that relies on a IServiceLocator to create new views when necessary.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionnavigationeventargs">RegionNavigationEventArgs</a></td>
<td><div class="summary">
EventArgs used with the Navigated event.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionnavigationfailedeventargs">RegionNavigationFailedEventArgs</a></td>
<td><div class="summary">
EventArgs used with the NavigationFailed event.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionnavigationjournal">RegionNavigationJournal</a></td>
<td><div class="summary">
Provides journaling of current, back, and forward navigation within regions.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionnavigationjournalentry">RegionNavigationJournalEntry</a></td>
<td><div class="summary">
An entry in an IRegionNavigationJournal representing the URI navigated to.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionnavigationservice">RegionNavigationService</a></td>
<td><div class="summary">
Provides navigation for regions.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionviewregistry">RegionViewRegistry</a></td>
<td><div class="summary">
Defines a registry for the content of the regions used on View Discovery composition.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.selectorregionadapter">SelectorRegionAdapter</a></td>
<td><div class="summary">
Adapter that creates a new <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region">Region</a> and binds all the views to the adapted <a href="http://msdn.microsoft.com/en-us/library/ms595227">Selector</a>. It also keeps the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.activeviews">ActiveViews</a> and the selected items of the <a href="http://msdn.microsoft.com/en-us/library/ms595227">Selector</a> in sync.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.singleactiveregion">SingleActiveRegion</a></td>
<td><div class="summary">
Region that allows a maximum of one active view at a time.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.syncactivestateattribute">SyncActiveStateAttribute</a></td>
<td><div class="summary">
Defines that a view is synchronized with its parent view's Active state.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.updateregionsexception">UpdateRegionsException</a></td>
<td><div class="summary">
Represents errors that occured during the regions' update.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.viewregisteredeventargs">ViewRegisteredEventArgs</a></td>
<td><div class="summary">
Argument class used by the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionviewregistry.contentregistered">ContentRegistered</a> event when a new content is registered.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.viewregistrationexception">ViewRegistrationException</a></td>
<td><div class="summary">
Exception that's thrown when something goes wrong while Registering a View with a region name in the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionviewregistry">RegionViewRegistry</a> class.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.viewscollection">ViewsCollection</a></td>
<td><div class="summary">
Implementation of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iviewscollection">IViewsCollection</a> that takes an <a href="http://msdn.microsoft.com/en-us/library/ms668604">ObservableCollection&lt;(Of &lt;(T&gt;)&gt;)</a> of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.itemmetadata">ItemMetadata</a> and filters it to display an <a href="http://msdn.microsoft.com/en-us/library/ms668629">INotifyCollectionChanged</a> collection of <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> elements (the items which the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.itemmetadata">ItemMetadata</a> wraps).
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.viewsorthintattribute">ViewSortHintAttribute</a></td>
<td><div class="summary">
Provides a hint from a view to a region on how to sort the view.
</div></td>
</tr>
</tbody>
</table>

Interfaces
----------

<span id="interfaceToggle"></span>
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
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iconfirmnavigationrequest">IConfirmNavigationRequest</a></td>
<td><div class="summary">
Provides a way for objects involved in navigation to determine if a navigation request should continue.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync">INavigateAsync</a></td>
<td><div class="summary">
Provides methods to perform navigation.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigationaware">INavigationAware</a></td>
<td><div class="summary">
Provides a way for objects involved in navigation to be notified of navigation activities.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion">IRegion</a></td>
<td><div class="summary">
Defines a model that can be used to compose views.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionadapter">IRegionAdapter</a></td>
<td><div class="summary">
Defines an interfaces to adapt an object and bind it to a new <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion">IRegion</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior">IRegionBehavior</a></td>
<td><div class="summary">
Interface for allowing extensible behavior on regions.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorcollection">IRegionBehaviorCollection</a></td>
<td><div class="summary">
Defines the interface for a collection of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior">IRegionBehavior</a> classes on a Region.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorfactory">IRegionBehaviorFactory</a></td>
<td><div class="summary">
Interface for RegionBehaviorFactories. This factory allows the registration of the default set of RegionBehaviors, that will be added to the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorcollection">IRegionBehaviorCollection</a>s of all <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion">IRegion</a>s, unless overridden on a 'per-region' basis.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregioncollection">IRegionCollection</a></td>
<td><div class="summary">
Defines a collection of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion">IRegion</a> uniquely identified by their Name.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager">IRegionManager</a></td>
<td><div class="summary">
Defines an interface to manage a set of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion">regions</a> and to attach regions to objects (typically controls).
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanageraccessor">IRegionManagerAccessor</a></td>
<td><div class="summary">
Provides an abstraction on top of the RegionManager static members.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmemberlifetime">IRegionMemberLifetime</a></td>
<td><div class="summary">
When implemented, allows an instance placed in a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion">IRegion</a> that uses a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.regionmemberlifetimebehavior">RegionMemberLifetimeBehavior</a> to indicate it should be removed when it transitions from an activated to deactived state.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationcontentloader">IRegionNavigationContentLoader</a></td>
<td><div class="summary">
Identifies the view in a region that is the target of a navigation request.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationjournal">IRegionNavigationJournal</a></td>
<td><div class="summary">
Provides journaling of current, back, and forward navigation within regions.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationjournalentry">IRegionNavigationJournalEntry</a></td>
<td><div class="summary">
An entry in an IRegionNavigationJournal representing the URI navigated to.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationservice">IRegionNavigationService</a></td>
<td><div class="summary">
Provides navigation for regions.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionviewregistry">IRegionViewRegistry</a></td>
<td><div class="summary">
Defines the interface for the registry of region's content.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iviewscollection">IViewsCollection</a></td>
<td><div class="summary">
Defines a view of a collection.
</div></td>
</tr>
</tbody>
</table>
