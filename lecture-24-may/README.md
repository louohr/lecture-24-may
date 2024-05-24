# Repetition of HTML and CSS

<details>
<summary>Table of contents</summary>
- [Semantics](#semantics)
</details>

## HTML Repetition

### Semantics

## CSS Repetition

### CSS syntax

<figure>
    <img src="./images/img_selector.gif">
</figure>

- **Selector** this targets the element that
  we want to style. Be specific here, the more
  the merrier.

- **Declaration:** It's a combination of a
  property and value.

- **\*Property:** The specific styling that we want to apply
  to the element specified by the selector. Could be `background-color`, `margin`, `padding` and so on.

- **Value:** It's the value that we give to the property and is the thing that is visible on the webpage. For instance, the color red for the background color: `background-color: red`

The syntax for css looks like this:

```css
selector {
  css-rule: value;
}
```

Let's look a the selector syntax:

```css
/* Element selector */
h1 {
}

/* class selector, using period ( . ) */
.some-class {
}

/* id selector, using ( # ) */
#some-id {
  /* your css rules */
}
```
