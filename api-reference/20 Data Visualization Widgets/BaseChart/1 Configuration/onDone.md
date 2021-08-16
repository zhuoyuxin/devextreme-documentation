---
EventForAction: ..\4 Events\done.md
default: null
type: function(e)
---
---
##### notUsedInTheme

##### shortDescription
A function that is executed when all series are ready.

##### param(e): Object
Information about the event.

##### field(e.component): DOMComponent
The widget's instance.

##### field(e.element): dxElement
The widget's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.model): Object
The model data. Available only if you use Knockout.

---
#####See Also#####
- [getAllSeries()](/api-reference/20%20Data%20Visualization%20Widgets/BaseChart/3%20Methods/getAllSeries().md '{basewidgetpath}/Methods/#getAllSeries')
- [getSeriesByName(seriesName)](/api-reference/20%20Data%20Visualization%20Widgets/BaseChart/3%20Methods/getSeriesByName(seriesName).md '{basewidgetpath}/Methods/#getSeriesByNameseriesName')
- [getSeriesByPos(seriesIndex)](/api-reference/20%20Data%20Visualization%20Widgets/BaseChart/3%20Methods/getSeriesByPos(seriesIndex).md '{basewidgetpath}/Methods/#getSeriesByPosseriesIndex')