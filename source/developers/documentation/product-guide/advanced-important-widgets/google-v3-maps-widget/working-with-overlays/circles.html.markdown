---
old_url: circles.htm
title: "Circles"
active_menu_item: developers
class_name: developers
full_width: true
---


A Circle can be drawn on the Map with a radius as well as line and fill properties.

Below is some code that shows how to create a new line using [addCircle()](/developers/documentation/scripting-apis/client-api/widget-object-functions/advanced-maps/addcircle) . Don't forget that you can also create multiple overlays from any simple or complex array using the [populateWidget()](/developers/documentation/product-guide/advanced-important-widgets/google-v3-maps-widget/using-populatewidget) function.

    function handler_actionBtn11_onClick(mouseev){
        if (circleObj) {
            app.w('googleMapsAdvanced').removeOverlay(circleObj);
            circleObj = null;
        } else {
            var circle = [[41.878113, -87.629798], 200000, "Title Text"];
                circleObj = app.w('googleMapsAdvanced').
    (circle);
        }
    }
   

Refer to [addCircle()](/developers/documentation/scripting-apis/client-api/widget-object-functions/advanced-maps/addcircle) in the [Client API](/developers/documentation/scripting-apis/client-api/) section for full details on the function.
