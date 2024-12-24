# HTML Links

To create links, you use the `<a>` element and users can click on anything between the opening `<a>` tag and the closing `</a>` tag. In order for the `<a>` element to work as intended, you use the [href attribute](attributes#^fff13b) and its value specifies the page you want to link to.

![[links-syntax_html.svg]]

Code example:

```html
<p>Movie Reviews:</p>
<ul>
  <li><a href="https://wwww.empireonline.com">Empire</a></li>
  <li><a href="https://wwww.metacritic.com">Metacritic</a></li>
  <li><a href="https://wwww.rottentomatoes.com">Rotten Tomatoes</a></li>
  <li><a href="https://wwww.variety.com">Variety</a></li>
</ul>
```

## Uniform Resource Locator (URL)

Every web page has its own **URL** and this is the web address that people type into a browser if they want to visit a specific page. There are two type of **URL**:

1. **Absolute URL**
2. **Relative URL**

## Absolute URL

When you want to link to a different website, the value of the `href` attribute will be the full web address for the site, which is known as an **absolute URL**.

**Absolute URL** starts with the domain name for that site, and can be followed by the path to a specific page.

The syntax:

```html
<a href="https://www.google.com/"></a>
```

## Relative URL

When linking to other pages within the same site, that’s when **relative URLs** comes into play. **Relative URL** are like a shorthand version of **absolute URL** because there is no need to specify the domain name of the page since the page will be stored locally.

The syntax:

```html
<ul>
  <li><a href="index.html">Home</a></li>
  <li><a href="about.html">About</a></li>
  <li><a href="service.html">Service</a></li>
  <li><a href="register.html">Register</a></li>
</ul>
```

## email links

To create a link that starts up the user’s email program and addresses an email to a specific email address, you use the `<a>` element with the `href` attribute which starts with `mailto:` follow by the email address.

The syntax:

```html
<a href="mailto:support@callus.org">Email Support</a>
```

## opening links in a new window

To open a link in a new window, you use the [target](attributes#^fff13b) attribute on the opening `<a>` tag and the value should be `_blank`.

The syntax:

```html
<a href="https://www.animeplanet.org" target="_blank">Anime Planet</a> <!-- opens in a new window -->
```

---

- [[linking the same page]]

[[html]]
[[attributes]]
[[block and inline]]****
