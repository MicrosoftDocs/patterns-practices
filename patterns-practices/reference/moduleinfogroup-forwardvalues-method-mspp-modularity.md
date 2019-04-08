---
TOCTitle: ForwardValues Method
Title: 'ModuleInfoGroup.ForwardValues Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.ForwardValues(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'moduleinfogroup-forwardvalues-method-mspp-modularity.md'
---

# ModuleInfoGroup.ForwardValues Method

Forwards [InitializationMode](/patterns-practices/reference/moduleinfogroup-initializationmode-property-mspp-modularity) and [Ref](/patterns-practices/reference/moduleinfogroup-ref-property-mspp-modularity) properties from this [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) to *moduleInfo*.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected void ForwardValues(
	ModuleInfo moduleInfo
)
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
The module info to forward values to.

## Exceptions

<table>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://msdn.microsoft.com/en-us/library/27426hcy" data-raw-source="[System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)">System.ArgumentNullException</a></td>
<td>An <a href="http://msdn.microsoft.com/en-us/library/27426hcy" data-raw-source="[ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)">ArgumentNullException</a> is thrown if <i>moduleInfo</i> is <strong>null</strong>a null reference (<strong>Nothing</strong> in Visual Basic).</td>
</tr>
</tbody>
</table>


```VB
'Declaration
Protected Sub ForwardValues ( 
	moduleInfo As ModuleInfo
)
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
The module info to forward values to.

## Exceptions

<table>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://msdn.microsoft.com/en-us/library/27426hcy" data-raw-source="[System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)">System.ArgumentNullException</a></td>
<td>An <a href="http://msdn.microsoft.com/en-us/library/27426hcy" data-raw-source="[ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)">ArgumentNullException</a> is thrown if <i>moduleInfo</i> is <strong>Nothing</strong>a null reference (<strong>Nothing</strong> in Visual Basic).</td>
</tr>
</tbody>
</table>

## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)  
[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  