---
TOCTitle: DelegateCommand Methods
Title: 'DelegateCommand Methods (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Commands.DelegateCommand'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430976(v=PandP.50)'
---

Prism Class Library

DelegateCommand Methods
=======================

Include Protected Members
Include Inherited Members

The [DelegateCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430976.pubmethod(en-us,PandP.50).gif "Public method")
[CanExecute()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.delegatecommand.canexecute)
Determines if the command can be executed.

![](https://msdn.microsoft.com/en-us/Gg430976.protmethod(en-us,PandP.50).gif "Protected method")
[CanExecute(Object)](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.delegatecommandbase.canexecute(system.object))
Determines if the command can execute with the provided parameter by invoking the [Func&lt;(Of &lt;(T, TResult&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/bb549151) supplied during construction.

(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase).)
![](https://msdn.microsoft.com/en-us/Gg430976.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430976.pubmethod(en-us,PandP.50).gif "Public method")
[Execute()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.delegatecommand.execute)
Executes the command.

![](https://msdn.microsoft.com/en-us/Gg430976.protmethod(en-us,PandP.50).gif "Protected method")
[Execute(Object)](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.delegatecommandbase.execute(system.object))
Executes the command with the provided parameter by invoking the [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8) supplied during construction.

(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase).)
![](https://msdn.microsoft.com/en-us/Gg430976.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430976.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg430976.static(en-us,PandP.50).gif "Static member")
[FromAsyncHandler(Func&lt;(Of &lt;(Task&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.delegatecommand.fromasynchandler(system.func%7bsystem.threading.tasks.task%7d))
Factory method to create a new instance of [DelegateCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand) from an awaitable handler method.

![](https://msdn.microsoft.com/en-us/Gg430976.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg430976.static(en-us,PandP.50).gif "Static member")
[FromAsyncHandler(Func&lt;(Of &lt;(Task&gt;)&gt;), Func&lt;(Of &lt;(Boolean&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.delegatecommand.fromasynchandler(system.func%7bsystem.threading.tasks.task%7d%2csystem.func%7bsystem.boolean%7d))
Factory method to create a new instance of [DelegateCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand) from an awaitable handler method.

![](https://msdn.microsoft.com/en-us/Gg430976.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430976.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430976.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430976.protmethod(en-us,PandP.50).gif "Protected method")
[OnCanExecuteChanged](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.delegatecommandbase.oncanexecutechanged)
Raises [CanExecuteChanged](http://msdn2.microsoft.com/en-us/library/ms523106) on the UI thread so every command invoker can requery [CanExecute(Object)](http://msdn2.microsoft.com/en-us/library/ms604093).

(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase).)
![](https://msdn.microsoft.com/en-us/Gg430976.protmethod(en-us,PandP.50).gif "Protected method")
[OnIsActiveChanged](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.delegatecommandbase.onisactivechanged)
This raises the [IsActiveChanged](https://msdn.microsoft.com/e:microsoft.practices.prism.commands.delegatecommandbase.isactivechanged) event.

(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase).)
![](https://msdn.microsoft.com/en-us/Gg430976.pubmethod(en-us,PandP.50).gif "Public method")
[RaiseCanExecuteChanged](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.delegatecommandbase.raisecanexecutechanged)
Raises [CanExecuteChanged](https://msdn.microsoft.com/e:microsoft.practices.prism.commands.delegatecommandbase.canexecutechanged) on the UI thread so every command invoker can requery to check if the command can execute.
Remarks
-------

<span id="remarksToggle"></span>Note that this will trigger the execution of [CanExecute(Object)](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.delegatecommandbase.canexecute(system.object)) once for each invoker.

(Inherited from [DelegateCommandBase](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommandbase).)
![](https://msdn.microsoft.com/en-us/Gg430976.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)

See Also
--------

<span id="seeAlsoToggle"></span>
[DelegateCommand Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.delegatecommand)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
