---
TOCTitle: BuildChildDomain Method
Title: 'DirectoryModuleCatalog.BuildChildDomain Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.DirectoryModuleCatalog.BuildChildDomain(System.AppDomain)'
ms:mtpsurl: 'directorymodulecatalog-buildchilddomain-method-mspp-modularity.md'
---

# DirectoryModuleCatalog.BuildChildDomain Method

Creates a new child domain and copies the evidence from a parent domain.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual AppDomain BuildChildDomain(
	AppDomain parentDomain
)
```
```VB
'Declaration
Protected Overridable Function BuildChildDomain ( 
	parentDomain As AppDomain
) As AppDomain
```

### Parameters

*parentDomain*  
Type: [System.AppDomain](http://msdn.microsoft.com/en-us/library/w124b5fa)  
The parent domain.

### Return Value

Type: [AppDomain](http://msdn.microsoft.com/en-us/library/w124b5fa)  
The new child domain.

## Remarks

 Grabs the *parentDomain* evidence and uses it to construct the new [AppDomain](http://msdn.microsoft.com/en-us/library/w124b5fa) because in a ClickOnce execution environment, creating an [AppDomain](http://msdn.microsoft.com/en-us/library/w124b5fa) will by default pick up the partial trust environment of the AppLaunch.exe, which was the root executable. The AppLaunch.exe does a create domain and applies the evidence from the ClickOnce manifests to create the domain that the application is actually executing in. This will need to be Full Trust for Prism applications.

## Exceptions

<table>
<tbody>
<tr responsive="true">
<th class="exceptionNameColumn" scope="col"><strong>Exception</strong></th>
<th class="exceptionConditionColumn" scope="col"><strong>Condition</strong></th>
</tr>
<tr>
<td data-th="Exception"><a href="http://msdn2.microsoft.com/en-us/library/27426hcy" target="_blank">System<span xmlns="">.</span>ArgumentNullException</a></td>
<td data-th="Condition">An <a href="http://msdn2.microsoft.com/en-us/library/27426hcy" target="_blank">ArgumentNullException</a> is thrown if <span class="parameter"><i>parentDomain</i></span> is null.</td>
</tr>
</tbody>
</table>

## See Also

[DirectoryModuleCatalog Class](/patterns-practices/reference/directorymodulecatalog-class-mspp-modularity)<br/>
[DirectoryModuleCatalog Members](/patterns-practices/reference/directorymodulecatalog-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)