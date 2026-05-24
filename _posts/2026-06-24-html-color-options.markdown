---
layout: post
title:  "Color Input Options"
date:   2026-06-24 10:00:00 -0400
categories: html
---

# Adding Color Options to Color Input

When using a color input, you can specify options by setting the `list` attribute to the id of a `<datalist>` that contains `<option>` tags.

```html
<input type="color" list="color-list" />
<datalist id="color-list">
  <option value="#3b82f6"></option>
  <option value="#000000"></option>
  <option value="#008000"></option>
  <option value="#ff0000"></option>
</datalist>
```

Then the options will appear with the dropdown.

![Color options](/assets/images/color-options.png)

See full implementation here: [Color option implementation](https://github.com/JavaKoala/home-calendar-react/pull/17)
