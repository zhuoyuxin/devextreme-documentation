---
type: eventType
---
---
##### notUsedInTheme

##### shortDescription
Raised after a funnel item's selection state is changed in the UI or programmatically.

##### param(e): object
Information about the event.

##### field(e.component): DOMComponent
The widget's instance.

##### field(e.element): dxElement
The widget's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.model): object
The model data. Available only if you use Knockout.

##### field(e.item): dxFunnelItem
The [Item](/api-reference/20%20Data%20Visualization%20Widgets/dxFunnel/6%20Item '/Documentation/ApiReference/Data_Visualization_Widgets/dxFunnel/Item/') object.

---
Main article: [onSelectionChanged](/api-reference/20%20Data%20Visualization%20Widgets/dxFunnel/1%20Configuration/onSelectionChanged.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxFunnel/Configuration/#onSelectionChanged')

#####See Also#####
#include common-link-handleevents