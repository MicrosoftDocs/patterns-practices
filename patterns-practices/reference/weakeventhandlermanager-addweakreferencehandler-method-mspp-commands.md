---
TOCTitle: AddWeakReferenceHandler Method
Title: 'WeakEventHandlerManager.AddWeakReferenceHandler Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.WeakEventHandlerManager.AddWeakReferenceHandler(System.Collections.Generic.List{System.WeakReference}@,System.EventHandler,System.Int32)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736187(v=PandP.50)'
---

Prism Class Library

WeakEventHandlerManager.AddWeakReferenceHandler Method
==========================================================

Adds a handler to the supplied list in a weak way.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


public static void AddWeakReferenceHandler( ref List&lt;WeakReference&gt; handlers, EventHandler handler, int defaultListSize )Public Shared Sub AddWeakReferenceHandler ( ByRef handlers As List(Of WeakReference), handler As EventHandler, defaultListSize As Integer )

### Parameters

handlers  
Type: [System.Collections.Generic.List](http://msdn.microsoft.com/en-us/library/6sh2ey19)&lt;(Of &lt;([WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd)&gt;)&gt;)
Existing handler list. It will be created if null.

handler  
Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/xhb70ccc)
Handler to add.

defaultListSize  
Type: [System.Int32](http://msdn.microsoft.com/en-us/library/td2s409d)
Default list size.

See Also
--------


[WeakEventHandlerManager Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.weakeventhandlermanager)

[WeakEventHandlerManager Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.weakeventhandlermanager)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
