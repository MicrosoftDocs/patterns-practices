---
TOCTitle: '14: Upgrading from Prism Library 4.1'
Title: '14: Upgrading from Prism Library 4.1'
ms:assetid: 'e4ffe88e-a88c-42bd-a3e1-faac89ddb803'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Ff921144(v=PandP.40)'
---

# 14: Upgrading from Prism Library 4.1


This topic describes how to upgrade a solution from version 4.1 to version 5.0 of the Prism Library and the major changes that you should be aware of if you are considering upgrading to the 5.0 version.

## ViewModel Namespace and API Changes

The classes in the **Microsoft.Practices.Prism.ViewModel** namespace were made obsolete but still exist in Prism 5.0. You should use the classes from the **Microsoft.Practices.Prism**.**Mvvm** portable class library with **Microsoft.Practices.Prism**.**Mvvm** namespace. The **BindableBase** class replaces the **NotificationObject** class. If you need to implement **INotifyPropertyChanged** event, you should now use **BindableBase**, and use the **SetProperty** method in the property setter, which verifies if the value actually changed and if so, sets the backing field and raises the **PropertyChanged** event.

The 4.1 code was as follows:

```C#
  this.RaisePropertyChanged(() => this.WatchListItems);

  . . .

  if (value != this.timeInForce)
  {
    this.timeInForce = value;
    this.RaisePropertyChanged(() => this.TimeInForce);
  }
```

The 5.0 code is as follows:

```C#
  OnPropertyChanged(() => this.WatchListItems);

  . . . 

  SetProperty(ref this.timeInForce, value);
```

The Prism NuGet package will manage the changes to the new Prism assemblies.

If you decide to manually update your references, the **Microsoft.Practices.Prism.ViewModel** namespace now requires you to add the following references:

-  Microsoft.Practices.Prism.Mvvm
-  Microsoft.Practices.Prism.Mvvm.Desktop
-  Microsoft.Practices.Prism.ShareInterfaces

Alternatively you can add a NuGet reference to the Prism.Mvvm package if you only want the Prism.Mvvm APIs.

## EventAggregator Namespace and API Changes

The classes in the Events namespace were made obsolete but still exist in Prism 5.0. You should use the classes from the **Prism**.**PubSubEvents** portable class library with the **Prism**.**PubSubEvents** namespace. The **PubSubEvent** class replaces the **CompositePresentationEvent** class.

The Prism NuGet package will manage the changes to the new Prism assemblies.

If you decide to manually update your references, you will now need to add a reference to the following:

-  **Microsoft.Practices.Prism.PubSubEvents**

Alternatively you can insert a NuGet reference to the Prism.PubSubEvents NuGet package if you only want the Prism.PubSubEvents APIs.

## Regions Namespace API Changes

The **UriQuery** class was replaced with the **NavigationParameters** class and moved to the **Regions** namespace. Previous functionality remains the same, and support for object parameters was added. The **RequestNavigate** method defined in the interface **INavigateAsync** was updated to allow the passing of **NavigationParameters**.

## Commands Assembly Changes

The following classes from the **Commands** namespace were moved from the Prism library to the Prism.Mvvm portable class library:

-  **CompositeCommand**
-  **DelegateCommand**
-  **DelegateCommandBase**
-  **WeakEventHandlerManager**

For these classes you will only need to change your references to the Prism.Mvvm assembly.

The **CommandBehaviorBase** class was moved to the **Prism**.**Interactivity** namespace from the **Commands** namespace. The **ExecuteCommand** method now takes an object as a parameter.

The **ButtonBaseClickCommandBehavior** and **Click** classes were removed as they were obsolete last release.

## Prism NuGet Packages

The following signed Prism assemblies can now be referenced from NuGet:

-  [Prism 5.0](http://aka.ms/prism-wpf-prism50nuget)
-  [Prism.Composition 5.0](http://aka.ms/prism-wpf-prism50compositionnuget)
-  [Prism.Interactivity 5.0](http://aka.ms/prism-wpf-prism50interactivitynuget)
-  [Prism.PubSubEvents 1.0](http://aka.ms/prism-wpf-prism50pubsubeventsnuget)
-  [Prism.Mvvm 1.0](http://aka.ms/prism-wpf-prism50mvvmnuget)
-  [Prism.UnityExtensions 5.01](http://aka.ms/prism-wpf-prism50unityextensionsnuget)
-  [Prism.MefExtensions 5.0](http://aka.ms/prism-wpf-prism50mefextensionsnuget)

The [Prism NuGet package](http://aka.ms/prism-wpf-prism50nuget) will download the Prism.Composition, Prism.PubSubEvents, Prism.Mvvm, and Prism.Interactivity NuGet packages.

