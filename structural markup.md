# Structural Markup

> [!info] ChatGPT
> Structural markup refers to the use of HTML tags to define the overall structure and layout of a webpage. Structural markup focuses more on the overall layout, rather than the meaning of individual content elements.

These are elements you can use to describe both headings and paragraphs.

## body, head and title

- `<body>`: everything inside this element is shown inside the main browser.
- `<head>`: this element comes before the head element but after the `<html>` element. This element hold information about your page.
- `<titile>`: the contents of the title element is shown either in the top of the browser or on the tab for that page.

## Headings

HTML has six level headings starting from `h1` which is used for main headings, `h2` for sub-headings, `h3` for sub-subheadings and all the way to `h6`.

```html
<h1>The Main Heading</h1>
<h2>This is a level 2 heading</h2>
<h3>This is a level 3 heading</h3>
<h4>This is a level 4 heading</h4>
<h5>This is a level 5 heading</h5>
<h6>This is a level 6 heading</h6>
```

## Paragraphs

The `<p>` element is used for paragraphs. If you surround your text with the opening and closing `<p>` tag, the browser will know that this text that’s being surrounded by the `<p>` element is a paragraph. By default, the browser will show each paragraph on a new line.

```html
<p>
  This text inside these tags will be considered a paragraph by the browser.
</p>
```

## Bold and Italic

```html
<p>This is how you make your text appear <b>bold</b></p>
<p>This is how you make your text appear <i>italic</i></p>
```

## Superscript and Subscript

The `<sup>` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 2$^2$.

```html
<p>
  On the 4<sup>th</sup> of September you will also learn more about
  E=MC<sup>2</sup>.
</p>
```

The `<sub>` element is used to contain characters that should be subscript. It is commonly used with footnotes or chemical formulas such as H$_{2}$O

```html
<p>
  The amount of CO<sub>2</sub> in the atmosphere grew by 2ppm in 2009<sub>
    1</sub
  >
</p>
```

## Line breaks and horizonal rules

The `<br>` will add a line break inside the middle of the paragraph.

```html
<p>
  Once upon <br />
  there was a boy called Shikiyama <br />
  He was bullied in school and hated by his parents
</p>
```

The `<hr />` element adds a horizontal rule between sections or elements.

```html
<h2>How to make potato chips</h2>
<hr />
<p>To make potato chips, first wash your potatoes</p>
```
