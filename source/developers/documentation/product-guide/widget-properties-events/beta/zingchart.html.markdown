---
old_url: zingchart.htm
title: "Zingchart"
active_menu_item: developers
class_name: developers
full_width: true
---


The Zing Chart Widget should be considered to be in a Beta state until mention of it is removed from the documentation and is accessible from the Advanced section of the Toolbox

Zingchart can be configured to show different chart types and optimised for Mobile apps. See [Zing Charts](/developers/documentation/product-guide/advanced-important-widgets/zing-charts/) for more information

<table>
<tr>
<td width="137">
<a id="layout"> </a> <b>General</b>

</td>
<td width="23">
</td>
<td width="782">
</td>
</tr>


<tr>
<td width="138">
Widget Class

</td>
<td width="21">
</td>
<td width="782">
Internal class name of the widget.- Zingchart

</td>
</tr>
<tr>
<td width="138">
Name

</td>
<td width="21">
</td>
<td width="782">
This is the Widget name that is displayed when references are made to the Widget. You can choose any name that includes alphanumeric characters.

</td>
</tr>
<tr>
<td width="138">
Multiserial

</td>
<td width="21">
</td>
<td width="782">
Brings up dialog to set data series with various data.

</td>
</tr>
<tr>
<td width="138">
Renderer

</td>
<td width="21">
</td>
<td width="782">
auto(default)/html5/canvas/svg/vml.  Select the specific rendering for your charts if required.

</td>
</tr>
<tr>
<td width="138">
Full Settings

</td>
<td width="21">
</td>
<td width="782">
  Access the Zing Chart wizard to populate your charts. See <a href="adding_data_using_zingchart_wi.htm">Adding Data using ZingChart Wizard</a>

</td>
</tr>
<tr>
<td width="138">
Hide Context Menu
</td>
<td width="21">
</td>
<td width="782">
  True/False(default). Set to True to hide the context menu for Native Apps.

</td>
</tr>
</table>
<table>
<tr>
<td width="137">
<a id="layout"> </a> <b>Layout</b>

</td>
<td width="23">
</td>
<td width="782">
</td>
</tr>
<tr>
<td width="137">
X

</td>
<td width="23">
</td>
<td width="782">
Number of pixels from the left edge of the Page.

</td>
</tr>
<tr>
<td width="137">
Y

</td>
<td width="23">
</td>
<td width="782">
Number of pixels from the top edge of the Page.

</td>
</tr>
<tr>
<td width="137">
Sizes

</td>
<td width="23">
</td>
<td width="782">
  Where you can set the Width and Height of the widget. If a widget is within a Container in Vertical or Horizontal mode, then the widget can also be made to change size in response to the size of the display width and height See <a href="/developers/documentation/product-guide/content-and-app-layout/responsive-adaptive-fluid-design/sizes-property-dialog">'Sizes' Property Dialog</a>

</td>
</tr>
<tr>
<td width="137">
Repeat

</td>
<td width="23">
</td>
<td width="782">
  If set to True, this displays the Widget on either all pages except ones you specify in a list or only on pages you choose from a list.  Find out more about this in <a href="/developers/documentation/product-guide/content-and-app-layout/editing-and-laying-out-reference/repeating-widgets-across-multi">Repeating Widgets Across Multiple Pages</a> .

</td>
</tr>
<tr>
<td width="137">
Z-Index

</td>
<td width="23">
</td>
<td width="782">
A number that indicates the imaginary layer that the Widget is in. If you imagine several Widgets all placed over one another, the top-most Widget has the highest Z-Index and the bottom most Widget has the lowest. You can adjust the Z-Index by changing the value. You can also use the right-click menu to adjust these in a friendlier way.

</td>
</tr>
<tr>
<td width="137">
Anchors

</td>
<td width="23">
</td>
<td width="782">
  This is used in conjunction with "Docked" App Pages. You can use this to allows a Widget's X, Y, Width and Height to be automatically altered as the browser window is resized. See <a href="/developers/documentation/product-guide/content-and-app-layout/editing-and-laying-out-reference/widget-anchoring">Docking & Anchoring</a> .

</td>
</tr>
<tr>
<td width="137">
Align in Container

</td>
<td width="23">
</td>
<td width="782">
Left/Center/Right. Set as required to align the widget within its parent container

</td>
</tr>

</table>
<table>
<tr>
<td width="135">
<a id="behavior"> </a> <b>Behavior</b>

</td>
<td width="25">
</td>
<td width="782">
</td>
</tr>
<tr>
<td width="135">
Drag and Drop

</td>
<td width="25">
</td>
<td width="782">
If set to true, the user is able to drag and drop the widget with the mouse at run time

</td>
</tr>
<tr>
<td width="135">
Resizing

</td>
<td width="25">
</td>
<td width="782">
Disable/Enable. Set to True to allow the widget to be resized at Runtime. Configurable Max/Min Width and Height, Right & Bottom, Top & Left or All

</td>
</tr>
<tr>
<td width="135">
Visible

</td>
<td width="25">
</td>
<td width="782">
Set to False if you want the Widget to appear hidden by default. You would use Javascript to override this at a later stage.

</td>
</tr>
<tr>
<td width="135">
Enable

</td>
<td width="25">
</td>
<td width="782">
Set to false to leave the Widget visible but to prevent any user interaction

</td>
</tr>
<tr>
<td width="135">
</td>
<td width="25">
</td>
<td width="782">
</td>
</tr>
</table>
<table>
<tr>
<td width="135">
<a id="data"> </a> <b>Data</b>

</td>
<td width="25">
</td>
<td width="782">
</td>
</tr>
<tr>
<td width="135">
View

</td>
<td width="25">
</td>
<td width="782">
Select the view to use

