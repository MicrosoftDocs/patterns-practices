---
TOCTitle: LoadModuleCompleted Event
Title: 'IModuleTypeLoader.LoadModuleCompleted Event (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'E:Microsoft.Practices.Prism.Modularity.IModuleTypeLoader.LoadModuleCompleted'
ms:mtpsurl: 'imoduletypeloader-loadmodulecompleted-event-mspp-modularity.md'
---

Prism Class Library

=======

# IModuleTypeLoader.LoadModuleCompleted Event

Raised when a module is loaded or fails to load.

**Namespace:** [Microsoft.Practices.Prism.Modularity](mspp-modularity-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)
## Syntax

```C#
    event EventHandler<LoadModuleCompletedEventArgs> LoadModuleCompleted
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)&lt;[LoadModuleCompletedEventArgs](loadmodulecompletedeventargs-class-mspp-modularity.md)&gt;

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

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)&lt;[LoadModuleCompletedEventArgs](loadmodulecompletedeventargs-class-mspp-modularity.md)&gt;

## Syntax

```VB
'Declaration
Event LoadModuleCompleted As EventHandler(Of LoadModuleCompletedEventArgs)
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)(Of [LoadModuleCompletedEventArgs](loadmodulecompletedeventargs-class-mspp-modularity.md))

## Remarks

This event is raised once per ModuleInfo instance requested in [LoadModuleType(ModuleInfo)](imoduletypeloader-loadmoduletype-method-mspp-modularity.md).

## See Also

[IModuleTypeLoader Interface](imoduletypeloader-interface-mspp-modularity.md)

[IModuleTypeLoader Members](imoduletypeloader-members-mspp-modularity.md)

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace.md)