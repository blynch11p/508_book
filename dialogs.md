# Dialogs

Dialogs are a little bit trickier to make accessible, but with a few key principles, they can be made keyboard navigable and usable with screen readers.

1. Screen Readers will announces that a dialog is opened and the name of the dialog, because we have a role of ```dialog``` with a label associated using <strong>aria-labelledby</strong>.

2. When the dialog opens, focus lands in the first focus-able element in the dialog.

3. Tabbing keeps focus within the dialog. Note that you have to write code to restrict the tab sequence to the dialog.

4. Closing the dialog places focus back on the source button.

5. Pressing the ```esc``` key closes the dialog and places the focus back on the source button. Note that for widgets like typeaheads, pressing ```esc``` should close the typeahead and not the dialog.


Note that if you have textual content in the dialog besides labels, you should associate it with an <strong>aria-describedby</strong> to the right input field so it gets announced when you tab to the input field.

```HTML
<button onclick='showHideDialog(event)' id="sourceLink">
    Show Dialog
</button>
<div id="overlay" onkeydown='closeDialog(event)'>
  <div
    id="container"
    role='dialog'
    aria-labelledby='dialog-title'>
      <h2 id='dialog-title'>Shipping Address</h2>
      <div id="content">
        <div>
          <label for="inputfield">Name </label>
          <input
            type="text"
            name="Name field"
            id="inputfield" />
        </div>
      </div>
      <div>
        <button
          onclick='showHideDialog(event)'
          id="submitButton">
            Submit
        </button>
        <button
          onclick='showHideDialog(event)'
          id="closeButton">
            Close
        </button>
      </div>
```


