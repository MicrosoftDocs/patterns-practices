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
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/allactiveregion-class-mspp-regions" data-raw-source="[AllActiveRegion](/patterns-practices/reference/allactiveregion-class-mspp-regions)">AllActiveRegion</a></td>
<td><div class="summary">
Region that keeps all the views in it as active. Deactivation of views is not allowed.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/contentcontrolregionadapter-class-mspp-regions" data-raw-source="[ContentControlRegionAdapter](/patterns-practices/reference/contentcontrolregionadapter-class-mspp-regions)">ContentControlRegionAdapter</a></td>
<td><div class="summary">
Adapter that creates a new <a href="/patterns-practices/reference/singleactiveregion-class-mspp-regions" data-raw-source="[SingleActiveRegion](/patterns-practices/reference/singleactiveregion-class-mspp-regions)">SingleActiveRegion</a> and monitors its active view to set it on the adapted <a href="http://msdn.microsoft.com/en-us/library/ms609797" data-raw-source="[ContentControl](http://msdn.microsoft.com/en-us/library/ms609797)">ContentControl</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/itemmetadata-class-mspp-regions" data-raw-source="[ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions)">ItemMetadata</a></td>
<td><div class="summary">
Defines a class that wraps an item and adds metadata for it.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/itemscontrolregionadapter-class-mspp-regions" data-raw-source="[ItemsControlRegionAdapter](/patterns-practices/reference/itemscontrolregionadapter-class-mspp-regions)">ItemsControlRegionAdapter</a></td>
<td><div class="summary">
Adapter that creates a new <a href="/patterns-practices/reference/allactiveregion-class-mspp-regions" data-raw-source="[AllActiveRegion](/patterns-practices/reference/allactiveregion-class-mspp-regions)">AllActiveRegion</a> and binds all the views to the adapted <a href="http://msdn.microsoft.com/en-us/library/ms611045" data-raw-source="[ItemsControl](http://msdn.microsoft.com/en-us/library/ms611045)">ItemsControl</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions" data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions)">NavigationAsyncExtensions</a></td>
<td><div class="summary">
Provides additional methods to the <a href="/patterns-practices/reference/inavigateasync-interface-mspp-regions" data-raw-source="[INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions)">INavigateAsync</a> interface.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/navigationcontext-class-mspp-regions" data-raw-source="[NavigationContext](/patterns-practices/reference/navigationcontext-class-mspp-regions)">NavigationContext</a></td>
<td><div class="summary">
Encapsulates information about a navigation request.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/navigationparameters-class-mspp-regions" data-raw-source="[NavigationParameters](/patterns-practices/reference/navigationparameters-class-mspp-regions)">NavigationParameters</a></td>
<td><div class="summary">
Represents Navigation parameters.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/navigationresult-class-mspp-regions" data-raw-source="[NavigationResult](/patterns-practices/reference/navigationresult-class-mspp-regions)">NavigationResult</a></td>
<td><div class="summary">
Represents the result of navigating to a URI.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a></td>
<td><div class="summary">
Implementation of <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a> that allows multiple active views.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionadapterbase-t-class-mspp-regions" data-raw-source="[RegionAdapterBase&amp;lt;T&amp;gt;](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)">RegionAdapterBase&lt;T&gt;</a></td>
<td><div class="summary">
Base class to facilitate the creation of <a href="/patterns-practices/reference/iregionadapter-interface-mspp-regions" data-raw-source="[IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions)">IRegionAdapter</a> implementations.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionadaptermappings-class-mspp-regions" data-raw-source="[RegionAdapterMappings](/patterns-practices/reference/regionadaptermappings-class-mspp-regions)">RegionAdapterMappings</a></td>
<td><div class="summary">
This class maps <a href="http://msdn.microsoft.com/en-us/library/42892f65" data-raw-source="[Type](http://msdn.microsoft.com/en-us/library/42892f65)">Type</a> with <a href="/patterns-practices/reference/iregionadapter-interface-mspp-regions" data-raw-source="[IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions)">IRegionAdapter</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionbehavior-class-mspp-regions" data-raw-source="[RegionBehavior](/patterns-practices/reference/regionbehavior-class-mspp-regions)">RegionBehavior</a></td>
<td><div class="summary">
Provides a base class for region&#39;s behaviors.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionbehaviorcollection-class-mspp-regions" data-raw-source="[RegionBehaviorCollection](/patterns-practices/reference/regionbehaviorcollection-class-mspp-regions)">RegionBehaviorCollection</a></td>
<td><div class="summary">
A collection of <a href="/patterns-practices/reference/iregionbehavior-interface-mspp-regions" data-raw-source="[IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)">IRegionBehavior</a> instances, that are stored and retrieved by Key.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionbehaviorfactory-class-mspp-regions" data-raw-source="[RegionBehaviorFactory](/patterns-practices/reference/regionbehaviorfactory-class-mspp-regions)">RegionBehaviorFactory</a></td>
<td><div class="summary">
Defines a factory that allows the registration of the default set of <a href="/patterns-practices/reference/iregionbehavior-interface-mspp-regions" data-raw-source="[IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)">IRegionBehavior</a>, that will be added to the <a href="/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions" data-raw-source="[IRegionBehaviorCollection](/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions)">IRegionBehaviorCollection</a> of all <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a>s, unless overridden on a &#39;per-region&#39; basis.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regioncontext-class-mspp-regions" data-raw-source="[RegionContext](/patterns-practices/reference/regioncontext-class-mspp-regions)">RegionContext</a></td>
<td><div class="summary">
Class that holds methods to Set and Get the RegionContext from a DependencyObject. RegionContext allows sharing of contextual information between the view that&#39;s hosting a <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a> and any views that are inside the Region.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionmanager-class-mspp-regions" data-raw-source="[RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions)">RegionManager</a></td>
<td><div class="summary">
This class is responsible for maintaining a collection of regions and attaching regions to controls.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)">RegionManagerExtensions</a></td>
<td><div class="summary">
Class that creates a fluent interface for the <a href="/patterns-practices/reference/iregionmanager-interface-mspp-regions" data-raw-source="[IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)">IRegionManager</a> class, with respect to adding views to regions (View Injection pattern), registering view types to regions (View Discovery pattern)
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionmemberlifetimeattribute-class-mspp-regions" data-raw-source="[RegionMemberLifetimeAttribute](/patterns-practices/reference/regionmemberlifetimeattribute-class-mspp-regions)">RegionMemberLifetimeAttribute</a></td>
<td><div class="summary">
When <a href="/patterns-practices/reference/regionmemberlifetimeattribute-class-mspp-regions" data-raw-source="[RegionMemberLifetimeAttribute](/patterns-practices/reference/regionmemberlifetimeattribute-class-mspp-regions)">RegionMemberLifetimeAttribute</a> is applied to class provides data the <a href="/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors" data-raw-source="[RegionMemberLifetimeBehavior](/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors)">RegionMemberLifetimeBehavior</a> can use to determine if the instance should be removed when it is deactivated.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionnavigationcontentloader-class-mspp-regions" data-raw-source="[RegionNavigationContentLoader](/patterns-practices/reference/regionnavigationcontentloader-class-mspp-regions)">RegionNavigationContentLoader</a></td>
<td><div class="summary">
Implementation of <a href="/patterns-practices/reference/iregionnavigationcontentloader-interface-mspp-regions" data-raw-source="[IRegionNavigationContentLoader](/patterns-practices/reference/iregionnavigationcontentloader-interface-mspp-regions)">IRegionNavigationContentLoader</a> that relies on a IServiceLocator to create new views when necessary.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionnavigationeventargs-class-mspp-regions" data-raw-source="[RegionNavigationEventArgs](/patterns-practices/reference/regionnavigationeventargs-class-mspp-regions)">RegionNavigationEventArgs</a></td>
<td><div class="summary">
EventArgs used with the Navigated event.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionnavigationfailedeventargs-class-mspp-regions" data-raw-source="[RegionNavigationFailedEventArgs](/patterns-practices/reference/regionnavigationfailedeventargs-class-mspp-regions)">RegionNavigationFailedEventArgs</a></td>
<td><div class="summary">
EventArgs used with the NavigationFailed event.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionnavigationjournal-class-mspp-regions" data-raw-source="[RegionNavigationJournal](/patterns-practices/reference/regionnavigationjournal-class-mspp-regions)">RegionNavigationJournal</a></td>
<td><div class="summary">
Provides journaling of current, back, and forward navigation within regions.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionnavigationjournalentry-class-mspp-regions" data-raw-source="[RegionNavigationJournalEntry](/patterns-practices/reference/regionnavigationjournalentry-class-mspp-regions)">RegionNavigationJournalEntry</a></td>
<td><div class="summary">
An entry in an IRegionNavigationJournal representing the URI navigated to.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionnavigationservice-class-mspp-regions" data-raw-source="[RegionNavigationService](/patterns-practices/reference/regionnavigationservice-class-mspp-regions)">RegionNavigationService</a></td>
<td><div class="summary">
Provides navigation for regions.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionviewregistry-class-mspp-regions" data-raw-source="[RegionViewRegistry](/patterns-practices/reference/regionviewregistry-class-mspp-regions)">RegionViewRegistry</a></td>
<td><div class="summary">
Defines a registry for the content of the regions used on View Discovery composition.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/selectorregionadapter-class-mspp-regions" data-raw-source="[SelectorRegionAdapter](/patterns-practices/reference/selectorregionadapter-class-mspp-regions)">SelectorRegionAdapter</a></td>
<td><div class="summary">
Adapter that creates a new <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a> and binds all the views to the adapted <a href="http://msdn.microsoft.com/en-us/library/ms595227" data-raw-source="[Selector](http://msdn.microsoft.com/en-us/library/ms595227)">Selector</a>. It also keeps the <a href="/patterns-practices/reference/iregion-activeviews-property-mspp-regions" data-raw-source="[ActiveViews](/patterns-practices/reference/iregion-activeviews-property-mspp-regions)">ActiveViews</a> and the selected items of the <a href="http://msdn.microsoft.com/en-us/library/ms595227" data-raw-source="[Selector](http://msdn.microsoft.com/en-us/library/ms595227)">Selector</a> in sync.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/singleactiveregion-class-mspp-regions" data-raw-source="[SingleActiveRegion](/patterns-practices/reference/singleactiveregion-class-mspp-regions)">SingleActiveRegion</a></td>
<td><div class="summary">
Region that allows a maximum of one active view at a time.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/syncactivestateattribute-class-mspp-regions" data-raw-source="[SyncActiveStateAttribute](/patterns-practices/reference/syncactivestateattribute-class-mspp-regions)">SyncActiveStateAttribute</a></td>
<td><div class="summary">
Defines that a view is synchronized with its parent view&#39;s Active state.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/updateregionsexception-class-mspp-regions" data-raw-source="[UpdateRegionsException](/patterns-practices/reference/updateregionsexception-class-mspp-regions)">UpdateRegionsException</a></td>
<td><div class="summary">
Represents errors that occured during the regions&#39; update.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/viewregisteredeventargs-class-mspp-regions" data-raw-source="[ViewRegisteredEventArgs](/patterns-practices/reference/viewregisteredeventargs-class-mspp-regions)">ViewRegisteredEventArgs</a></td>
<td><div class="summary">
Argument class used by the <a href="/patterns-practices/reference/iregionviewregistry-contentregistered-event-mspp-regions" data-raw-source="[ContentRegistered](/patterns-practices/reference/iregionviewregistry-contentregistered-event-mspp-regions)">ContentRegistered</a> event when a new content is registered.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/viewregistrationexception-class-mspp-regions" data-raw-source="[ViewRegistrationException](/patterns-practices/reference/viewregistrationexception-class-mspp-regions)">ViewRegistrationException</a></td>
<td><div class="summary">
Exception that&#39;s thrown when something goes wrong while Registering a View with a region name in the <a href="/patterns-practices/reference/regionviewregistry-class-mspp-regions" data-raw-source="[RegionViewRegistry](/patterns-practices/reference/regionviewregistry-class-mspp-regions)">RegionViewRegistry</a> class.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/viewscollection-class-mspp-regions" data-raw-source="[ViewsCollection](/patterns-practices/reference/viewscollection-class-mspp-regions)">ViewsCollection</a></td>
<td><div class="summary">
Implementation of <a href="/patterns-practices/reference/iviewscollection-interface-mspp-regions" data-raw-source="[IViewsCollection](/patterns-practices/reference/iviewscollection-interface-mspp-regions)">IViewsCollection</a> that takes an <a href="http://msdn.microsoft.com/en-us/library/ms668604" data-raw-source="[ObservableCollection&amp;lt;T&amp;gt;](http://msdn.microsoft.com/en-us/library/ms668604)">ObservableCollection&lt;T&gt;</a> of <a href="/patterns-practices/reference/itemmetadata-class-mspp-regions" data-raw-source="[ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions)">ItemMetadata</a> and filters it to display an <a href="http://msdn.microsoft.com/en-us/library/ms668629" data-raw-source="[INotifyCollectionChanged](http://msdn.microsoft.com/en-us/library/ms668629)">INotifyCollectionChanged</a> collection of <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a> elements (the items which the <a href="/patterns-practices/reference/itemmetadata-class-mspp-regions" data-raw-source="[ItemMetadata](/patterns-practices/reference/itemmetadata-class-mspp-regions)">ItemMetadata</a> wraps).
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/viewsorthintattribute-class-mspp-regions" data-raw-source="[ViewSortHintAttribute](/patterns-practices/reference/viewsorthintattribute-class-mspp-regions)">ViewSortHintAttribute</a></td>
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
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iconfirmnavigationrequest-interface-mspp-regions" data-raw-source="[IConfirmNavigationRequest](/patterns-practices/reference/iconfirmnavigationrequest-interface-mspp-regions)">IConfirmNavigationRequest</a></td>
<td><div class="summary">
Provides a way for objects involved in navigation to determine if a navigation request should continue.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/inavigateasync-interface-mspp-regions" data-raw-source="[INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions)">INavigateAsync</a></td>
<td><div class="summary">
Provides methods to perform navigation.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/inavigationaware-interface-mspp-regions" data-raw-source="[INavigationAware](/patterns-practices/reference/inavigationaware-interface-mspp-regions)">INavigationAware</a></td>
<td><div class="summary">
Provides a way for objects involved in navigation to be notified of navigation activities.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a></td>
<td><div class="summary">
Defines a model that can be used to compose views.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregionadapter-interface-mspp-regions" data-raw-source="[IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions)">IRegionAdapter</a></td>
<td><div class="summary">
Defines an interfaces to adapt an object and bind it to a new <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregionbehavior-interface-mspp-regions" data-raw-source="[IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)">IRegionBehavior</a></td>
<td><div class="summary">
Interface for allowing extensible behavior on regions.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions" data-raw-source="[IRegionBehaviorCollection](/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions)">IRegionBehaviorCollection</a></td>
<td><div class="summary">
Defines the interface for a collection of <a href="/patterns-practices/reference/iregionbehavior-interface-mspp-regions" data-raw-source="[IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)">IRegionBehavior</a> classes on a Region.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions" data-raw-source="[IRegionBehaviorFactory](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions)">IRegionBehaviorFactory</a></td>
<td><div class="summary">
Interface for RegionBehaviorFactories. This factory allows the registration of the default set of RegionBehaviors, that will be added to the <a href="/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions" data-raw-source="[IRegionBehaviorCollection](/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions)">IRegionBehaviorCollection</a>s of all <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a>s, unless overridden on a &#39;per-region&#39; basis.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregioncollection-interface-mspp-regions" data-raw-source="[IRegionCollection](/patterns-practices/reference/iregioncollection-interface-mspp-regions)">IRegionCollection</a></td>
<td><div class="summary">
Defines a collection of <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a> uniquely identified by their Name.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregionmanager-interface-mspp-regions" data-raw-source="[IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)">IRegionManager</a></td>
<td><div class="summary">
Defines an interface to manage a set of <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[regions](/patterns-practices/reference/iregion-interface-mspp-regions)">regions</a> and to attach regions to objects (typically controls).
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregionmanageraccessor-interface-mspp-regions" data-raw-source="[IRegionManagerAccessor](/patterns-practices/reference/iregionmanageraccessor-interface-mspp-regions)">IRegionManagerAccessor</a></td>
<td><div class="summary">
Provides an abstraction on top of the RegionManager static members.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregionmemberlifetime-interface-mspp-regions" data-raw-source="[IRegionMemberLifetime](/patterns-practices/reference/iregionmemberlifetime-interface-mspp-regions)">IRegionMemberLifetime</a></td>
<td><div class="summary">
When implemented, allows an instance placed in a <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a> that uses a <a href="/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors" data-raw-source="[RegionMemberLifetimeBehavior](/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors)">RegionMemberLifetimeBehavior</a> to indicate it should be removed when it transitions from an activated to deactived state.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregionnavigationcontentloader-interface-mspp-regions" data-raw-source="[IRegionNavigationContentLoader](/patterns-practices/reference/iregionnavigationcontentloader-interface-mspp-regions)">IRegionNavigationContentLoader</a></td>
<td><div class="summary">
Identifies the view in a region that is the target of a navigation request.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregionnavigationjournal-interface-mspp-regions" data-raw-source="[IRegionNavigationJournal](/patterns-practices/reference/iregionnavigationjournal-interface-mspp-regions)">IRegionNavigationJournal</a></td>
<td><div class="summary">
Provides journaling of current, back, and forward navigation within regions.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregionnavigationjournalentry-interface-mspp-regions" data-raw-source="[IRegionNavigationJournalEntry](/patterns-practices/reference/iregionnavigationjournalentry-interface-mspp-regions)">IRegionNavigationJournalEntry</a></td>
<td><div class="summary">
An entry in an IRegionNavigationJournal representing the URI navigated to.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregionnavigationservice-interface-mspp-regions" data-raw-source="[IRegionNavigationService](/patterns-practices/reference/iregionnavigationservice-interface-mspp-regions)">IRegionNavigationService</a></td>
<td><div class="summary">
Provides navigation for regions.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iregionviewregistry-interface-mspp-regions" data-raw-source="[IRegionViewRegistry](/patterns-practices/reference/iregionviewregistry-interface-mspp-regions)">IRegionViewRegistry</a></td>
<td><div class="summary">
Defines the interface for the registry of region&#39;s content.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iviewscollection-interface-mspp-regions" data-raw-source="[IViewsCollection](/patterns-practices/reference/iviewscollection-interface-mspp-regions)">IViewsCollection</a></td>
<td><div class="summary">
Defines a view of a collection.
</div></td>
</tr>
</tbody>
</table>