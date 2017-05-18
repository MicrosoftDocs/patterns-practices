---
TOCTitle: GetView Method
Title: 'IRegion.GetView Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegion.GetView(System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405982(v=PandP.50)'
---

Prism Class Library

IRegion..::.GetView Method
==========================

Returns the view instance that was added to the region using a specific name.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>Object GetView( string viewName )Function GetView ( viewName As String ) As Object
#### Parameters

viewName  
Type: [System..::.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The name used when adding the view to the region.

#### Return Value

Type: [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
Returns the named view or nullNothingnullptra null reference (Nothing in Visual Basic) if the view with viewName does not exist in the current region.

See Also
--------

<span id="seeAlsoToggle"></span>
[IRegion Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion)

[IRegion Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.iregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
