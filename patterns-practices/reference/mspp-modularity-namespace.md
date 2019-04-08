---
TOCTitle: 'Microsoft.Practices.Prism.Modularity Namespace'
Title: 'Microsoft.Practices.Prism.Modularity Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Modularity'
ms:mtpsurl: 'mspp-modularity-namespace.md'
---

# Microsoft.Practices.Prism.Modularity Namespace

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
<td><a href="/patterns-practices/reference/assemblyresolver-class-mspp-modularity" data-raw-source="[AssemblyResolver](/patterns-practices/reference/assemblyresolver-class-mspp-modularity)">AssemblyResolver</a></td>
<td><div>
Handles AppDomain&#39;s AssemblyResolve event to be able to load assemblies dynamically in the LoadFrom context, but be able to reference the type from assemblies loaded in the Load context.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/configurationmodulecatalog-class-mspp-modularity" data-raw-source="[ConfigurationModuleCatalog](/patterns-practices/reference/configurationmodulecatalog-class-mspp-modularity)">ConfigurationModuleCatalog</a></td>
<td><div>
A catalog built from a configuration file.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/configurationstore-class-mspp-modularity" data-raw-source="[ConfigurationStore](/patterns-practices/reference/configurationstore-class-mspp-modularity)">ConfigurationStore</a></td>
<td><div>
Defines a store for the module metadata.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/cyclicdependencyfoundexception-class-mspp-modularity" data-raw-source="[CyclicDependencyFoundException](/patterns-practices/reference/cyclicdependencyfoundexception-class-mspp-modularity)">CyclicDependencyFoundException</a></td>
<td><div>
Represents the exception that is thrown when there is a circular dependency between modules during the module loading process.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/directorymodulecatalog-class-mspp-modularity" data-raw-source="[DirectoryModuleCatalog](/patterns-practices/reference/directorymodulecatalog-class-mspp-modularity)">DirectoryModuleCatalog</a></td>
<td><div>
Represets a catalog created from a directory on disk.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>

