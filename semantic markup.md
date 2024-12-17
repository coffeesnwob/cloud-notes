# Semantic Markup

Semantic Markup provides extra information, and meaning or purpose of the content within them rather than just defining its appearance.

## strong and emphasis

If you want to make text appear or indicate that it is important you use the `<strong>` element. By default, the text will appear bold.

```html
<p>
  <strong>Beware:</strong> Pickpockets operate in this area. Make sure that you
  guard your belongs with care.
</p>
```

The `<em>` element indicates emphasis that *subtly* changes the meaning of the sentence and by default, text will appear italic.

```html
<p>
  This is a normal sentence. This is a sentence with <em>emphasized text</em>.
</p>
```

## quotations

You use the `<blockquote>` element for larger quotes that take up an entire paragraph. Browsers tend to indent the contents of the `<blockquote>` element. `<blockquote>` also uses the [cite attribute](attributes#^fff13b) to provide the source of the quoted content.

>[!danger]- Important
>- Don’t use this element just to indent text in your webpage.

```html
<blockquote cite="https://en.wikipedia.org/">
  <p>
    Networking is not about just connecting people. It's about connecting
    people, people with ideas, and people with opportunities.
  </p>
  <p>~ Michele Jannae</p>
</blockquote>
```

The `<q>` element is used for shorter quotes that sit within a paragraph.

```html
<p>
  Steve Jobs once said,
  <q>Innovation distinguishes between a leader and a follower.</q>
</p>
```

>[!success]- Tip
>- You can use the `<q>` element inside the `<blockquote>` element

## abbreviations and acronyms

The `<abbr>` element is used for both abbreviations and acronyms and it uses an attribute called [title](def/attributes#^fff13b) to specify the full term.

```html
<p>
  <abbr title="Professor">Prof</abbr> Stephen Hawking is a theoretical physicist and cosmologist.
</p>
<p>
  <abbr title="National Aeronautics and Space Administration">NASA</abbr> do
  some crazy space stuff.
</p>
```

## citation and definitions

When you are referencing a piece of work such as a book, film or research paper, the `<cite>` element can be used to indicate where the citation is from. Browsers will render the contents of a cite element in _italics_.

```html
<p>
  <cite>A Brief History of Time</cite> by Stephen Hawking has sold over ten
  million copies worldwide
</p>
```

> [!question] Does the `<cite>` element have attributes and how to properly use it and in which scenarios? #question

The `<dfn>` element is used to define a new term. The browser will also render the contents of this element in _italics_.

```html
<p>
  A <dfn>black hole</dfn> is a region of space from which nothing, note even
  light, can escape.
</p>
```

## address and details

An **address element** is used to define contact information or geographical details for a webpage. The `<address>` tag is typically used for author or contact information, such as physical addresses, phone numbers, email addresses, and social media profiles. Browsers tend to display the contents of the `<address>` element in _italics_.

```html
<address>
  <p>Contact us at:</p>
  <a href="mailto:support@example.com">support@example.com</a><br />
  <p>Phone: +1 234 567 890</p>
  <p>Visit us at: 123 Main Street, Bulawayo, Zim</p>
</address>
```

## changes to content

The `<ins>` element can be used to show content that has been inserted into a document, while `<del>` element can show text that has been deleted from it.

```html
<p>It was the <del>worst</del> <ins>best</ins> idea she had ever had.</p>
```

The `<s>` element indicates something that is no longer accurate or relevant.

```html
<p>Laptop Computer:</p>
<p><s>was $995</s></p>
<p>Now only $375</p>
```

---

[[html]]
[[attributes]]
[[structural markup]]