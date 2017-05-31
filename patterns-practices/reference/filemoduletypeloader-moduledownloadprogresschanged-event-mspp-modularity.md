---
TOCTitle: ModuleDownloadProgressChanged Event
Title: 'FileModuleTypeLoader.ModuleDownloadProgressChanged Event (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'E:Microsoft.Practices.Prism.Modularity.FileModuleTypeLoader.ModuleDownloadProgressChanged'
ms:mtpsurl: 'filemoduletypeloader-moduledownloadprogresschanged-event-mspp-modularity.md'
---

# FileModuleTypeLoader.ModuleDownloadProgressChanged Event

Raised repeatedly to provide progress as modules are loaded in the background.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public event EventHandler<ModuleDownloadProgressChangedEventArgs> ModuleDownloadProgressChanged
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)&lt;[ModuleDownloadProgressChangedEventArgs](/patterns-practices/reference/moduledownloadprogresschangedeventargs-class-mspp-modularity)&gt;

## Syntax

```VB
'Declaration
Public Event ModuleDownloadProgressChanged As EventHandler(Of ModuleDownloadProgressChangedEventArgs)
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)(Of [ModuleDownloadProgressChangedEventArgs](/patterns-practices/reference/moduledownloadprogresschangedeventargs-class-mspp-modularity))

### Implements

[IModuleTypeLoader.ModuleDownloadProgressChanged](/patterns-practices/reference/imoduletypeloader-moduledownloadprogresschanged-event-mspp-modularity)

## See Also

[FileModuleTypeLoader Class](/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity)

[FileModuleTypeLoader Members](/patterns-practices/reference/filemoduletypeloader-members-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)