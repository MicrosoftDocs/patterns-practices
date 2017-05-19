---
TOCTitle: ModuleDownloadProgressChanged Event
Title: 'MefFileModuleTypeLoader.ModuleDownloadProgressChanged Event (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'E:Microsoft.Practices.Prism.MefExtensions.Modularity.MefFileModuleTypeLoader.ModuleDownloadProgressChanged'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430920(v=PandP.50)'
---

# MefFileModuleTypeLoader.ModuleDownloadProgressChanged Event

Raised repeatedly to provide progress as modules are loaded in the background.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.modularity)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public virtual event EventHandler<ModuleDownloadProgressChangedEventArgs> ModuleDownloadProgressChanged
```

#### Value

Type: [System.EventHandler](http://msdn2.microsoft.com/en-us/library/db0etb8x)&lt;[ModuleDownloadProgressChangedEventArgs](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduledownloadprogresschangedeventargs(v=pandp.50))&gt;

## Syntax

```VB
'Declaration
Public Overridable Event ModuleDownloadProgressChanged As EventHandler(Of ModuleDownloadProgressChangedEventArgs)
```

#### Value

Type: [System.EventHandler](http://msdn2.microsoft.com/en-us/library/db0etb8x)(Of [ModuleDownloadProgressChangedEventArgs](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduledownloadprogresschangedeventargs(v=pandp.50)))

#### Implements

[IModuleTypeLoader.ModuleDownloadProgressChanged](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduletypeloader.moduledownloadprogresschanged(v=pandp.50))

## See Also

[MefFileModuleTypeLoader Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader(v=pandp.50))

[MefFileModuleTypeLoader Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader_members(v=pandp.50))

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity(v=pandp.50))
