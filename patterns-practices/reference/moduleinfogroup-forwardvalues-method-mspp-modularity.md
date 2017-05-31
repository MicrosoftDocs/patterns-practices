---
TOCTitle: ForwardValues Method
Title: 'ModuleInfoGroup.ForwardValues Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.ForwardValues(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'moduleinfogroup-forwardvalues-method-mspp-modularity.md'
---

# ModuleInfoGroup.ForwardValues Method

Forwards [InitializationMode](/patterns-practices/reference/moduleinfogroup-initializationmode-property-mspp-modularity) and [Ref](/patterns-practices/reference/moduleinfogroup-ref-property-mspp-modularity) properties from this [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) to moduleInfo.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)

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

 Exception                                                                              Condition                                                                                                                                            
 
 [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)  An [ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) is thrown if *moduleInfo* is **nulla** null reference (**Nothing** in Visual Basic).

## See Also
[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)

[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
