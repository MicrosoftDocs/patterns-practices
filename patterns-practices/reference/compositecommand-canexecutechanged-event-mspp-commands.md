---
TOCTitle: CanExecuteChanged Event
Title: 'CompositeCommand.CanExecuteChanged Event (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'E:Microsoft.Practices.Prism.Commands.CompositeCommand.CanExecuteChanged'
ms:mtpsurl: 'compositecommand-canexecutechanged-event-mspp-commands.md'
---

# CompositeCommand.CanExecuteChanged Event

Occurs when any of the registered commands raise [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106). You must keep a hard reference to the handler to avoid garbage collection and unexpected results. See remarks for more information.

**Namespace:** [Microsoft.Practices.Prism.Commands](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
**Assembly:** Microsoft.Practices.Prism.Mvvm (in Microsoft.Practices.Prism.Mvvm.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax
public event EventHandler CanExecuteChangedPublic Event CanExecuteChanged As EventHandler
### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/xhb70ccc)
### Implements

[ICommand.CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106)

## Remarks

 When subscribing to the [CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106) event using code (not when binding using XAML) will need to keep a hard reference to the event handler. This is to prevent garbage collection of the event handler because the command implements the Weak Event pattern so it does not have a hard reference to this handler. An example implementation can be seen in the CompositeCommand and CommandBehaviorBase classes. In most scenarios, there is no reason to sign up to the CanExecuteChanged event directly, but if you do, you are responsible for maintaining the reference.

## Examples

 The following code holds a reference to the event handler. The myEventHandlerReference value should be stored in an instance member to avoid it from being garbage collected. EventHandler myEventHandlerReference = new EventHandler(this.OnCanExecuteChanged); command.CanExecuteChanged += myEventHandlerReference;

## See Also
[CompositeCommand Class](https://msdn.microsoft.com/library/microsoft.practices.prism.commands.compositecommand)

[CompositeCommand Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.commands.compositecommand)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.commands)
