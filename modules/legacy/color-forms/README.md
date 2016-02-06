
This module sets basic color styles for form elements on a light background.

## Input Fields

To style the color, background, and border styles for form fields, use the `.field` style.
This style works on text inputs, selects, and textareas.

```html
<label>Input</label>
<input type="text" class="block col-12 field">
<label>Select</label>
<select class="block col-12 field">
  <option value="1">One</option>
  <option value="2">Two</option>
  <option value="3">Three</option>
</select>
<label>Textarea</label>
<textarea class="block col-12 field"></textarea>
```

The `.field` style includes states for disabled and read-only fields, as well as success, warning, and error states.

```html
<label>Normal</label>
<input type="text" class="block col-12 field">
<label>Disabled</label>
<input type="text" class="block col-12 field" disabled value="This is disabled">
<label>Read Only</label>
<input type="text" class="block col-12 field" readonly value="This is read-only">
<label>Required</label>
<input type="text" class="block col-12 field" required>
<label>.is-focused</label>
<input type="text" class="block col-12 field is-focused">
<label>.is-disabled</label>
<input type="text" class="block col-12 field is-disabled">
<label>.is-read-only</label>
<input type="text" class="block col-12 field is-read-only">
<label>Success</label>
<input type="text" class="block col-12 field is-success">
<label>Warning</label>
<input type="text" class="block col-12 field is-warning">
<label>Error</label>
<input type="text" class="block col-12 field is-error">
```

