---
TOCTitle: LoadModuleCompleted Event
Title: 'IModuleTypeLoader.LoadModuleCompleted Event (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'E:Microsoft.Practices.Prism.Modularity.IModuleTypeLoader.LoadModuleCompleted'
ms:mtpsurl: 'imoduletypeloader-loadmodulecompleted-event-mspp-modularity.md'
---



# IModuleTypeLoader.LoadModuleCompleted Event

Raised when a module is loaded or fails to load.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
event EventHandler<LoadModuleCompletedEventArgs> LoadModuleCompleted
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)&lt;[LoadModuleCompletedEventArgs](/patterns-practices/reference/loadmodulecompletedeventargs-class-mspp-modularity)&gt;


```VB
'Declaration
Event LoadModuleCompleted As EventHandler(Of LoadModuleCompletedEventArgs)
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)(Of [LoadModuleCompletedEventArgs](/patterns-practices/reference/loadmodulecompletedeventargs-class-mspp-modularity))

## Remarks

This event is raised once per ModuleInfo instance requested in [LoadModuleType(ModuleInfo)](/patterns-practices/reference/imoduletypeloader-loadmoduletype-method-mspp-modularity).

## See Also

[IModuleTypeLoader Interface](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)<br/>
[IModuleTypeLoader Members](/patterns-practices/reference/imoduletypeloader-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)