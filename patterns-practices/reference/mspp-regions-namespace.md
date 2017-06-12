---
TOCTitle: 'Microsoft.Practices.Prism.Regions Namespace'
Title: 'Microsoft.Practices.Prism.Regions Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Regions'
ms:mtpsurl: 'mspp-regions-namespace.md'
---


# Microsoft.Practices.Prism.Regions Namespace

 

## Classes


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
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[AllActiveRegion](/patterns-practices/reference/allactiveregion-class-mspp-regions)</td>
<td><div class="summary">
Region that keeps all the views in it as active. Deactivation of views is not allowed.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ContentControlRegionAdapter](/patterns-practices/reference/contentcontrolregionadapter-class-mspp-regions)</td>
<td><div class="summary">
Adapter that creates a new [SingleActiveRegion](/patterns-practices/reference/singleactiveregion-class-mspp-regions) and monitors its active view to set it on the adapted [ContentControl](http://msdn.microsoft.com/en-us/library/ms609797).
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions)</td>
<td><div class="summary">
Defines a class that wraps an item and adds metadata for it.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ItemsControlRegionAdapter](/patterns-practices/reference/itemscontrolregionadapter-class-mspp-regions)</td>
<td><div class="summary">
Adapter that creates a new [AllActiveRegion](/patterns-practices/reference/allactiveregion-class-mspp-regions) and binds all the views to the adapted [ItemsControl](http://msdn.microsoft.com/en-us/library/ms611045).
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions)</td>
<td><div class="summary">
Provides additional methods to the [INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions) interface.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[NavigationContext](/patterns-practices/reference/navigationcontext-class-mspp-regions)</td>
<td><div class="summary">
Encapsulates information about a navigation request.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[NavigationParameters](/patterns-practices/reference/navigationparameters-class-mspp-regions)</td>
<td><div class="summary">
Represents Navigation parameters.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[NavigationResult](/patterns-practices/reference/navigationresult-class-mspp-regions)</td>
<td><div class="summary">
Represents the result of navigating to a URI.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[Region](/patterns-practices/reference/region-class-mspp-regions)</td>
<td><div class="summary">
Implementation of [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) that allows multiple active views.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionAdapterBase&lt;T&gt;](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)</td>
<td><div class="summary">
Base class to facilitate the creation of [IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions) implementations.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionAdapterMappings](/patterns-practices/reference/regionadaptermappings-class-mspp-regions)</td>
<td><div class="summary">
This class maps [Type](http://msdn.microsoft.com/en-us/library/42892f65) with [IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions).
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionBehavior](/patterns-practices/reference/regionbehavior-class-mspp-regions)</td>
<td><div class="summary">
Provides a base class for region's behaviors.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionBehaviorCollection](/patterns-practices/reference/regionbehaviorcollection-class-mspp-regions)</td>
<td><div class="summary">
A collection of [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) instances, that are stored and retrieved by Key.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionBehaviorFactory](/patterns-practices/reference/regionbehaviorfactory-class-mspp-regions)</td>
<td><div class="summary">
Defines a factory that allows the registration of the default set of [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions), that will be added to the [IRegionBehaviorCollection](/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions) of all [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)s, unless overridden on a 'per-region' basis.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionContext](/patterns-practices/reference/regioncontext-class-mspp-regions)</td>
<td><div class="summary">
Class that holds methods to Set and Get the RegionContext from a DependencyObject. RegionContext allows sharing of contextual information between the view that's hosting a [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) and any views that are inside the Region.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions)</td>
<td><div class="summary">
This class is responsible for maintaining a collection of regions and attaching regions to controls.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)</td>
<td><div class="summary">
Class that creates a fluent interface for the [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) class, with respect to adding views to regions (View Injection pattern), registering view types to regions (View Discovery pattern)
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionMemberLifetimeAttribute](/patterns-practices/reference/regionmemberlifetimeattribute-class-mspp-regions)</td>
<td><div class="summary">
When [RegionMemberLifetimeAttribute](/patterns-practices/reference/regionmemberlifetimeattribute-class-mspp-regions) is applied to class provides data the [RegionMemberLifetimeBehavior](/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors) can use to determine if the instance should be removed when it is deactivated.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionNavigationContentLoader](/patterns-practices/reference/regionnavigationcontentloader-class-mspp-regions)</td>
<td><div class="summary">
Implementation of [IRegionNavigationContentLoader](/patterns-practices/reference/iregionnavigationcontentloader-interface-mspp-regions) that relies on a IServiceLocator to create new views when necessary.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionNavigationEventArgs](/patterns-practices/reference/regionnavigationeventargs-class-mspp-regions)</td>
<td><div class="summary">
EventArgs used with the Navigated event.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionNavigationFailedEventArgs](/patterns-practices/reference/regionnavigationfailedeventargs-class-mspp-regions)</td>
<td><div class="summary">
EventArgs used with the NavigationFailed event.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionNavigationJournal](/patterns-practices/reference/regionnavigationjournal-class-mspp-regions)</td>
<td><div class="summary">
Provides journaling of current, back, and forward navigation within regions.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionNavigationJournalEntry](/patterns-practices/reference/regionnavigationjournalentry-class-mspp-regions)</td>
<td><div class="summary">
An entry in an IRegionNavigationJournal representing the URI navigated to.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionNavigationService](/patterns-practices/reference/regionnavigationservice-class-mspp-regions)</td>
<td><div class="summary">
Provides navigation for regions.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionViewRegistry](/patterns-practices/reference/regionviewregistry-class-mspp-regions)</td>
<td><div class="summary">
Defines a registry for the content of the regions used on View Discovery composition.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[SelectorRegionAdapter](/patterns-practices/reference/selectorregionadapter-class-mspp-regions)</td>
<td><div class="summary">
Adapter that creates a new [Region](/patterns-practices/reference/region-class-mspp-regions) and binds all the views to the adapted [Selector](http://msdn.microsoft.com/en-us/library/ms595227). It also keeps the [ActiveViews](/patterns-practices/reference/iregion-activeviews-property-mspp-regions) and the selected items of the [Selector](http://msdn.microsoft.com/en-us/library/ms595227) in sync.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[SingleActiveRegion](/patterns-practices/reference/singleactiveregion-class-mspp-regions)</td>
<td><div class="summary">
Region that allows a maximum of one active view at a time.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[SyncActiveStateAttribute](/patterns-practices/reference/syncactivestateattribute-class-mspp-regions)</td>
<td><div class="summary">
Defines that a view is synchronized with its parent view's Active state.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[UpdateRegionsException](/patterns-practices/reference/updateregionsexception-class-mspp-regions)</td>
<td><div class="summary">
Represents errors that occured during the regions' update.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ViewRegisteredEventArgs](/patterns-practices/reference/viewregisteredeventargs-class-mspp-regions)</td>
<td><div class="summary">
Argument class used by the [ContentRegistered](/patterns-practices/reference/iregionviewregistry-contentregistered-event-mspp-regions) event when a new content is registered.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ViewRegistrationException](/patterns-practices/reference/viewregistrationexception-class-mspp-regions)</td>
<td><div class="summary">
Exception that's thrown when something goes wrong while Registering a View with a region name in the [RegionViewRegistry](/patterns-practices/reference/regionviewregistry-class-mspp-regions) class.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ViewsCollection](/patterns-practices/reference/viewscollection-class-mspp-regions)</td>
<td><div class="summary">
Implementation of [IViewsCollection](/patterns-practices/reference/iviewscollection-interface-mspp-regions) that takes an [ObservableCollection&lt;T&gt;](http://msdn.microsoft.com/en-us/library/ms668604) of [ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions) and filters it to display an [INotifyCollectionChanged](http://msdn.microsoft.com/en-us/library/ms668629) collection of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) elements (the items which the [ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions) wraps).
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ViewSortHintAttribute](/patterns-practices/reference/viewsorthintattribute-class-mspp-regions)</td>
<td><div class="summary">
Provides a hint from a view to a region on how to sort the view.
</div></td>
</tr>
</tbody>
</table>

