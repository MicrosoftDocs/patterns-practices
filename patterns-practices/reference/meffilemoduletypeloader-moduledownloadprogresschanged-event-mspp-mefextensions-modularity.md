---
TOCTitle: ModuleDownloadProgressChanged Event
Title: 'MefFileModuleTypeLoader.ModuleDownloadProgressChanged Event (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'E:Microsoft.Practices.Prism.MefExtensions.Modularity.MefFileModuleTypeLoader.ModuleDownloadProgressChanged'
ms:mtpsurl: 'meffilemoduletypeloader-moduledownloadprogresschanged-event-mspp-mefextensions-modularity.md'
---

# MefFileModuleTypeLoader.ModuleDownloadProgressChanged Event

Raised repeatedly to provide progress as modules are loaded in the background.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public virtual event EventHandler<ModuleDownloadProgressChangedEventArgs> ModuleDownloadProgressChanged
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)&lt;[ModuleDownloadProgressChangedEventArgs](/patterns-practices/reference/moduledownloadprogresschangedeventargs-class-mspp-modularity)&gt;

## Syntax

```VB
'Declaration
Public Overridable Event ModuleDownloadProgressChanged As EventHandler(Of ModuleDownloadProgressChangedEventArgs)
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)(Of [ModuleDownloadProgressChangedEventArgs](/patterns-practices/reference/moduledownloadprogresschangedeventargs-class-mspp-modularity))

### Implements

[IModuleTypeLoader.ModuleDownloadProgressChanged](/patterns-practices/reference/imoduletypeloader-moduledownloadprogresschanged-event-mspp-modularity)

## See Also

[MefFileModuleTypeLoader Class](/patterns-practices/reference/meffilemoduletypeloader-class-mspp-mefextensions-modularity)<br/>
[MefFileModuleTypeLoader Members](/patterns-practices/reference/meffilemoduletypeloader-members-mspp-mefextensions-modularity)<br/>
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)