# Basscss Responsive Border

Responsive border utilities module for Basscss - http://basscss.com

## Prefix Naming Convention
These styles follow the same breakpoint prefix convention as other Basscss modules.

<div class="overflow-scroll">
  <table class="mb2 table-light overflow-hidden border rounded">
    <thead class="bg-darken-1">
      <tr> <th>Prefix</th> <th>Description</th> </tr>
    </thead>
    <tbody>
      <tr> <td>(no prefix)</td> <td>Not scoped to a breakpoint</td> </tr>
      <tr> <td>sm-</td> <td>--breakpoint-sm (default: min-width 40em)</td> </tr>
      <tr> <td>md-</td> <td>--breakpoint-md (default: min-width 52em)</td> </tr>
      <tr> <td>lg-</td> <td>--breakpoint-lg (default: min-width 64em)</td> </tr>
    </tbody>
  </table>
</div>

## Example

```html
<div class="sm-border-top md-border-none lg-border-left">I'll have a small border on small viewports, no border on medium viewports, and a left border on large viewports!</div>
<div class="md-rounded lg-circle">I'm rounded on medium viewports and a circle on large viewports!</div>
```
