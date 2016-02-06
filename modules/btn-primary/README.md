
Solid button color style for use with the `.btn` base style.

```html
<div class="mb1">
  <button class="btn btn-primary">Button</button>
  <a href="#!" class="btn btn-primary">Link Button</a>
  <input type="button" class="btn btn-primary" value="Input Button">
</div>
```

By default, `.btn-primary` has white text on a blue background.

Adjust the default colors using the `--button-color` and `--button-background-color` custom properties.

```css
:root {
  --button-color: black;
  --button-background-color: silver;
}
```

Use other color utilities to handle one-off exceptions.

```html
<button class="btn btn-primary mb1 bg-blue">Button</button>
<button class="btn btn-primary mb1 bg-black">Button</button>
<button class="btn btn-primary mb1 black bg-gray">Button</button>
<button class="btn btn-primary mb1 black bg-silver">Button</button>
<button class="btn btn-primary mb1 black bg-aqua">Button</button>
<button class="btn btn-primary mb1 bg-navy">Button</button>
<button class="btn btn-primary mb1 bg-teal">Button</button>
<button class="btn btn-primary mb1 bg-green">Button</button>
<button class="btn btn-primary mb1 bg-olive">Button</button>
<button class="btn btn-primary mb1 bg-lime">Button</button>
<button class="btn btn-primary mb1 black bg-yellow">Button</button>
<button class="btn btn-primary mb1 bg-orange">Button</button>
<button class="btn btn-primary mb1 bg-red">Button</button>
<button class="btn btn-primary mb1 bg-fuchsia">Button</button>
<button class="btn btn-primary mb1 bg-purple">Button</button>
<button class="btn btn-primary mb1 bg-maroon">Button</button>
<button class="btn btn-primary mb1 black bg-darken-1">Button</button>
<button class="btn btn-primary mb1 black bg-darken-2">Button</button>
<button class="btn btn-primary mb1 black bg-darken-3">Button</button>
<button class="btn btn-primary mb1 black bg-darken-4">Button</button>
```


