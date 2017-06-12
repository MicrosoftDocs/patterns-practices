---
TOCTitle: InitializationMode Enumeration
Title: 'InitializationMode Enumeration (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.InitializationMode'
ms:mtpsurl: 'initializationmode-enumeration-mspp-modularity.md'
---


# InitializationMode Enumeration

Specifies on which stage the Module group will be initialized.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public enum InitializationMode
```

```VB
'Declaration
Public Enumeration InitializationMode
```

## Members

<table>
<thead>
<tr class="header">
<th> </th>
<th>Member name</th>
<th>Value</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td> </td>
<td>WhenAvailable</td>
<td>0</td>
<td>The module will be initialized when it is available on application start-up.</td>
</tr>
<tr class="odd">
<td> </td>
<td>OnDemand</td>
<td>1</td>
<td>The module will be initialized when requested, and not automatically on application start-up.</td>
</tr>
</tbody>
</table>

## See Also

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)