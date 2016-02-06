
This modules sets structural styles for base form elements, creating a consistent visual rhythm among forms
while allowing for color to be adjusted where needed.
These styles do not rely on markup structure and can be combined with
utilities to make fine-grained, contextual adjustments.
Form element styles are intended to be interoperable with all other utility styles.


## Inline Forms
By default, form elements follow browser defaults and display inline.
Note: the `.field` style is part of `basscss-color-forms`.

```html
<form>
  <label for="search">Search</label>
  <input id="search" type="text" class="field">
  <button class="btn btn-primary">Go</button>
</form>
```

## Stacked Forms

Use `.block`, `.col-12`, and other layout utilities to stack form elements and adjust margins.

```html
<form class="sm-col-6">
  <label>Email Address</label>
  <input type="text" class="block col-12 mb1 field">
  <label>Password</label>
  <input type="password" class="block col-12 mb1 field">
  <label>Select</label>
  <select class="block col-12 mb1 field">
    <option>Option 1</option>
    <option>Option 2</option>
    <option>Option 3</option>
    <option>Option 4</option>
    <option>Option 5</option>
  </select>
  <label class="block col-12 mb2">
    <input type="checkbox" checked>
    Remember me
  </label>
  <button type="submit" class="btn btn-primary">Sign In</button>
  <button type="reset" class="btn btn-primary black bg-gray">Cancel</button>
</form>
```
To adjust the color of forms, use the styles in `basscss-color-forms` and `basscss-color-forms-dark`.

