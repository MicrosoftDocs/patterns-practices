---
TOCTitle: 'SetProperty(T) Method'
Title: 'BindableBase.SetProperty(T) Method (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.BindableBase.SetProperty\`\`1(\`\`0@,\`\`0,System.String)'
ms:mtpsurl: 'bindablebase-setproperty-t-method-mspp-mvvm.md'
---

# BindableBase.SetProperty&lt;T&gt; Method

Checks if a property already matches a desired value. Sets the property and notifies listeners only when necessary.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
protected virtual bool SetProperty<T>(
	ref T storage,
	T value,
	string propertyName = null
)
```

### Parameters

*storage*  
Type: T%  
Reference to a property with both getter and setter.

*value*  
Type: T  
Desired value for the property.

*propertyName* (Optional)  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
Name of the property used to notify listeners. This value is optional and can be provided automatically when invoked from compilers that support CallerMemberName.

## Type Parameters

*T*  
Type of the property.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
True if the value was changed, false if the existing value matched the desired value.


# BindableBase.SetProperty(Of T) Method

Checks if a property already matches a desired value. Sets the property and notifies listeners only when necessary.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Protected Overridable Function SetProperty(Of T) ( 
	ByRef storage As T,
	value As T,
	Optional propertyName As String = Nothing
) As Boolean
```

### Parameters

*storage*  
Type: T%  
Reference to a property with both getter and setter.

*value*  
Type: T  
Desired value for the property.

*propertyName* (Optional)  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
Name of the property used to notify listeners. This value is optional and can be provided automatically when invoked from compilers that support CallerMemberName.

## Type Parameters

*T*  
Type of the property.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
True if the value was changed, false if the existing value matched the desired value.

## See Also

[BindableBase Class](/patterns-practices/reference/bindablebase-class-mspp-mvvm)  
[BindableBase Members](/patterns-practices/reference/bindablebase-members-mspp-mvvm)  
[Microsoft.Practices.Prism.Mvvm Namespace](/patterns-practices/reference/mspp-mvvm-namespace)