## Interfaces


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
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IConfirmNavigationRequest](/patterns-practices/reference/iconfirmnavigationrequest-interface-mspp-regions)</td>
<td><div class="summary">
Provides a way for objects involved in navigation to determine if a navigation request should continue.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions)</td>
<td><div class="summary">
Provides methods to perform navigation.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[INavigationAware](/patterns-practices/reference/inavigationaware-interface-mspp-regions)</td>
<td><div class="summary">
Provides a way for objects involved in navigation to be notified of navigation activities.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)</td>
<td><div class="summary">
Defines a model that can be used to compose views.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions)</td>
<td><div class="summary">
Defines an interfaces to adapt an object and bind it to a new [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions).
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)</td>
<td><div class="summary">
Interface for allowing extensible behavior on regions.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionBehaviorCollection](/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions)</td>
<td><div class="summary">
Defines the interface for a collection of [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) classes on a Region.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionBehaviorFactory](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions)</td>
<td><div class="summary">
Interface for RegionBehaviorFactories. This factory allows the registration of the default set of RegionBehaviors, that will be added to the [IRegionBehaviorCollection](/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions)s of all [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)s, unless overridden on a 'per-region' basis.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionCollection](/patterns-practices/reference/iregioncollection-interface-mspp-regions)</td>
<td><div class="summary">
Defines a collection of [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) uniquely identified by their Name.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)</td>
<td><div class="summary">
Defines an interface to manage a set of [regions](/patterns-practices/reference/iregion-interface-mspp-regions) and to attach regions to objects (typically controls).
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionManagerAccessor](/patterns-practices/reference/iregionmanageraccessor-interface-mspp-regions)</td>
<td><div class="summary">
Provides an abstraction on top of the RegionManager static members.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionMemberLifetime](/patterns-practices/reference/iregionmemberlifetime-interface-mspp-regions)</td>
<td><div class="summary">
When implemented, allows an instance placed in a [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) that uses a [RegionMemberLifetimeBehavior](/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors) to indicate it should be removed when it transitions from an activated to deactived state.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionNavigationContentLoader](/patterns-practices/reference/iregionnavigationcontentloader-interface-mspp-regions)</td>
<td><div class="summary">
Identifies the view in a region that is the target of a navigation request.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionNavigationJournal](/patterns-practices/reference/iregionnavigationjournal-interface-mspp-regions)</td>
<td><div class="summary">
Provides journaling of current, back, and forward navigation within regions.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionNavigationJournalEntry](/patterns-practices/reference/iregionnavigationjournalentry-interface-mspp-regions)</td>
<td><div class="summary">
An entry in an IRegionNavigationJournal representing the URI navigated to.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionNavigationService](/patterns-practices/reference/iregionnavigationservice-interface-mspp-regions)</td>
<td><div class="summary">
Provides navigation for regions.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IRegionViewRegistry](/patterns-practices/reference/iregionviewregistry-interface-mspp-regions)</td>
<td><div class="summary">
Defines the interface for the registry of region's content.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IViewsCollection](/patterns-practices/reference/iviewscollection-interface-mspp-regions)</td>
<td><div class="summary">
Defines a view of a collection.
</div></td>
</tr>
</tbody>
</table>