---
TOCTitle: 'Microsoft.Practices.Prism.Modularity Namespace'
Title: 'Microsoft.Practices.Prism.Modularity Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Modularity'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419043(v=PandP.50)'
---

# Microsoft.Practices.Prism.Modularity Namespace

## Classes

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
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.assemblyresolver">AssemblyResolver</a></td>
<td><div>
Handles AppDomain's AssemblyResolve event to be able to load assemblies dynamically in the LoadFrom context, but be able to reference the type from assemblies loaded in the Load context.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.configurationmodulecatalog">ConfigurationModuleCatalog</a></td>
<td><div>
A catalog built from a configuration file.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.configurationstore(v=pandp.50)">ConfigurationStore</a></td>
<td><div>
Defines a store for the module metadata.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.cyclicdependencyfoundexception(v=pandp.50)">CyclicDependencyFoundException</a></td>
<td><div>
Represents the exception that is thrown when there is a circular dependency between modules during the module loading process.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.directorymodulecatalog(v=pandp.50)">DirectoryModuleCatalog</a></td>
<td><div>
Represets a catalog created from a directory on disk.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.duplicatemoduleexception(v=pandp.50">DuplicateModuleException</a></td>
<td><div>
Exception thrown when a module is declared twice in the same catalog.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.filemoduletypeloader(v=pandp.50)">FileModuleTypeLoader</a></td>
<td><div>
Loads modules from an arbitrary location on the filesystem. This typeloader is only called if <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> classes have a Ref parameter that starts with &quot;file://&quot;. This class is only used on the Desktop version of the Prism Library.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.loadmodulecompletedeventargs">LoadModuleCompletedEventArgs</a></td>
<td><div>
Provides completion information after a module is loaded, or fails to load.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modularityexception">ModularityException</a></td>
<td><div>
Base class for exceptions that are thrown because of a problem with modules.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleattribute">ModuleAttribute</a></td>
<td><div>
Indicates that the class should be considered a named module using the provided module name.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a></td>
<td><div>
The <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a> holds information about the modules that can be used by the application. Each module is described in a <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> class, that records the name, type and location of the module. It also verifies that the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a> is internally valid. That means that it does not have: Circular dependenciesMissing dependencies Invalid dependencies, such as a Module that's loaded at startup that depends on a module that might need to be retrieved. The <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a> also serves as a baseclass for more specialized Catalogs .
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleconfigurationelement">ModuleConfigurationElement</a></td>
<td><div>
A configuration element to declare module metadata.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleconfigurationelementcollection">ModuleConfigurationElementCollection</a></td>
<td><div>
A collection of <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleconfigurationelement">ModuleConfigurationElement</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduledependencyattribute">ModuleDependencyAttribute</a></td>
<td><div>
Specifies that the current module has a dependency on another module. This attribute should be used on classes that implement <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imodule">IModule</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduledependencycollection">ModuleDependencyCollection</a></td>
<td><div>
A collection of <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduledependencyconfigurationelement">ModuleDependencyConfigurationElement</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduledependencyconfigurationelement">ModuleDependencyConfigurationElement</a></td>
<td><div>
A <a href="http://msdn.microsoft.com/en-us/library/kyx77cz3">ConfigurationElement</a> for module dependencies.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduledependencysolver">ModuleDependencySolver</a></td>
<td><div>
Used by <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinitializer">ModuleInitializer</a> to get the load sequence for the modules to load according to their dependencies.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduledownloadprogresschangedeventargs">ModuleDownloadProgressChangedEventArgs</a></td>
<td><div>
Provides progress information as a module downloads.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a></td>
<td><div>
Defines the metadata that describes a module.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup">ModuleInfoGroup</a></td>
<td><div>
Represents a group of <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> instances that are usually deployed together. <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup">ModuleInfoGroup</a>s are also used by the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a> to prevent common deployment problems such as having a module that's required at startup that depends on modules that will only be downloaded on demand. The group also forwards <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup.ref">Ref</a> and <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup.initializationmode">InitializationMode</a> values to the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s that it contains.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroupextensions">ModuleInfoGroupExtensions</a></td>
<td><div>
Defines extension methods for the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup">ModuleInfoGroup</a> class.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinitializeexception">ModuleInitializeException</a></td>
<td><div>
Exception thrown by <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduleinitializer">IModuleInitializer</a> implementations whenever a module fails to load.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinitializer">ModuleInitializer</a></td>
<td><div>
Implements the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduleinitializer">IModuleInitializer</a> interface. Handles loading of a module based on a type.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager">ModuleManager</a></td>
<td><div>
Component responsible for coordinating the modules' type loading and module initialization process.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulenotfoundexception">ModuleNotFoundException</a></td>
<td><div>
Exception thrown when a requested <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> is not found.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulesconfigurationsection">ModulesConfigurationSection</a></td>
<td><div>
A <a href="http://msdn.microsoft.com/en-us/library/x0kca287">ConfigurationSection</a> for module configuration.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduletypeloadernotfoundexception">ModuleTypeLoaderNotFoundException</a></td>
<td><div>
Exception that's thrown when there is no <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduletypeloader">IModuleTypeLoader</a> registered in <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager.moduletypeloaders">ModuleTypeLoaders</a> that can handle this particular type of module.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduletypeloadingexception">ModuleTypeLoadingException</a></td>
<td><div>
Exception thrown by <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imodulemanager">IModuleManager</a> implementations whenever a module fails to retrieve.
</div></td>
</tr>
</tbody>
</table>

## Interfaces

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
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.iassemblyresolver">IAssemblyResolver</a></td>
<td><div>
Interface for classes that are responsible for resolving and loading assembly files.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.iconfigurationstore">IConfigurationStore</a></td>
<td><div>
Defines a store for the module metadata.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imodule">IModule</a></td>
<td><div>
Defines the contract for the modules deployed in the application.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a></td>
<td><div>
This is the expected catalog definition for the ModuleManager. The ModuleCatalog holds information about the modules that can be used by the application. Each module is described in a ModuleInfo class, that records the name, type and location of the module.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imodulecatalogitem">IModuleCatalogItem</a></td>
<td><div>
Marker interface that allows both <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup">ModuleInfoGroup</a>s and <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s to be added to the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> from code and XAML.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduleinitializer">IModuleInitializer</a></td>
<td><div>
Declares a service which initializes the modules into the application.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imodulemanager">IModuleManager</a></td>
<td><div>
Defines the interface for the service that will retrieve and initialize the application's modules.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduletypeloader">IModuleTypeLoader</a></td>
<td><div>
Defines the interface for moduleTypeLoaders
</div></td>
</tr>
</tbody>
</table>

## Enumerations

<span id="enumerationToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubenumeration(en-us,PandP.50).gif" title="Public enumeration" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.initializationmode">InitializationMode</a></td>
<td><div>
Specifies on which stage the Module group will be initialized.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419043.pubenumeration(en-us,PandP.50).gif" title="Public enumeration" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulestate">ModuleState</a></td>
<td><div>
Defines the states a <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> can be in, with regards to the module loading and initialization process.
</div></td>
</tr>
</tbody>
</table>
