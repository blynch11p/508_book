# ARIA States and Properties

Below is an alphabetical list of WAI-ARIA states and properties.

<strong>aria-activedescendant</strong><br>
Identifies the currently active descendant of a composite widget.

<strong>aria-atomic</strong><br>
Indicates whether assistive technologies will present all, or only parts of, the changed region based on the change notifications defined by the aria-relevant attribute. See related aria-relevant.

<strong>aria-autocomplete</strong><br>
Indicates whether user input completion suggestions are provided.

<strong>aria-busy (state)</strong><br>
Indicates whether an element, and its subtree, are currently being updated.

<strong>aria-checked (state)</strong><br>
Indicates the current "checked" state of checkboxes, radio buttons, and other widgets. See related aria-pressed and aria-selected.

<strong>aria-controls</strong><br>
Identifies the element (or elements) whose contents or presence are controlled by the current element. See related aria-owns.

<strong>aria-describedby</strong><br>
Identifies the element (or elements) that describes the object. See related
aria-labelledby.

<strong>aria-disabled (state)</strong><br>
Indicates that the element is perceivable but disabled, so it is not editable or otherwise operable. See related aria-hidden and aria-readonly.

<strong>aria-dropeffect</strong><br>
Indicates what functions can be performed when the dragged object is released on the drop target. This allows assistive technologies to convey the possible drag options available to users, including whether a pop-up menu of choices is provided by the application. Typically, drop effect functions can only be provided once an object has been grabbed for a drag operation as the drop effect functions available are dependent on the object being dragged.

<strong>aria-expanded (state)</strong><br>
Indicates whether the element, or another grouping element it controls, is currently expanded or collapsed.

<strong>aria-flowto</strong><br>
Identifies the next element (or elements) in an alternate reading order of content which, at the user's discretion, allows assistive technology to override the general default of reading in document source order.

<strong>aria-grabbed (state)</strong><br>
Indicates an element's "grabbed" state in a drag-and-drop operation.

<strong>aria-haspopup</strong><br>
Indicates that the element has a popup context menu or sub-level menu.

<strong>aria-hidden (state)</strong><br>
Indicates that the element and all of its descendants are not visible or perceivable to any user as implemented by the author. See related aria-disabled.

<strong>aria-invalid (state)</strong><br>
Indicates the entered value does not conform to the format expected by the application.

<strong>aria-label</strong><br>
Defines a string value that labels the current element. See related aria-labelledby.

<strong>aria-labelledby</strong><br>
Identifies the element (or elements) that labels the current element. See related aria-label and aria-describedby.

<strong>aria-level</strong><br>
Defines the hierarchical level of an element within a structure.

<strong>aria-live</strong><br>
Indicates that an element will be updated, and describes the types of updates the user agents, assistive technologies, and user can expect from the live region.

<strong>aria-multiline</strong><br>
Indicates whether a text box accepts multiple lines of input or only a single line.

<strong>aria-multiselectable</strong><br>
Indicates that the user may select more than one item from the current selectable descendants.

<strong>aria-orientation</strong><br>
Indicates whether the element and orientation is horizontal or vertical.

<strong>aria-owns</strong><br>
Identifies an element (or elements) in order to define a visual, functional, or contextual parent/child relationship between DOM elements where the DOM hierarchy cannot be used to represent the relationship. See related aria-controls.

<strong>aria-posinset</strong><br>
Defines an element's number or position in the current set of listitems or treeitems. Not required if all elements in the set are present in the DOM. See related aria-setsize.

<strong>aria-pressed (state)</strong><br>
Indicates the current "pressed" state of toggle buttons. See related aria-checked and aria-selected.

<strong>aria-readonly</strong><br>
Indicates that the element is not editable, but is otherwise operable. See related aria-disabled.

<strong>aria-relevant</strong><br>
Indicates what user agent change notifications (additions, removals, etc.) assistive technologies will receive within a live region. See related aria-atomic.

<strong>aria-required</strong><br>
Indicates that user input is required on the element before a form may be submitted.

<strong>aria-selected (state)</strong><br>
Indicates the current "selected" state of various widgets. See related aria-checked and aria-pressed.

<strong>aria-setsize</strong><br>
Defines the number of items in the current set of listitems or treeitems. Not required if all elements in the set are present in the DOM. See related aria-posinset.

<strong>aria-sort</strong><br>
Indicates if items in a table or grid are sorted in ascending or descending order.

<strong>aria-valuemax</strong><br>
Defines the maximum allowed value for a range widget.

<strong>aria-valuemin</strong><br>
Defines the minimum allowed value for a range widget.

<strong>aria-valuenow</strong><br>
Defines the current value for a range widget. See related aria-valuetext.

<strong>aria-valuetext</strong><br>
Defines the human readable text alternative of aria-valuenow for a range widget.

 ####[A detailed definition of each WAI-ARIA state and property](https://www.w3.org/TR/wai-aria/states_and_properties#state_prop_def)