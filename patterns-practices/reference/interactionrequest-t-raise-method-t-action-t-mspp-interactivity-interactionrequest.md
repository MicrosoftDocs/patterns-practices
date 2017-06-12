---
TOCTitle: 'Raise Method (T, Action(T))'
Title: 'InteractionRequest(T).Raise Method (T, Action(T)) (Microsoft.Practices.Prism.Interactivity.InteractionRequest)'
ms:assetid: 'M:Microsoft.Practices.Prism.Interactivity.InteractionRequest.InteractionRequest\`1.Raise(\`0,System.Action{\`0})'
ms:mtpsurl: 'interactionrequest-t-raise-method-t-action-t-mspp-interactivity-interactionrequest.md'
---

# InteractionRequest&lt;T&gt;.Raise Method (T, Action&lt;T&gt;)

Fires the Raised event.

**Namespace:** [Microsoft.Practices.Prism.Interactivity.InteractionRequest](/patterns-practices/reference/mspp-interactivity-interactionrequest-namespace)

**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void Raise(
	T context,
	Action<T> callback
)
```

### Parameters

_context_  
Type: [T](/patterns-practices/reference/interactionrequest-t-class-mspp-interactivity-interactionrequest)  
The context for the interaction request.

_callback_  
Type: [System.Action](/patterns-practices/reference/interactionrequest-t-class-mspp-interactivity-interactionrequest)&lt;[T](/patterns-practices/reference/interactionrequest-t-class-mspp-interactivity-interactionrequest)&gt;  
The callback to execute when the interaction is completed.

## See Also

[InteractionRequest&lt;T&gt; Class](/patterns-practices/reference/interactionrequest-t-class-mspp-interactivity-interactionrequest)<br/>
[InteractionRequest&lt;T&gt; Members](/patterns-practices/reference/interactionrequest-t-members-mspp-interactivity-interactionrequest)<br/>
[Raise Overload](/patterns-practices/reference/interactionrequest-t-raise-method-mspp-interactivity-interactionrequest)<br/>
[Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace](/patterns-practices/reference/mspp-interactivity-interactionrequest-namespace)<br/>

# InteractionRequest(Of T).Raise Method (T, Action(Of T))

Fires the Raised event.

**Namespace:** [Microsoft.Practices.Prism.Interactivity.InteractionRequest](/patterns-practices/reference/mspp-interactivity-interactionrequest-namespace)

**Assembly:** Microsoft.Practices.Prism.Interactivity (in Microsoft.Practices.Prism.Interactivity.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Sub Raise ( 
	context As T,
	callback As Action(Of T)
)
```

### Parameters

_context_  
Type: [T](/patterns-practices/reference/interactionrequest-t-class-mspp-interactivity-interactionrequest)  
The context for the interaction request.

_callback_  
Type: [System.Action](/patterns-practices/reference/interactionrequest-t-class-mspp-interactivity-interactionrequest)(Of [T](/patterns-practices/reference/interactionrequest-t-class-mspp-interactivity-interactionrequest))  
The callback to execute when the interaction is completed.

## See Also

[InteractionRequest(Of T) Class](/patterns-practices/reference/interactionrequest-t-class-mspp-interactivity-interactionrequest)<br/>
[InteractionRequest(Of T) Members](/patterns-practices/reference/interactionrequest-t-members-mspp-interactivity-interactionrequest)<br/>
[Raise Overload](/patterns-practices/reference/interactionrequest-t-raise-method-mspp-interactivity-interactionrequest)<br/>
[Microsoft.Practices.Prism.Interactivity.InteractionRequest Namespace](/patterns-practices/reference/mspp-interactivity-interactionrequest-namespace)<br/>