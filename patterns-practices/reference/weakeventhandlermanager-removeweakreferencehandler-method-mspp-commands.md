---
TOCTitle: RemoveWeakReferenceHandler Method
Title: 'WeakEventHandlerManager.RemoveWeakReferenceHandler Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.WeakEventHandlerManager.RemoveWeakReferenceHandler(System.Collections.Generic.List{System.WeakReference},System.EventHandler)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736259(v=PandP.50)'
---

# WeakEventHandlerManager.RemoveWeakReferenceHandler Method

Removes an event handler from the reference list.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))

=======
**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public static void RemoveWeakReferenceHandler(
	List<WeakReference> handlers,
	EventHandler handler
)
```

### Parameters

*handlers*

	Type: [System.Collections.Generic.List](http://msdn2.microsoft.com/en-us/library/6sh2ey19)&lt;[WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd)&gt;

	Handler list to remove reference from.

*handler*  
		
	Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/xhb70ccc)
	
	Handler to remove.

```VB
'Declaration
Public Shared Sub RemoveWeakReferenceHandler ( 
	handlers As List(Of WeakReference),
	handler As EventHandler
)
```

### Parameters

*handlers*  
		
	Type: [System.Collections.Generic.List](http://msdn2.microsoft.com/en-us/library/6sh2ey19)(Of [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd))
	Handler list to remove reference from.

*handler*  

	Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/xhb70ccc)
	Handler to remove.

## See Also

[WeakEventHandlerManager Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.weakeventhandlermanager(v=pandp.50))
=======
[WeakEventHandlerManager Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.weakeventhandlermanager)

[WeakEventHandlerManager Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands.weakeventhandlermanager_members(v=pandp.50))

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.commands(v=pandp.50))
=======
[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
