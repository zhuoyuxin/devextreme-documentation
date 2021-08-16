---
##### shortDescription
Sets the argument axis' start and end values.

##### param(startValue): Number|Date|String
A new start value.

##### param(endValue): Number|Date|String
A new end value.

---
This function can be used when implementing [zooming](/concepts/05%20Widgets/zz%20Common/10%20Data%20Visualization%20Widgets/90%20Charts%20-%20End-User%20Interaction/6%20Zooming%20and%20Scrolling '/Documentation/Guide/Widgets/Common/Data_Visualization_Widgets/Charts_-_End-User_Interaction/Zooming_and_Scrolling/') for your chart. If your chart is integrated with the **RangeSelector** widget, call the **zoomArgument** function when the range selector's selected range is changed. Pass the start and end values of the range selector's selected range as the corresponding parameters of the function.

When the chart's [adjustOnZoom](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/1%20Configuration/adjustOnZoom.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Configuration/#adjustOnZoom') option is set to _true_, the maximum and minimum values of the chart's value axis are changed to correspond to the maximum and minimum values of the chart's series. This is required to remove the empty area in the chart that may appear when changing the maximum and minimum values of the argument axis. To prevent value axis adjustment in response to argument axis boundary changes, set the **adjustOnZoom** option to _false_.

#include common-demobutton with {
    url: "https://js.devexpress.com/Demos/WidgetsGallery/Demo/Charts/ZoomingAndScrollingAPI/jQuery/Light/"
}

#####See Also#####
#include common-link-callmethods