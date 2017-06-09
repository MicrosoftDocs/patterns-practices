---
TOCTitle: CallWeakReferenceHandlers Method
Title: 'WeakEventHandlerManager.CallWeakReferenceHandlers Method (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'M:Microsoft.Practices.Prism.Commands.WeakEventHandlerManager.CallWeakReferenceHandlers(System.Object,System.Collections.Generic.List{System.WeakReference})'
ms:mtpsurl: 'weakeventhandlermanager-callweakreferencehandlers-method-mspp-commands.md'
---


# WeakEventHandlerManager.CallWeakReferenceHandlers Method

Invokes the handlers

**Namespace:** [Microsoft.Practices.Prism.Commands](/patterns-practices/reference/mspp-commands-namespace)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
    public static void CallWeakReferenceHandlers(
	Object sender,
	List<WeakReference> handlers
)
```

### Parameters

*sender*

Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

*handlers*  

Type: [System.Collections.Generic.List](http://msdn.microsoft.com/en-us/library/6sh2ey19)&lt;[WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd)&gt;

## Syntax

```VB
    'Declaration
Public Shared Sub CallWeakReferenceHandlers ( 
	sender As Object,
	handlers As List(Of WeakReference)
)
```

### Parameters

*sender*

Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

*handlers*  

Type: [System.Collections.Generic.List](http://msdn.microsoft.com/en-us/library/6sh2ey19)(Of [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd))


## See Also

[WeakEventHandlerManager Class](/patterns-practices/reference/weakeventhandlermanager-class-mspp-commands)

[WeakEventHandlerManager Members](/patterns-practices/reference/weakeventhandlermanager-members-mspp-commands)

[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)