---
id: DOMComponent.defaultOptions(rule)
---
---
##### shortDescription
Specifies the device-dependent default configuration properties for this component.

##### param(rule): Object
The component's default device properties.

##### field(rule.device): Device | function()
[Device parameters](/api-reference/50%20Common/Object%20Structures/device '/Documentation/ApiReference/Common/Object_Structures/device/').      
When you specify a function, get information about the current device from the argument. Return **true** if the properties should be applied to the device.

##### field(rule.options): Object
Options to be applied.

---
**defaultOptions** is a static method that the UI component class supports. The following code demonstrates how to specify default properties for all instances of the {WidgetName} UI component in an application executed on the desktop.

---
##### jQuery

    <!--JavaScript-->
    DevExpress.ui.dx{WidgetName}.defaultOptions({ 
        device: { deviceType: "desktop" },
        options: {
            // Here go the {WidgetName} properties
        }
    });

##### Angular

    <!--TypeScript-->
    import {WidgetName}, { Properties } from "devextreme/ui/{widget_name}";
    // ...
    export class AppComponent {
        constructor () {
            {WidgetName}.defaultOptions<Properties>({
                device: { deviceType: "desktop" },
                options: {
                    // Here go the {WidgetName} properties
                }
            });
        }
    }

##### Vue

    <template>
        <div>
            <Dx{WidgetName} id="{widgetName}1" />
            <Dx{WidgetName} id="{widgetName}2" />
        </div>
    </template>
    <script>
    import Dx{WidgetName} from "devextreme-vue/{widget-name}";
    import {WidgetName} from "devextreme/ui/{widget_name}";

    {WidgetName}.defaultOptions({
        device: { deviceType: "desktop" },
        options: {
            // Here go the {WidgetName} properties
        }
    });

    export default {
        components: {
            Dx{WidgetName}
        }
    }
    </script>


##### React

    import dx{WidgetName} from "devextreme/ui/{widget_name}";
    import {WidgetName} from "devextreme-react/{widget-name}";
     
    dx{WidgetName}.defaultOptions({
        device: { deviceType: "desktop" },
        options: {
            // Here go the {WidgetName} properties
        }
    });
        
    export default function App() {
        return (
            <div>
                <{WidgetName} id="{widgetName}1" />
                <{WidgetName} id="{widgetName}2" />
            </div>
        )
    }

---

You can also set rules for multiple device types:

---
##### jQuery

    <!--JavaScript-->
    DevExpress.ui.dx{WidgetName}.defaultOptions({ 
        device: [
            { deviceType: 'desktop' },
            { deviceType: 'tablet' },
            { deviceType: 'phone' },
        ],
        options: {
            // Here go the {WidgetName} properties
        }
    });

##### Angular

    <!--TypeScript-->
    import {WidgetName}, { Properties } from "devextreme/ui/{widget_name}";
    // ...
    export class AppComponent {
        constructor () {
            {WidgetName}.defaultOptions<Properties>({
                device: [
                    { deviceType: 'desktop' },
                    { deviceType: 'tablet' },
                    { deviceType: 'phone' },
                ],
                options: {
                    // Here go the {WidgetName} properties
                }
            });
        }
    }

##### Vue

    <template>
        <div>
            <Dx{WidgetName} id="{widgetName}1" />
            <Dx{WidgetName} id="{widgetName}2" />
        </div>
    </template>
    <script>
    import Dx{WidgetName} from "devextreme-vue/{widget-name}";
    import {WidgetName} from "devextreme/ui/{widget_name}";

    {WidgetName}.defaultOptions({
        device: [
            { deviceType: 'desktop' },
            { deviceType: 'tablet' },
            { deviceType: 'phone' },
        ],
        options: {
            // Here go the {WidgetName} properties
        }
    });

    export default {
        components: {
            Dx{WidgetName}
        }
    }
    </script>


##### React

    import dx{WidgetName} from "devextreme/ui/{widget_name}";
    import {WidgetName} from "devextreme-react/{widget-name}";
     
    dx{WidgetName}.defaultOptions({
        device: [
            { deviceType: 'desktop' },
            { deviceType: 'tablet' },
            { deviceType: 'phone' },
        ],
        options: {
            // Here go the {WidgetName} properties
        }
    });
        
    export default function App() {
        return (
            <div>
                <{WidgetName} id="{widgetName}1" />
                <{WidgetName} id="{widgetName}2" />
            </div>
        )
    }

---