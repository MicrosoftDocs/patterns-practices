---
TOCTitle: 'OnPropertyChanged Method (String)'
Title: 'BindableBase.OnPropertyChanged Method (String) (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.BindableBase.OnPropertyChanged(System.String)'
ms:mtpsurl: 'bindablebase-onpropertychanged-method-mspp-mvvm.md'
---

# BindableBase.OnPropertyChanged Method (String)

Notifies listeners that a property value has changed.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mvvm(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax
```C#
protected void OnPropertyChanged(
	string propertyName
)
```
```VB
'Declaration
Protected Sub OnPropertyChanged ( 
	propertyName As String
)
```

### Parameters

*propertyName*  

Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)

Name of the property used to notify listeners. This value is optional and can be provided automatically when invoked from compilers that support [CallerMemberNameAttribute](http://msdn2.microsoft.com/en-us/library/hh551816).

## See Also
[BindableBase Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mvvm.bindablebase(v=pandp.50))

[BindableBase Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mvvm.bindablebase_members(v=pandp.50))

[OnPropertyChanged Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mvvm.bindablebase.onpropertychanged(v=pandp.50))

[Microsoft.Practices.Prism.Mvvm Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mvvm(v=pandp.50))