<td><a href="/patterns-practices/reference/duplicatemoduleexception-class-mspp-modularity" data-raw-source="[DuplicateModuleException](/patterns-practices/reference/duplicatemoduleexception-class-mspp-modularity)">DuplicateModuleException</a></td>
<td><div>
Exception thrown when a module is declared twice in the same catalog.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity" data-raw-source="[FileModuleTypeLoader](/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity)">FileModuleTypeLoader</a></td>
<td><div>
Loads modules from an arbitrary location on the filesystem. This typeloader is only called if <a href="/patterns-practices/reference/https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo" data-raw-source="[ModuleInfo](/patterns-practices/reference/https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)">ModuleInfo</a> classes have a Ref parameter that starts with &quot;file://&quot;. This class is only used on the Desktop version of the Prism Library.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/loadmodulecompletedeventargs-class-mspp-modularity" data-raw-source="[LoadModuleCompletedEventArgs](/patterns-practices/reference/loadmodulecompletedeventargs-class-mspp-modularity)">LoadModuleCompletedEventArgs</a></td>
<td><div>
Provides completion information after a module is loaded, or fails to load.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/modularityexception-class-mspp-modularity" data-raw-source="[ModularityException](/patterns-practices/reference/modularityexception-class-mspp-modularity)">ModularityException</a></td>
<td><div>
Base class for exceptions that are thrown because of a problem with modules.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduleattribute-class-mspp-modularity" data-raw-source="[ModuleAttribute](/patterns-practices/reference/moduleattribute-class-mspp-modularity)">ModuleAttribute</a></td>
<td><div>
Indicates that the class should be considered a named module using the provided module name.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a></td>
<td><div>
The <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a> holds information about the modules that can be used by the application. Each module is described in a <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a> class, that records the name, type and location of the module. It also verifies that the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a> is internally valid. That means that it does not have: Circular dependenciesMissing dependencies Invalid dependencies, such as a Module that&#39;s loaded at startup that depends on a module that might need to be retrieved. The <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a> also serves as a baseclass for more specialized Catalogs .
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduleconfigurationelement-class-mspp-modularity" data-raw-source="[ModuleConfigurationElement](/patterns-practices/reference/moduleconfigurationelement-class-mspp-modularity)">ModuleConfigurationElement</a></td>
<td><div>
A configuration element to declare module metadata.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduleconfigurationelementcollection-class-mspp-modularity" data-raw-source="[ModuleConfigurationElementCollection](/patterns-practices/reference/moduleconfigurationelementcollection-class-mspp-modularity)">ModuleConfigurationElementCollection</a></td>
<td><div>
A collection of <a href="/patterns-practices/reference/moduleconfigurationelement-class-mspp-modularity" data-raw-source="[ModuleConfigurationElement](/patterns-practices/reference/moduleconfigurationelement-class-mspp-modularity)">ModuleConfigurationElement</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduledependencyattribute-class-mspp-modularity" data-raw-source="[ModuleDependencyAttribute](/patterns-practices/reference/moduledependencyattribute-class-mspp-modularity)">ModuleDependencyAttribute</a></td>
<td><div>
Specifies that the current module has a dependency on another module. This attribute should be used on classes that implement <a href="/patterns-practices/reference/imodule-interface-mspp-modularity" data-raw-source="[IModule](/patterns-practices/reference/imodule-interface-mspp-modularity)">IModule</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduledependencycollection-class-mspp-modularity" data-raw-source="[ModuleDependencyCollection](/patterns-practices/reference/moduledependencycollection-class-mspp-modularity)">ModuleDependencyCollection</a></td>
<td><div>
A collection of <a href="/patterns-practices/reference/moduledependencyconfigurationelement-class-mspp-modularity" data-raw-source="[ModuleDependencyConfigurationElement](/patterns-practices/reference/moduledependencyconfigurationelement-class-mspp-modularity)">ModuleDependencyConfigurationElement</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduledependencyconfigurationelement-class-mspp-modularity" data-raw-source="[ModuleDependencyConfigurationElement](/patterns-practices/reference/moduledependencyconfigurationelement-class-mspp-modularity)">ModuleDependencyConfigurationElement</a></td>
<td><div>
A <a href="/patterns-practices/reference/http://msdn.microsoft.com/en-us/library/kyx77cz3" data-raw-source="[ConfigurationElement](/patterns-practices/reference/http://msdn.microsoft.com/en-us/library/kyx77cz3)">ConfigurationElement</a> for module dependencies.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduledependencysolver-class-mspp-modularity" data-raw-source="[ModuleDependencySolver](/patterns-practices/reference/moduledependencysolver-class-mspp-modularity)">ModuleDependencySolver</a></td>
<td><div>
Used by <a href="/patterns-practices/reference/moduleinitializer-class-mspp-modularity" data-raw-source="[ModuleInitializer](/patterns-practices/reference/moduleinitializer-class-mspp-modularity)">ModuleInitializer</a> to get the load sequence for the modules to load according to their dependencies.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduledownloadprogresschangedeventargs-class-mspp-modularity" data-raw-source="[ModuleDownloadProgressChangedEventArgs](/patterns-practices/reference/moduledownloadprogresschangedeventargs-class-mspp-modularity)">ModuleDownloadProgressChangedEventArgs</a></td>
<td><div>
Provides progress information as a module downloads.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a></td>
<td><div>
Defines the metadata that describes a module.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity" data-raw-source="[ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)">ModuleInfoGroup</a></td>
<td><div>
Represents a group of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a> instances that are usually deployed together. <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity" data-raw-source="[ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)">ModuleInfoGroup</a>s are also used by the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity
)">ModuleCatalog</a> to prevent common deployment problems such as having a module that&#39;s required at startup that depends on modules that will only be downloaded on demand. The group also forwards <a href="/patterns-practices/reference/moduleinfogroup-ref-property-mspp-modularity" data-raw-source="[Ref](/patterns-practices/reference/moduleinfogroup-ref-property-mspp-modularity)">Ref</a> and <a href="/patterns-practices/reference/moduleinfogroup-initializationmode-property-mspp-modularity" data-raw-source="[InitializationMode](/patterns-practices/reference/moduleinfogroup-initializationmode-property-mspp-modularity)">InitializationMode</a> values to the <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a>s that it contains.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduleinfogroupextensions-class-mspp-modularity" data-raw-source="[ModuleInfoGroupExtensions](/patterns-practices/reference/moduleinfogroupextensions-class-mspp-modularity)">ModuleInfoGroupExtensions</a></td>
<td><div>
Defines extension methods for the <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity" data-raw-source="[ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)">ModuleInfoGroup</a> class.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduleinitializeexception-class-mspp-modularity" data-raw-source="[ModuleInitializeException](/patterns-practices/reference/moduleinitializeexception-class-mspp-modularity)">ModuleInitializeException</a></td>
<td><div>
Exception thrown by <a href="/patterns-practices/reference/imoduleinitializer-interface-mspp-modularity" data-raw-source="[IModuleInitializer](/patterns-practices/reference/imoduleinitializer-interface-mspp-modularity)">IModuleInitializer</a> implementations whenever a module fails to load.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduleinitializer-class-mspp-modularity" data-raw-source="[ModuleInitializer](/patterns-practices/reference/moduleinitializer-class-mspp-modularity)">ModuleInitializer</a></td>
<td><div>
Implements the <a href="/patterns-practices/reference/imoduleinitializer-interface-mspp-modularity" data-raw-source="[IModuleInitializer](/patterns-practices/reference/imoduleinitializer-interface-mspp-modularity)">IModuleInitializer</a> interface. Handles loading of a module based on a type.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/modulemanager-class-mspp-modularity" data-raw-source="[ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity)">ModuleManager</a></td>
<td><div>
Component responsible for coordinating the modules&#39; type loading and module initialization process.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/modulenotfoundexception-class-mspp-modularity" data-raw-source="[ModuleNotFoundException](/patterns-practices/reference/modulenotfoundexception-class-mspp-modularity
)">ModuleNotFoundException</a></td>
<td><div>
Exception thrown when a requested <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a> is not found.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/modulesconfigurationsection-class-mspp-modularity" data-raw-source="[ModulesConfigurationSection](/patterns-practices/reference/modulesconfigurationsection-class-mspp-modularity)">ModulesConfigurationSection</a></td>
<td><div>
A <a href="/patterns-practices/reference/http://msdn.microsoft.com/en-us/library/x0kca287" data-raw-source="[ConfigurationSection](/patterns-practices/reference/http://msdn.microsoft.com/en-us/library/x0kca287)">ConfigurationSection</a> for module configuration.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduletypeloadernotfoundexception-class-mspp-modularity" data-raw-source="[ModuleTypeLoaderNotFoundException](/patterns-practices/reference/moduletypeloadernotfoundexception-class-mspp-modularity)">ModuleTypeLoaderNotFoundException</a></td>
<td><div>
Exception that&#39;s thrown when there is no <a href="/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity" data-raw-source="[IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)">IModuleTypeLoader</a> registered in <a href="/patterns-practices/reference/modulemanager-moduletypeloaders-property-mspp-modularity" data-raw-source="[ModuleTypeLoaders](/patterns-practices/reference/modulemanager-moduletypeloaders-property-mspp-modularity)">ModuleTypeLoaders</a> that can handle this particular type of module.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduletypeloadingexception-class-mspp-modularity" data-raw-source="[ModuleTypeLoadingException](/patterns-practices/reference/moduletypeloadingexception-class-mspp-modularity)">ModuleTypeLoadingException</a></td>
<td><div>
Exception thrown by <a href="/patterns-practices/reference/imodulemanager-interface-mspp-modularity" data-raw-source="[IModuleManager](/patterns-practices/reference/imodulemanager-interface-mspp-modularity)">IModuleManager</a> implementations whenever a module fails to retrieve.
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
<td><a href="/patterns-practices/reference/iassemblyresolver-interface-mspp-modularity" data-raw-source="[IAssemblyResolver](/patterns-practices/reference/iassemblyresolver-interface-mspp-modularity)">IAssemblyResolver</a></td>
<td><div>
Interface for classes that are responsible for resolving and loading assembly files.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/iconfigurationstore-interface-mspp-modularity" data-raw-source="[IConfigurationStore](/patterns-practices/reference/iconfigurationstore-interface-mspp-modularity)">IConfigurationStore</a></td>
<td><div>
Defines a store for the module metadata.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/imodule-interface-mspp-modularity" data-raw-source="[IModule](/patterns-practices/reference/imodule-interface-mspp-modularity)">IModule</a></td>
<td><div>
Defines the contract for the modules deployed in the application.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/imodulecatalog-interface-mspp-modularity" data-raw-source="[IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity)">IModuleCatalog</a></td>
<td><div>
This is the expected catalog definition for the ModuleManager. The ModuleCatalog holds information about the modules that can be used by the application. Each module is described in a ModuleInfo class, that records the name, type and location of the module.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/imodulecatalogitem-interface-mspp-modularity" data-raw-source="[IModuleCatalogItem](/patterns-practices/reference/imodulecatalogitem-interface-mspp-modularity)">IModuleCatalogItem</a></td>
<td><div>
Marker interface that allows both <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity" data-raw-source="[ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)">ModuleInfoGroup</a>s and <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity
)">ModuleInfo</a>s to be added to the <a href="/patterns-practices/reference/imodulecatalog-interface-mspp-modularity" data-raw-source="[IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity)">IModuleCatalog</a> from code and XAML.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/imoduleinitializer-interface-mspp-modularity" data-raw-source="[IModuleInitializer](/patterns-practices/reference/imoduleinitializer-interface-mspp-modularity)">IModuleInitializer</a></td>
<td><div>
Declares a service which initializes the modules into the application.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/imodulemanager-interface-mspp-modularity" data-raw-source="[IModuleManager](/patterns-practices/reference/imodulemanager-interface-mspp-modularity)">IModuleManager</a></td>
<td><div>
Defines the interface for the service that will retrieve and initialize the application&#39;s modules.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity" data-raw-source="[IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)">IModuleTypeLoader</a></td>
<td><div>
Defines the interface for moduleTypeLoaders
</div></td>
</tr>
</tbody>
</table>

## Enumerations


<table>

<thead>
<tr class="header">
<th> </th>
<th>Enumeration</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubenumeration.gif" alt="Public enumeration"/></td>
<td><a href="/patterns-practices/reference/initializationmode-enumeration-mspp-modularity" data-raw-source="[InitializationMode](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity)">InitializationMode</a></td>
<td><div>
Specifies on which stage the Module group will be initialized.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubenumeration.gif" alt="Public enumeration"/></td>
<td><a href="/patterns-practices/reference/modulestate-enumeration-mspp-modularity" data-raw-source="[ModuleState](/patterns-practices/reference/modulestate-enumeration-mspp-modularity)">ModuleState</a></td>
<td><div>
Defines the states a <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a> can be in, with regards to the module loading and initialization process.
</div></td>
</tr>
</tbody>
</table>
