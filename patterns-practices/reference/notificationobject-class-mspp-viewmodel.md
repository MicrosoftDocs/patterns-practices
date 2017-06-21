---
TOCTitle: NotificationObject Class
Title: 'NotificationObject Class (Microsoft.Practices.Prism.ViewModel)'
ms:assetid: 'T:Microsoft.Practices.Prism.ViewModel.NotificationObject'
ms:mtpsurl: 'notificationobject-class-mspp-viewmodel.md'
---

# NotificationObject Class

Base class for items that support property notification.

**Namespace:** [Microsoft.Practices.Prism.ViewModel](/patterns-practices/reference/mspp-viewmodel-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
[SerializableAttribute]
[ObsoleteAttribute("Please use Prism.Mvvm.BindableBase")]
public abstract class NotificationObject : INotifyPropertyChanged
```
```VB
'Declaration
<SerializableAttribute>
<ObsoleteAttribute("Please use Prism.Mvvm.BindableBase")> 
Public MustInherit Class NotificationObject
	Implements INotifyPropertyChanged
```

## Remarks

 This class provides basic support for implementing the [INotifyPropertyChanged](http://msdn.microsoft.com/en-us/library/ms133020) interface and for marshalling execution to the UI thread.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  Microsoft.Practices.Prism.ViewModel.NotificationObject

## See Also

[NotificationObject Members](/patterns-practices/reference/notificationobject-class-mspp-viewmodel)  
[Microsoft.Practices.Prism.ViewModel Namespace](/patterns-practices/reference/mspp-viewmodel-namespace)  
