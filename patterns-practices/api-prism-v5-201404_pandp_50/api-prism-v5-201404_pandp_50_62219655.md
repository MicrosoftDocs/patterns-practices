---
TOCTitle: CompositeCommand Members
Title: 'CompositeCommand Members (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Commands.CompositeCommand'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430760(v=PandP.50)'
---

Prism Class Library

CompositeCommand Members
========================

Include Protected Members
Include Inherited Members

The [CompositeCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.compositecommand) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430760.pubmethod(en-us,PandP.50).gif "Public method")
[CompositeCommand()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.compositecommand.)
Initializes a new instance of [CompositeCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.compositecommand).

![](https://msdn.microsoft.com/en-us/Gg430760.pubmethod(en-us,PandP.50).gif "Public method")
[CompositeCommand(Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.compositecommand.)
Initializes a new instance of [CompositeCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.compositecommand).

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430760.pubmethod(en-us,PandP.50).gif "Public method")
[CanExecute](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.compositecommand.canexecute(system.object))
Forwards [CanExecute(Object)](http://msdn2.microsoft.com/en-us/library/ms604093) to the registered commands and returns trueTruetruetrue (True in Visual Basic) if all of the commands return trueTruetruetrue (True in Visual Basic).

![](https://msdn.microsoft.com/en-us/Gg430760.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430760.pubmethod(en-us,PandP.50).gif "Public method")
[Execute](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.compositecommand.execute(system.object))
Forwards [Execute(Object)](http://msdn2.microsoft.com/en-us/library/ms604094) to the registered commands.

![](https://msdn.microsoft.com/en-us/Gg430760.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430760.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430760.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430760.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430760.protmethod(en-us,PandP.50).gif "Protected method")
[OnCanExecuteChanged](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.compositecommand.oncanexecutechanged)
Raises [CanExecuteChanged](http://msdn2.microsoft.com/en-us/library/ms523106) on the UI thread so every command invoker can requery [CanExecute(Object)](http://msdn2.microsoft.com/en-us/library/ms604093) to check if the [CompositeCommand](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.compositecommand) can execute.

![](https://msdn.microsoft.com/en-us/Gg430760.pubmethod(en-us,PandP.50).gif "Public method")
[RegisterCommand](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.compositecommand.registercommand(system.windows.input.icommand))
Adds a command to the collection and signs up for the [CanExecuteChanged](http://msdn2.microsoft.com/en-us/library/ms523106) event of it.

![](https://msdn.microsoft.com/en-us/Gg430760.protmethod(en-us,PandP.50).gif "Protected method")
[ShouldExecute](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.compositecommand.shouldexecute(system.windows.input.icommand))
Evaluates if a command should execute.

![](https://msdn.microsoft.com/en-us/Gg430760.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430760.pubmethod(en-us,PandP.50).gif "Public method")
[UnregisterCommand](https://msdn.microsoft.com/m:microsoft.practices.prism.commands.compositecommand.unregistercommand(system.windows.input.icommand))
Removes a command from the collection and removes itself from the [CanExecuteChanged](http://msdn2.microsoft.com/en-us/library/ms523106) event of it.

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430760.pubproperty(en-us,PandP.50).gif "Public property")
[RegisteredCommands](https://msdn.microsoft.com/p:microsoft.practices.prism.commands.compositecommand.registeredcommands)
Gets the list of all the registered commands.

Events
------

<span id="eventTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430760.pubevent(en-us,PandP.50).gif "Public event")
[CanExecuteChanged](https://msdn.microsoft.com/e:microsoft.practices.prism.commands.compositecommand.canexecutechanged)
Occurs when any of the registered commands raise [CanExecuteChanged](http://msdn2.microsoft.com/en-us/library/ms523106). You must keep a hard reference to the handler to avoid garbage collection and unexpected results. See remarks for more information.

See Also
--------

<span id="seeAlsoToggle"></span>
[CompositeCommand Class](https://msdn.microsoft.com/t:microsoft.practices.prism.commands.compositecommand)

[Microsoft.Practices.Prism.Commands Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.commands)
