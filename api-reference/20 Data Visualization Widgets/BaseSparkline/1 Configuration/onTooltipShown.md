---
EventForAction: ..\4 Events\tooltipShown.md
default: null
type: function(e)
---
---
##### notUsedInTheme

##### shortDescription
A handler for the **tooltipShown** event.

##### param(e): Object
Information about the event.

##### field(e.component): DOMComponent
The widget's instance.

##### field(e.element): dxElement
The widget's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.model): Object
The model data. Available only if you use Knockout.

---
The sparkline's tooltip appears when a user hovers the mouse cursor over it. 

When a tooltip appears, you can perform specific actions by handling the **tooltipShown** event. To do this, implement a handling function and assign it to this option. When implementing this function, use the object passed to it as its parameter. This object will provide you with the widget instance and its container.