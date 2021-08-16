---
type: eventType
---
---
##### shortDescription
Fires when a file or several files are added to or removed from selection.

##### param(e): object
Information about the event.

##### field(e.component): DOMComponent
The widget's instance.

##### field(e.element): dxElement
The widget's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.model): object
The model data. Available only if Knockout is used.

##### field(e.value): Array<File>
Newly selected files.

##### field(e.previousValue): Array<File>
Previously selected files.

##### field(e.jQueryEvent): jQuery.Event
The jQuery event that caused the handler execution. Deprecated in favor of the **event** field.

##### field(e.jQueryEvent).deprecated
Use 'event' instead.

##### field(e.event): event
The event that caused the handler execution. It is a [dxEvent](/api-reference/50%20Common/Object%20Structures/dxEvent '/Documentation/ApiReference/Common/Object_Structures/dxEvent/') or a [jQuery.Event](https://api.jquery.com/Types/#Event) when you use jQuery.

---
Instead, you can use the [onValueChanged](/api-reference/10%20UI%20Widgets/dxFileUploader/1%20Configuration/onValueChanged.md '/Documentation/ApiReference/UI_Widgets/dxFileUploader/Configuration/#onValueChanged') option to handle the event.

#####See Also#####
#include common-link-handleevents