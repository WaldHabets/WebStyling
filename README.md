# Sass Styling for HTML components
A small library containing various `.css` and `.scss` style sheets for re-use in projects.

# Defining you own styles

## Buttons

```scss
.my-button-class {
    @import button($my-button-color);
}
.my-flat-button-class {
    @import flat-button($my-button-color);
}
```