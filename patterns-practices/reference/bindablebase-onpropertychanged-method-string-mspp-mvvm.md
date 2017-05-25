---
TOCTitle: 'OnPropertyChanged Method (String)'
Title: 'BindableBase.OnPropertyChanged Method (String) (Microsoft.Practices.Prism.Mvvm)'
ms:assetid: 'M:Microsoft.Practices.Prism.Mvvm.BindableBase.OnPropertyChanged(System.String)'
ms:mtpsurl: 'bindablebase-onpropertychanged-method-mspp-mvvm.md'
---



# BindableBase.OnPropertyChanged Method (String)
=======
BindableBase.OnPropertyChanged Method (String)
==================================================


Notifies listeners that a property value has changed.

**Namespace:** [Microsoft.Practices.Prism.Mvvm](mspp-mvvm-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


~~~c#
protected void OnPropertyChanged(
	string propertyName
)
~~~

~~~VB
'Declaration
Protected Sub OnPropertyChanged ( 
	propertyName As String
)
~~~


## Parameters

*propertyName*  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)

Name of the property used to notify listeners. This value is optional and can be provided automatically when invoked from compilers that support [CallerMemberNameAttribute](http://msdn2.microsoft.com/en-us/library/hh551816).
=======

protected void OnPropertyChanged( string propertyName )Protected Sub OnPropertyChanged ( propertyName As String )

### Parameters

propertyName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
Name of the property used to notify listeners. This value is optional and can be provided automatically when invoked from compilers that support [CallerMemberNameAttribute](http://msdn.microsoft.com/en-us/library/hh551816).


## See Also


[BindableBase Class](bindablebase-class-mspp-mvvm.md)
=======

[BindableBase Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mvvm.bindablebase)


[BindableBase Members](bindablebase-members-mspp-mvvm.md)

[OnPropertyChanged Overload](bindablebase-onpropertychanged-method-mspp-mvvm.md)

[Microsoft.Practices.Prism.Mvvm Namespace](mspp-mvvm-namespace.md)
