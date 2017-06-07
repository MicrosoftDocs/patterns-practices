---
TOCTitle: ModuleDownloadProgressChangedEventArgs Constructor
Title: 'ModuleDownloadProgressChangedEventArgs Constructor (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleDownloadProgressChangedEventArgs.\#ctor(Microsoft.Practices.Prism.Modularity.ModuleInfo,System.Int64,System.Int64)'
ms:mtpsurl: 'moduledownloadprogresschangedeventargs-constructor-mspp-modularity.md'
---

# ModuleDownloadProgressChangedEventArgs Constructor

Initializes a new instance of the [ModuleDownloadProgressChangedEventArgs](/patterns-practices/reference/moduledownloadprogresschangedeventargs-class-mspp-modularity) class.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleDownloadProgressChangedEventArgs(
	ModuleInfo moduleInfo,
	long bytesReceived,
	long totalBytesToReceive
)
```
```VB
'Declaration
Public Sub New ( 
	moduleInfo As ModuleInfo,
	bytesReceived As Long,
	totalBytesToReceive As Long
)
```

#### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
The module info.

*bytesReceived*  
Type: [System.Int64](http://msdn.microsoft.com/en-us/library/6yy583ek)  
The bytes received.

*totalBytesToReceive*  
Type: [System.Int64](http://msdn.microsoft.com/en-us/library/6yy583ek)  
The total bytes to receive.

## See Also

[ModuleDownloadProgressChangedEventArgs Class](/patterns-practices/reference/moduledownloadprogresschangedeventargs-class-mspp-modularity)

[ModuleDownloadProgressChangedEventArgs Members](/patterns-practices/reference/moduledownloadprogresschangedeventargs-members-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
