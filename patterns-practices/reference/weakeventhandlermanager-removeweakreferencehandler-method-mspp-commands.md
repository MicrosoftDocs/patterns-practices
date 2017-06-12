---
TOCTitle: RemoveWeakReferenceHandler Method
Title: 'WeakEventHandlerManager.RemoveWeakReferenceHandler Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.WeakEventHandlerManager.RemoveWeakReferenceHandler(System.Collections.Generic.List{System.WeakReference},System.EventHandler)'
ms:mtpsurl: 'weakeventhandlermanager-removeweakreferencehandler-method-mspp-commands.md'
---

# WeakEventHandlerManager.RemoveWeakReferenceHandler Method

Removes an event handler from the reference list.

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public static void RemoveWeakReferenceHandler(
	List<WeakReference> handlers,
	EventHandler handler
)
```

### Parameters

*handlers*<br/>
Type: [System.Collections.Generic.List](http://msdn.microsoft.com/en-us/library/6sh2ey19)&lt;[WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd)&gt;<br/>
Handler list to remove reference from.

*handler*<br/>
Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/xhb70ccc)<br/>
Handler to remove.

```VB
'Declaration
Public Shared Sub RemoveWeakReferenceHandler ( 
	handlers As List(Of WeakReference),
	handler As EventHandler
)
```

### Parameters

*handlers*<br/>
Type: [System.Collections.Generic.List](http://msdn.microsoft.com/en-us/library/6sh2ey19)(Of [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd))<br/>
Handler list to remove reference from.

*handler*<br/>
Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/xhb70ccc)<br/>
Handler to remove.

## See Also

[WeakEventHandlerManager Class](/patterns-practices/reference/weakeventhandlermanager-class-mspp-commands)<br/>
[WeakEventHandlerManager Members](/patterns-practices/reference/weakeventhandlermanager-members-mspp-commands)<br/>
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)<br/>