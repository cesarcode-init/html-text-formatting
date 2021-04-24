# HTML Text Formatting

## Text Formatting sub-guide

- [Text Formatting](#text-formatting)
- [Bold](#bold)
- [Italics](#italics)
- [Underline](#underline)
- [Strikethrough](#strikethrough)
- [Highlighting Texts](#highlighting-texts)
- [Small Texts](#small-texts)
- [Subscript Texts](#subscript-texts)
- [Superscript Texts](#superscript-texts)
- [Program Output](#program-output)
- [Keyboard Keys](#keyboard-keys)
- [Variables](#variables)

This article targets beginners in web development. It is part of my previous post on [html-guide](https://dev.to/cesar_code/html-crash-course-1djc). This can also be a refresher for advanced developers.

Using appropriate HTML tags comes with a lot of advantages. You can't skip these benefits because they are indispensable to you as a web developer and to others like visually impaired people.

### How does it relate to you?

 Being a professional web developer requires being adept at what you are doing. It requires keeping your work at the most professional level you can. Professionalism does matter in this case. It is what companies seek in the first place. Trust me! It is what gets you hired, too.

### How is it important to visually impaired people?

Using appropriate semantic tags will help blind people listen to web pages. How does that happen? A software called _screen reader_ does that job. It reads your HTML structural semantics out loud to them and allows them to become aware of what is happening at that moment. It guides them, so you need to be careful how to employ HTML semantics. Misplacing them can sometimes lead to grave consequences.

## Text Formatting

It is not uncommon to think about text formatting tags or exclusively semantic tags as a mere text presentation. Whilst this thought isn't correct, we should keep in mind how important it is to use appropriate HTML tags at the right time and in the right place to render web pages informative, hence, semantically relevant. We often use CSS to achieve great presentations of web pages.

[back to sub-guide](#text-formatting-sub-guide)

## Bold

We use `<b>` tags to make texts **bold**. This tag stands for `bold`. It targets how the text should _look_.

```html
<p>This paragraph has a bold <b>word</b> in it.</p>
```

We use `<strong>` tags to make texts **bold**. It targets how _important_ the text is so you have to _emphasise_ its importance.

```html
<p>
  This paragraph has a bold <strong>word</strong> in it because it is very
  important.
</p>
```

The distinction between `<b>` and `<strong>` is the level of importance each one contains. Semantically speaking, you should use the `<strong>` tag if you tend to add important text. But, if it's a matter of semi-styling, which infers it's only about making the text **bold**, then we use the `<b>` tag.

Note that experts recommend using `<strong>` over `<b>`. It does matter for visually impaired people. Keep that in mind!

[back to sub-guide](#text-formatting-sub-guide)

## Italics

We use `<i>` tags to make texts _italic_. This tag stands for `italics`.

```html
<p>This paragraph has an italicized <i>word</i>.</p>
```

We can use `<dfn>` tags to make texts _italics_. It stands for `definition element`. As the name suggests, it defines an element.

```html
<p>
  This paragraph has a <dfn>definition element</dfn> in it because it is
  defining a term.
</p>

<p><dfn>HTML</dfn> stands for HyperText Markup Language.</p>
```

The distinction between `<i>` and `<dfn>`is what kind of representation you are trying to associate with each one of them. We use `<dfn>` when you want to define a term whilst using `<i>` only makes a text _italic_ in the strict sense of the word. Both `<dfn>` and `<i>` make text _italic_ though.

We can use `<em>` to make texts _italic_, too. This tag stands for `emphasise`. You should use this tag if and only if you want to emphasise something.

```html
<p>This paragraph has a <em>word</em> in italics.</p>
```

Note that experts recommend using `<em>` over `<i>`. It does matter for visually impaired people. Keep that in mind, too!

[back to sub-guide](#text-formatting-sub-guide)

## Underline

We use `<u>` tags to underline a text. The `<u>` tag stands for `underline`.

```html
<p>This paragraph has an underlined <u>word</u> in it.</p>
```

We use `<ins>` tags to underline a specific text. This tag stands for `insert`. We use this tag only when it comes to `inserting` a new piece of information that did not exist before.

```html
<p>This paragraph has an underlined <ins>word</ins> in it.</p>
```

[back to sub-guide](#text-formatting-sub-guide)

## Strikethrough

We use `<s>` tags to ~~strike a text through~~. This tag stands for `strikethrough`.

```html
<p>This paragraph has a crossed <s>word</s> in it.</p>
```

We use `<del>` tags to ~~strike a text through~~, too. This tag stands for `delete`.

```html
<p>This paragraph has a crossed and deleted <del>content</del> in it.</p>
```

The distinction between both of them, we use `<s>` tags when we want to showcase that a piece of information that might be unnecessary. It doesn't mean it has been deleted permanently. However, using `<del>` tags implies that this piece of information has been literally deleted.

[back to sub-guide](#text-formatting-sub-guide)

## Highlighting Texts

We use `<mark>` tags to highlight a text. This tag highlights the text as it uses the yellow colour.

```html
<p>This paragraph has a highlighted <mark>word</mark> in it.</p>
```

[back to sub-guide](#text-formatting-sub-guide)

## Small Texts

We use `<small>` tags to make a text smaller than its usual size.

```html
<p>This paragraph has a small <small>word</small> in it.</p>
```

[back to sub-guide](#text-formatting-sub-guide)

## Subscript Texts

We use `<sub>` tags to make a text lower and smaller than the main text. This tag stands for `subscript`.

```html
<p>We all know about CO<sub>2</sub>.</p>
```

[back to sub-guide](#text-formatting-sub-guide)

## Superscript Texts

We use `<sup>` tags to make a text higher and smaller than the main text. This tag stands for `superscript`.

```html
<p>What about 2<sup>3</sup>?</p>
```

[back to sub-guide](#text-formatting-sub-guide)

## Program Output

We use `<samp>` tags to declare that the text is an output from a computer program. It stands for `sample`. The first you will notice is the font of the text enclosed between this tag changes into `monotype`.

```html
<p><samp>Please enter a number</samp></p>
```

[back to sub-guide](#text-formatting-sub-guide)

## Keyboard Keys

We use `<kbd>` tags to enclose `keys` that belong to a keyboard.

```html
<p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy a text</p>
```

[back to sub-guide](#text-formatting-sub-guide)

## Variables

We use `<var>` tags to enclose mathematical variables.

```html
<p>look at this equation <var>x</var> = <var>y</var> * 30</p>
```

[back to sub-guide](#text-formatting-sub-guide)

Thank you for your attention. There is more to it. That is why updating regularly would be necessary.

Instagram: [@cesarcode.init](https://www.instagram.com/cesarcode.init/)

More: [cesar_code](https://dev.to/cesar_code)
