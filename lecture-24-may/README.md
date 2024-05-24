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

### What is CSS?

CSS stans for cascading style sheet. It says nothing really but it means that styling always cascades down through the css stylesheet. CSS goes from top to bottom so the structure in your css stylesheets matters.

### Three different ways to style your content.

#### Element styling

It is styling that targets a specific html element. Could be `<h1>` tag for instance. But remember, if you style this way _ALL_ the `<h1>` tags will get the same styling It's not very specific in other words.

```css
h1 {
  color: blue;
}
```

#### Class styling

Class styling is used when we ant to be much more specific on which elements
to style. There might be several of the same kind, but we are only interested in styling one of those. Then we use a css class.

```css
.some-class {
  background-color: blue;
  /* This styling will only apply to an element that has the specific class "some-class". */
}
```

A good thing to know about classes is that you can reuse them
as many times as you want.

#### Id styling

Works the same way as a class, you just use `#` instead. The convention here is that the id is unique,
it means you shouldn't reuse

```css
#some-id {
  background-color: yellow;
  /* This styling will only apply to an element that has the id of "some-id";. */
}
```
