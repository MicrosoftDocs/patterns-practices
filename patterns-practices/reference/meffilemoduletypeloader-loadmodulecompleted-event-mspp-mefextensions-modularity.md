---
TOCTitle: LoadModuleCompleted Event
Title: 'MefFileModuleTypeLoader.LoadModuleCompleted Event (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'E:Microsoft.Practices.Prism.MefExtensions.Modularity.MefFileModuleTypeLoader.LoadModuleCompleted'
ms:mtpsurl: 'meffilemoduletypeloader-loadmodulecompleted-event-mspp-mefextensions-modularity.md'
---

# MefFileModuleTypeLoader.LoadModuleCompleted Event

Raised when a module is loaded or fails to load.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public virtual event EventHandler<LoadModuleCompletedEventArgs> LoadModuleCompleted
```

### Value

Type: [System.EventHandler](http://msdn2.microsoft.com/en-us/library/db0etb8x)&lt;[LoadModuleCompletedEventArgs](/patterns-practices/reference/loadmodulecompletedeventargs-class-mspp-modularity)&gt;

## Syntax

```VB
'Declaration
Public Overridable Event LoadModuleCompleted As EventHandler(Of LoadModuleCompletedEventArgs)
```

### Value

Type: [System.EventHandler](http://msdn2.microsoft.com/en-us/library/db0etb8x)(Of [LoadModuleCompletedEventArgs](/patterns-practices/reference/loadmodulecompletedeventargs-class-mspp-modularity))

### Implements

[IModuleTypeLoader.LoadModuleCompleted](/patterns-practices/reference/imoduletypeloader-loadmodulecompleted-event-mspp-modularity)

## See Also

[MefFileModuleTypeLoader Class](/patterns-practices/reference/meffilemoduletypeloader-class-mspp-mefextensions-modularity)  
[MefFileModuleTypeLoader Members](/patterns-practices/reference/meffilemoduletypeloader-members-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)