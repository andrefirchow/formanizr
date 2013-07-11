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
There are several options you can set on the initialized formanizr-container or directly on a specific element (label, row, ...).

- Theme (_fzr_theme-dark_**)
- Font size (_fzr_tiny_**, _fzr_normal_** (default) oder _fzr_big_**)
- Position of legend inside a fieldset (_fzr_legend-inside_**)
- Position of label (_fzr_right_** and/or _fzr_label-top_**)
- Font weight for label(s) (_fzr_label-bold_**)

```html
<!-- initialize with options -->
<section class="formanizr fzr_tiny fzr_label-bold fzr_legend-inside fzr_theme-dark">
    <!-- form content -->
</section>
```
