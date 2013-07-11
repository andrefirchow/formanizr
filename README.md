# formanizr (beta)

> Small HTML/CSS framework to create nice cross-browser webforms.

## Stylish flexible and fluid HTML/CSS3 forms
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.

## See it in action ([DEMO](http://formanizr.firchow.net/beispiele.php))
Please check the [formanizr](http://formanizr.firchow.net) website for [demos](http://formanizr.firchow.net/beispiele.php) and [introductions](http://formanizr.firchow.net/dokumentation.php) (German language).

### Features
- fluid & responsive form-grid
- pure HTML/CSS - no graphics (optional icons), no JavaScript
- themeable - formanizr included 2 themes
- valid HTML5 markup

---

### Initialize

```html
<form class="formanizr">
    <!-- form content -->
</form>
```

### Options
There are several options you can set on the initialized formanizr-container or directly on a specific element (label, row, ...). All optional classes will prefixed with `fzr_`.

`code`

- Theme (`fzr_theme-dark`)
- Font size (`fzr_tiny`, `fzr_normal` (default) oder `fzr_big`)
- Position of legend inside a fieldset (`fzr_legend-inside`)
- Position of label (`fzr_right` and/or `fzr_label-top`)
- Font weight for label(s) (`fzr_label-bold`)

```html
<!-- initialize with options -->
<section class="formanizr fzr_tiny fzr_label-bold fzr_legend-inside fzr_theme-dark">
    <!-- form content -->
</section>
```
