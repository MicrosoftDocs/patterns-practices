---
TOCTitle: LoadModuleCompleted Event
Title: 'IModuleTypeLoader.LoadModuleCompleted Event (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'E:Microsoft.Practices.Prism.Modularity.IModuleTypeLoader.LoadModuleCompleted'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430925(v=PandP.50)'
---

Prism Class Library

=======

# IModuleTypeLoader.LoadModuleCompleted Event

Raised when a module is loaded or fails to load.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)
## Syntax

```C#
    event EventHandler<LoadModuleCompletedEventArgs> LoadModuleCompleted
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)&lt;[LoadModuleCompletedEventArgs](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.loadmodulecompletedeventargs(v=pandp.50))&gt;

## Syntax

```VB
    'Declaration
    Event LoadModuleCompleted As EventHandler(Of LoadModuleCompletedEventArgs)
```

=======

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
event EventHandler<LoadModuleCompletedEventArgs> LoadModuleCompleted
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)&lt;[LoadModuleCompletedEventArgs](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.loadmodulecompletedeventargs(v=pandp.50))&gt;

## Syntax

```VB
'Declaration
Event LoadModuleCompleted As EventHandler(Of LoadModuleCompletedEventArgs)
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)(Of [LoadModuleCompletedEventArgs](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.loadmodulecompletedeventargs(v=pandp.50)))

## Remarks

This event is raised once per ModuleInfo instance requested in [LoadModuleType(ModuleInfo)](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduletypeloader.loadmoduletype(v=pandp.50)).

## See Also

[IModuleTypeLoader Interface](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduletypeloader(v=pandp.50))

[IModuleTypeLoader Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduletypeloader_members(v=pandp.50))

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))