---
id: dxMultiView.Options.onItemRendered
type: function(e)
---
---
##### shortDescription
A function that is executed after a collection item is rendered.

##### param(e): ui/multi_view:ItemRenderedEvent
Information about the event.

##### field(e.component): {WidgetName}
The UI component's instance.

##### field(e.element): DxElement
#include common-ref-elementparam with { element: "UI component" }

##### field(e.itemData): Object
The current item's data.

##### field(e.itemElement): DxElement
#include common-ref-elementparam with { element: "item" }

##### field(e.itemIndex): Number
The current item's index.

##### field(e.model): any
Model data. Available only if you use Knockout.

---
<!-- Description goes here -->