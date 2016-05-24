# Labels

####Self-labeled

Some elements, like links and buttons with display text, label themselves. In this case, screen reader users and all other users can perceive the label.
```HTML
<div>
  <button>Submit</button>
</div>
```

####Using `<label>`

If we put text on the screen near an input such as a text field, the screen reader cannot reliably pick up on that visual association. It needs to be told which nearby text is the associated label. One way to do this is with the <strong>label</strong> element.
```HTML
<div>
    <label for="lastName">
      Last name:
    </label>
    <input id="lastName" type="text">
</div>
```

####Using 'aria-labelledby'

The HTML label works only for HTML inputs. If we make a control out of other elements by using ARIA, we can instead use <strong>aria-labelledby</strong>.
```HTML
<div>
  <div id="status">What's on your mind?</div>
  <div
    aria-labelledby="status"
    contenteditable
    id="composer"
    role="textbox">
  </div>
</div>
```
####Using 'aria-label'

In rare cases, the purpose of the input is visually obvious in context, but it's not obvious to someone using a screen reader. We can change that with <strong>aria-label</strong>.
```HTML
<div>
  <label>Telephone</label>
  <input id="one" type="number" aria-label="Area Code" />
  <input type="number" aria-label="Exchange Code" />
  <input type="number" aria-label="Line Number" />
</div>
```
or
```HTML
<button
  class="searchBtn" aria-label="search">
</button>
```
