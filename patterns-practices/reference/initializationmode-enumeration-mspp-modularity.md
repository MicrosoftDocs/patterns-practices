---
TOCTitle: InitializationMode Enumeration
Title: 'InitializationMode Enumeration (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.InitializationMode'
ms:mtpsurl: 'initializationmode-enumeration-mspp-modularity.md'
---

# InitializationMode Enumeration

Specifies on which stage the Module group will be initialized.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
public enum InitializationModePublic Enumeration InitializationMode

## Members

<span id="membersToggle"></span>
|     | Member name   | Value | Description                                                                                   |
|-----|---------------|-------|-----------------------------------------------------------------------------------------------|
|     | WhenAvailable | 0     | The module will be initialized when it is available on application start-up.                  |
|     | OnDemand      | 1     | The module will be initialized when requested, and not automatically on application start-up. |

## See Also
[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
