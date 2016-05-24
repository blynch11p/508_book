# Menus

Menus, like dialogs, rely on a few key principles to render them usable with the keyboard or screen reader.


The example below shows how to apply ARIA attributes to an unordered list element to give it the semantics screen readers need to announce it as a menu. It also demonstrates the JavaScript functionality you need to create the appropriate keyboard interaction.

1. You can move focus to the button by pressing tab.

2. Pressing enter with focus on the button opens the menu and moves focus to the first menu item.

3. Up and down arrows navigate the menu.

4. Escape closes the menu, returning focus to the button.

5. If actions were implemented, pressing enter on a menu item would perform the action.


```HTML
<!-- `menuExample` is a global object
  that contains the behavior
  methods for the menu interaction. -->
  
<div
  id="popupMenuExample"
  class="popupMenuWidget"
  onkeydown="(menuExample.onKeydown.bind(menuExample))(event)"
  onclick="(menuExample.onClickWidget.bind(menuExample))(event)">
  <a
    href="#"
    role="button"
    tabindex="0"
    aria-haspopup="true"
    aria-owns="actionsMenu"
    onclick="(menuExample.onClick.bind(menuExample))(event)">Actions &#9660;</a>
  <ul
    id="actionsMenu"
    role="menu"
    data-open="false"
    onmouseover="(menuExample.onMouseoverMenuItem.bind(menuExample))(event)"
    onclick="(menuExample.onClickMenuItem.bind(menuExample))(event)"
    style="display: none;">
    <li role="presentation">
      <a
        id="action_1"
        href="#"
        role="menuitem"
        tabindex="-1"
        data-active="false">Create</a>
    </li>
    <li role='presentation'>
      <a
        id="action_2"
        href="#"
        role="menuitem"
        tabindex="-1"
        data-active="false">Edit</a>
    </li>
    <li role='presentation'>
      <a
        id="action_3"
        href="#"
        role="menuitem"
        tabindex="-1"
        data-active="false">Delete</a>
    </li>
  </ul>
</div>

```