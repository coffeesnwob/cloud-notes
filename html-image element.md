# Images

When building a site from scratch, it is a good practice to create a folder for all the images the site is using. Images on your site should:

- be relevant
- convey information
- convey the right mood
- be instantly recognisable
- fit the color palette.

To create an image in HTML, you use the `<img>` element. This is an empty element meaning it does not have the closing tag and this element has the following attribute:

1. [src](def/attributes#^fff13b) → this tells the browser where to find the image file
2. [alt](def/attributes#^fff13b) → this provides a text description of the image which describes the image when the image is not being displayed.
3. [title](def/attributes#^fff13b) → this provides additional information about the image.

The value used in the alt attribute should be an accurate description of the image so it can be understood by screen readers.

The syntax:

```html
<img
  src="images/red-car.png"
  alt="Red sports car"
  title="Red supra 4gt crusing in the highway"
/>
```

You can also specify the width and height of an image using `width` and `height` inside the `img` element.

```html
<img
  src="images/red-car.png"
  alt="Red sports car"
  title="Red supra 4gt crusing in the highway"
  width="250"
  height="300"
/>
```

## Tools for editing and saving images

1. Adobe Photoshop
2. Gimp
3. Canva

---

- [[Image-file-types]]
- [[figure-and-figcaption]]

[[html]]
[[attributes]]
[[block and inline]]
