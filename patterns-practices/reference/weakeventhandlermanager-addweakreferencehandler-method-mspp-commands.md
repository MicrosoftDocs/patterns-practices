---
TOCTitle: AddWeakReferenceHandler Method
Title: 'WeakEventHandlerManager.AddWeakReferenceHandler Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.WeakEventHandlerManager.AddWeakReferenceHandler(System.Collections.Generic.List{System.WeakReference}@,System.EventHandler,System.Int32)'
ms:mtpsurl: 'weakeventhandlermanager-addweakreferencehandler-method-mspp-commands.md'
---

# WeakEventHandlerManager.AddWeakReferenceHandler Method

Adds a handler to the supplied list in a weak way.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#  
public static void AddWeakReferenceHandler(
	ref List<WeakReference> handlers,
	EventHandler handler,
	int defaultListSize
)
```

### Parameters

*handlers*

Type: [System.Collections.Generic.List](http://msdn.microsoft.com/en-us/library/6sh2ey19)&lt;[WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd)&gt;

Existing handler list. It will be created if null.

*handler*  

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/xhb70ccc)

Handler to add.

*defaultListSize*

Type: [System.Int32](http://msdn.microsoft.com/en-us/library/td2s409d)

Default list size.


## Syntax

```VB  
'Declaration
Public Shared Sub AddWeakReferenceHandler ( 
	ByRef handlers As List(Of WeakReference),
	handler As EventHandler,
	defaultListSize As Integer
)
```

### Parameters

*handlers*  

Type: [System.Collections.Generic.List](http://msdn.microsoft.com/en-us/library/6sh2ey19)(Of [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd))

Existing handler list. It will be created if null.

*handler*

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/xhb70ccc)

Handler to add.

*defaultListSize*

Type: [System.Int32](http://msdn.microsoft.com/en-us/library/td2s409d)

Default list size.

## See Also

[WeakEventHandlerManager Class](/patterns-practices/reference/weakeventhandlermanager-class-mspp-commands)  
[WeakEventHandlerManager Members](/patterns-practices/reference/weakeventhandlermanager-members-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)