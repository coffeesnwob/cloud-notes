## Attributes

Attributes provide additional information about the contents of an element and they appear inside an opening tag.

## The Syntax

![[attribute-syntax.svg]]

- **Attribute name** indicates what kind of extra information you are supplying about the element’s content.
- **Attribute value** is the information or setting for the attribute.

## attribute name, value and description

| name    | value                                                                                   | description                                                                                                                                                                                          |
| ------- | --------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| lang    | `"en"`, `"es"`, `"fr"` etc.                                                             | the `lang` attribute specifies the language of the content in an element. It helps assistive technologies like screen readers and search engines understand the language context.                    |
| cite    | `"https://www.example.org"`                                                             | the cite attribute is used to reference the source of a quotation or citation. It’s typically used within the `<blockquote>`, `<q>`, or `<cite>` tags to indicate the origin of the quoted material. |
| title   | the value is the abbr or acronym you are specifying in full term                        | the `title` attribute is used with `abbr` element and its value specify the acronym or abbreviation in full term                                                                                     |
| href    | `“https://www.imdb.com”`                                                                | they value of this attribute is the page you want to link to.                                                                                                                                        |
| id      |                                                                                         | this is a unique identifier and its value must be used once per id attribute used in your page.                                                                                                      |
| target  | `_blank`                                                                                | opens a link in a new window                                                                                                                                                                         |
| src     | `"images/red-car.png"`, this will usually be a [relative url](html-links#Relative URL). | this tells the browser where it can find the image file                                                                                                                                              |
| alt     | `"red new mordel of supra m5"`                                                          | this provides a text description of the image which describes the image when the image is not being displayed.                                                                                       |
| title   | “new sports version of supra in red color”                                              | this provides additional information about the image.                                                                                                                                                |
| scope   | `"col"`, `"row"`                                                                        | indicates whether it is a heading for a column or a row                                                                                                                                              |
| colspan | `"5"`, value is a number of column span                                                 | indicated how many columns that cell should run across.                                                                                                                                              |
| rowspan | `"2"`, value is a number of row span                                                    | indicates how many rows a cell should span down the table.                                                                                                                                           |

^fff13b

---

[[html]]
[[html-forms]]
[[html-image element]]
[[html-links]]
[[html-structure]]
[[html-tables]]
[[linking the same page]]
[[semantic markup]]
[[structural markup]]