---
EventForAction: ..\4 Events\selectAllValueChanged.md
default: null
type: function(e)
---
---
##### shortDescription
A function that is executed after the "Select All" check box's state changes. Applies only if [showCheckBoxesMode](/api-reference/10%20UI%20Widgets/dxTreeView/1%20Configuration/showCheckBoxesMode.md '/Documentation/ApiReference/UI_Widgets/dxTreeView/Configuration/#showCheckBoxesMode') is *"selectAll"* and [selectionMode](/api-reference/10%20UI%20Widgets/dxTreeView/1%20Configuration/selectionMode.md '/Documentation/ApiReference/UI_Widgets/dxTreeView/Configuration/#selectionMode') is *"multiple"*.

##### param(e): Object
Information about the event.

##### field(e.component): DOMComponent
The widget's instance.

##### field(e.element): dxElement
The widget's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.model): Object
The model data. Available only if Knockout is used.

##### field(e.value): Boolean
The "Select All" check box's new state.

---
#####See Also#####
- [onSelectionChanged](/api-reference/10%20UI%20Widgets/dxTreeView/1%20Configuration/onSelectionChanged.md '/Documentation/ApiReference/UI_Widgets/dxTreeView/Configuration/#onSelectionChanged')
- [Select Nodes](/concepts/05%20Widgets/TreeView/25%20Select%20Nodes '/Documentation/Guide/Widgets/TreeView/Select_Nodes/')