</td>
</tr>
<tr>
<td width="135">
Fields

</td>
<td width="25">
</td>
<td width="782">
  This property is used to allow you to set which data fields are taken from the View and used in the Widget. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/fields/">Fields</a> section for more details.

</td>
</tr>
<tr>
<td width="135">
Group By

</td>
<td width="25">
</td>
<td width="782">
  This allows you to Group data within a View in the same way you would with a SQL statement. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/fiieldsgroup-by">Group By</a> section for more details.

</td>
</tr>
<tr>
<td width="135">
Order By

</td>
<td width="25">
</td>
<td width="782">
  Specifies the order in which data is presented to the Widget.  Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/order-by">Order By</a> section for more details.

</td>
</tr>
<tr>
<td width="135">
Filter

</td>
<td width="25">
</td>
<td width="782">
This is a global, static filter that can be defined for each View in your App.

</td>
</tr>
<tr>
<td width="135">
Drill Filter

</td>
<td width="25">
</td>
<td width="782">
  This property controls the Drill Down filter that is set when a Widget is clicked on whose Broadcast property is set to True. You will be shown the Expression Editor and you can specify the precise condition that should be applied to the View that the Widget is connected to. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/drill-filter">Drill Filter</a> section for more details.

</td>
</tr>
<tr>
<td width="135">
Broadcast

</td>
<td width="25">
</td>
<td width="782">
  Indicates whether a click action on a Widget should trigger a Drill Down on any other Widgets that a) share the same Data Source and b) whose Listen property is set. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/broadcast">Broadcast</a> section for more details.

</td>
</tr>
<tr>
<td width="135">
Listen

</td>
<td width="25">
</td>
<td width="782">
  This indicates whether the Widget should react to a Drill Down action on a common View. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/listen">Listen</a> section for more details.

</td>
</tr>
<tr>
<td width="135">
Reset Filter

</td>
<td width="25">
</td>
<td width="782">
  Indicates whether a Drill Down on the Widget should reset the View's filter or whether it should add to the existing filter. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/reset-filter">Reset Filter</a> section for more details.

</td>
</tr>
<tr>
<td width="135">
Drill Type

</td>
<td width="25">
</td>
<td width="782">
  This indicates how a Widget should behave when it is clicked on and results in a Drill Down operation. See <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/drill-type">Drill Type</a>.

</td>
</tr>
<tr>
<td width="135">
Auto Load

</td>
<td width="25">
</td>
<td width="782">
Set to true to automatically fetch data from assigned view.

</td>
</tr>
</table>
<table>
<tr>
<td width="150">
<a id="style"> </a> <b>Style</b>

</td>
<td width="10">
</td>
<td width="782">
</td>
</tr>
<tr>
<td width="150">
Opacity

</td>
<td width="10">
</td>
<td width="782">
This % value specifies the transparency of the Widget.

</td>
</tr>
<tr>
<td width="150">
Margin

</td>
<td width="10">
</td>
<td width="782">
  Used to specify the margin around a widget when the parent container is in Relative Mode. See <a href="/developers/documentation/product-guide/content-and-app-layout/introduction/setting-a-margin">Setting a Margin</a>

</td>
</tr>
<tr>
<td width="150">
Box Sizing

</td>
<td width="10">
</td>
<td width="782">
content-box/border-box. Content-box - The padding or border of the element are laid out and drawn outside the specified width and height. Border-box -The padding or border element is laid out and drawn inside the specified width and height.

</td>
</tr>
<tr>
<td width="150">
Border

</td>
<td width="10">
</td>
<td width="782">
Specified the line width/style and colour of the border surrounding the Widget.

</td>
</tr>
<tr>
<td width="150">
BG Color

</td>
<td width="10">
</td>
<td width="782">
This specifies a default background color of the App. .

</td>
</tr>
<tr>
<td width="150">
Custom CSS Classes

</td>
<td width="10">
</td>
<td width="782">
  Where you define your CSS Style to customise your widgets  See also <a href="/developers/documentation/product-guide/advanced-features/custom-css-classes/">Custom CSS Classes</a>

</td>
</tr>
<tr>
<td width="150">
Widget Style

</td>
<td width="10">
</td>
<td width="782">
  This refers to the <a href="/developers/documentation/product-guide/content-and-app-layout/introduction/themes-styles/themesmanage">Theme entry</a> that should be used to set the Widget's default appearance. Once a Theme Style has been selected, individual components such as Font and Colors can be Set to False if you want the Widget to appear hidden by default.

</td>
</tr>
</table>

<table>
<tr>
<td width="148">
  <strong>Supported Events:</strong>

</td>
<td width="15">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
  <a href="/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/mouse-events">Mouse Events</a>

</td>
<td width="15">
</td>
<td width="128">
  <a href="/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/data-events">Data Events</a>

</td>
</tr>
<tr>
<td width="148">
On Click

</td>
<td width="15">
</td>
<td width="128">
onComplete

</td>
</tr>
<tr>
<td width="148">
On Double Click

</td>
<td width="15">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Mouse Down

</td>
<td width="15">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Mouse Up

</td>
<td width="15">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Mouse Enter

</td>
<td width="15">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Mouse Leave

</td>
<td width="15">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Drag Start

</td>
<td width="15">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Drag Stop

</td>
<td width="15">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Resize Start

</td>
<td width="15">
</td>
<td width="128">
</td>
</tr>
<tr>
<td width="148">
On Resize Stop

</td>
<td width="15">
</td>
<td width="128">
</td>
</tr>
</table>

## See Also

 - [Zing Charts](/developers/documentation/product-guide/advanced-important-widgets/zing-charts/)
 - [Mouse Events](/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/mouse-events)
 - [Data Events](/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/data-events)

