---
TOCTitle: 'ModuleInfo Constructor (String, String, String[])'
Title: 'ModuleInfo Constructor (String, String, String[]) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfo.\#ctor(System.String,System.String,System.String[])'
ms:mtpsurl: 'moduleinfo-constructor-mspp-modularity.md'
---

# ModuleInfo Constructor (String, String, String[])

Initializes a new instance of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity).

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleInfo(
	string name,
	string type,
	params string[] dependsOn
)
```

#### Parameters

*name*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The module's name.

*type*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The module [Type](http://msdn.microsoft.com/en-us/library/42892f65)'s AssemblyQualifiedName.

*dependsOn*  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)[]  
The modules this instance depends on.

## Exceptions

| Exception | Condition |
|---|---|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) is thrown if *dependsOn* is **null**a null reference (**Nothing** in Visual Basic). |

## See Also

[ModuleInfo Class](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
[ModuleInfo Members](/patterns-practices/reference/moduleinfo-members-mspp-modularity)  
ModuleInfo Overload  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  



# ModuleInfo Constructor (String, String, String())

Initializes a new instance of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity).

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Sub New ( 
	name As String,
	type As String,
	ParamArray dependsOn As String()
)
```

#### Parameters

*name*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The module's name.

*type*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The module [Type](http://msdn.microsoft.com/en-us/library/42892f65)'s AssemblyQualifiedName.

*dependsOn*  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)()  
The modules this instance depends on.

## Exceptions

| Exception | Condition |
|---|---|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) is thrown if *dependsOn* is **Nothing**a null reference (**Nothing** in Visual Basic). |

## See Also

[ModuleInfo Class](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
[ModuleInfo Members](/patterns-practices/reference/moduleinfo-members-mspp-modularity)  
ModuleInfo Overload  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  