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
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[AssemblyResolver](/patterns-practices/reference/assemblyresolver-class-mspp-modularity)</td>
<td><div>
Handles AppDomain's AssemblyResolve event to be able to load assemblies dynamically in the LoadFrom context, but be able to reference the type from assemblies loaded in the Load context.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ConfigurationModuleCatalog](/patterns-practices/reference/configurationmodulecatalog-class-mspp-modularity)</td>
<td><div>
A catalog built from a configuration file.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ConfigurationStore](/patterns-practices/reference/configurationstore-class-mspp-modularity)</td>
<td><div>
Defines a store for the module metadata.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[CyclicDependencyFoundException](/patterns-practices/reference/cyclicdependencyfoundexception-class-mspp-modularity)</td>
<td><div>
Represents the exception that is thrown when there is a circular dependency between modules during the module loading process.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[DirectoryModuleCatalog](/patterns-practices/reference/directorymodulecatalog-class-mspp-modularity)</td>
<td><div>
Represets a catalog created from a directory on disk.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[DuplicateModuleException](/patterns-practices/reference/duplicatemoduleexception-class-mspp-modularity)</td>
<td><div>
Exception thrown when a module is declared twice in the same catalog.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[FileModuleTypeLoader](/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity)</td>
<td><div>
Loads modules from an arbitrary location on the filesystem. This typeloader is only called if [ModuleInfo](/patterns-practices/reference/https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) classes have a Ref parameter that starts with &quot;file://&quot;. This class is only used on the Desktop version of the Prism Library.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[LoadModuleCompletedEventArgs](/patterns-practices/reference/loadmodulecompletedeventargs-class-mspp-modularity)</td>
<td><div>
Provides completion information after a module is loaded, or fails to load.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModularityException](/patterns-practices/reference/modularityexception-class-mspp-modularity)</td>
<td><div>
Base class for exceptions that are thrown because of a problem with modules.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleAttribute](/patterns-practices/reference/moduleattribute-class-mspp-modularity)</td>
<td><div>
Indicates that the class should be considered a named module using the provided module name.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)</td>
<td><div>
The [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) holds information about the modules that can be used by the application. Each module is described in a [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) class, that records the name, type and location of the module. It also verifies that the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) is internally valid. That means that it does not have: Circular dependenciesMissing dependencies Invalid dependencies, such as a Module that's loaded at startup that depends on a module that might need to be retrieved. The [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) also serves as a baseclass for more specialized Catalogs .
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleConfigurationElement](/patterns-practices/reference/moduleconfigurationelement-class-mspp-modularity)</td>
<td><div>
A configuration element to declare module metadata.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleConfigurationElementCollection](/patterns-practices/reference/moduleconfigurationelementcollection-class-mspp-modularity)</td>
<td><div>
A collection of [ModuleConfigurationElement](/patterns-practices/reference/moduleconfigurationelement-class-mspp-modularity).
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleDependencyAttribute](/patterns-practices/reference/moduledependencyattribute-class-mspp-modularity)</td>
<td><div>
Specifies that the current module has a dependency on another module. This attribute should be used on classes that implement [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity).
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleDependencyCollection](/patterns-practices/reference/moduledependencycollection-class-mspp-modularity)</td>
<td><div>
A collection of [ModuleDependencyConfigurationElement](/patterns-practices/reference/moduledependencyconfigurationelement-class-mspp-modularity).
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleDependencyConfigurationElement](/patterns-practices/reference/moduledependencyconfigurationelement-class-mspp-modularity)</td>
<td><div>
A [ConfigurationElement](/patterns-practices/reference/http://msdn.microsoft.com/en-us/library/kyx77cz3) for module dependencies.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleDependencySolver](/patterns-practices/reference/moduledependencysolver-class-mspp-modularity)</td>
<td><div>
Used by [ModuleInitializer](/patterns-practices/reference/moduleinitializer-class-mspp-modularity) to get the load sequence for the modules to load according to their dependencies.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleDownloadProgressChangedEventArgs](/patterns-practices/reference/moduledownloadprogresschangedeventargs-class-mspp-modularity)</td>
<td><div>
Provides progress information as a module downloads.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)</td>
<td><div>
Defines the metadata that describes a module.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)</td>
<td><div>
Represents a group of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) instances that are usually deployed together. [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)s are also used by the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity
) to prevent common deployment problems such as having a module that's required at startup that depends on modules that will only be downloaded on demand. The group also forwards [Ref](/patterns-practices/reference/moduleinfogroup-ref-property-mspp-modularity) and [InitializationMode](/patterns-practices/reference/moduleinfogroup-initializationmode-property-mspp-modularity) values to the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s that it contains.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleInfoGroupExtensions](/patterns-practices/reference/moduleinfogroupextensions-class-mspp-modularity)</td>
<td><div>
Defines extension methods for the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) class.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleInitializeException](/patterns-practices/reference/moduleinitializeexception-class-mspp-modularity)</td>
<td><div>
Exception thrown by [IModuleInitializer](/patterns-practices/reference/imoduleinitializer-interface-mspp-modularity) implementations whenever a module fails to load.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleInitializer](/patterns-practices/reference/moduleinitializer-class-mspp-modularity)</td>
<td><div>
Implements the [IModuleInitializer](/patterns-practices/reference/imoduleinitializer-interface-mspp-modularity) interface. Handles loading of a module based on a type.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity)</td>
<td><div>
Component responsible for coordinating the modules' type loading and module initialization process.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleNotFoundException](/patterns-practices/reference/modulenotfoundexception-class-mspp-modularity
)</td>
<td><div>
Exception thrown when a requested [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) is not found.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModulesConfigurationSection](/patterns-practices/reference/modulesconfigurationsection-class-mspp-modularity)</td>
<td><div>
A [ConfigurationSection](/patterns-practices/reference/http://msdn.microsoft.com/en-us/library/x0kca287) for module configuration.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleTypeLoaderNotFoundException](/patterns-practices/reference/moduletypeloadernotfoundexception-class-mspp-modularity)</td>
<td><div>
Exception that's thrown when there is no [IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity) registered in [ModuleTypeLoaders](/patterns-practices/reference/modulemanager-moduletypeloaders-property-mspp-modularity) that can handle this particular type of module.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ModuleTypeLoadingException](/patterns-practices/reference/moduletypeloadingexception-class-mspp-modularity)</td>
<td><div>
Exception thrown by [IModuleManager](/patterns-practices/reference/imodulemanager-interface-mspp-modularity) implementations whenever a module fails to retrieve.
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
<td>[IAssemblyResolver](/patterns-practices/reference/iassemblyresolver-interface-mspp-modularity)</td>
<td><div>
Interface for classes that are responsible for resolving and loading assembly files.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IConfigurationStore](/patterns-practices/reference/iconfigurationstore-interface-mspp-modularity)</td>
<td><div>
Defines a store for the module metadata.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IModule](/patterns-practices/reference/imodule-interface-mspp-modularity)</td>
<td><div>
Defines the contract for the modules deployed in the application.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity)</td>
<td><div>
This is the expected catalog definition for the ModuleManager. The ModuleCatalog holds information about the modules that can be used by the application. Each module is described in a ModuleInfo class, that records the name, type and location of the module.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IModuleCatalogItem](/patterns-practices/reference/imodulecatalogitem-interface-mspp-modularity)</td>
<td><div>
Marker interface that allows both [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)s and [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity
)s to be added to the [IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity) from code and XAML.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IModuleInitializer](/patterns-practices/reference/imoduleinitializer-interface-mspp-modularity)</td>
<td><div>
Declares a service which initializes the modules into the application.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IModuleManager](/patterns-practices/reference/imodulemanager-interface-mspp-modularity)</td>
<td><div>
Defines the interface for the service that will retrieve and initialize the application's modules.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)</td>
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
<td>![Public enumeration](/patterns-practices/reference/images/pubenumeration.gif)</td>
<td>[InitializationMode](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity)</td>
<td><div>
Specifies on which stage the Module group will be initialized.
</div></td>
</tr>
<tr class="even">
<td>![Public enumeration](/patterns-practices/reference/images/pubenumeration.gif)</td>
<td>[ModuleState](/patterns-practices/reference/modulestate-enumeration-mspp-modularity)</td>
<td><div>
Defines the states a [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) can be in, with regards to the module loading and initialization process.
</div></td>
</tr>
</tbody>
</table>
