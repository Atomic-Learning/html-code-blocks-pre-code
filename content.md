Sometimes when presenting code, it is useful to show multiple lines of code in a way that preserves whitespace and line breaks. A common approach is to use both the `<pre>`{.html} and `<code>`{.html} tags together. Consider the following example Python code:

```
def hello_world():
    print("Hello, World!")
```

This code block was created using the HTML code:

```html
<pre><code>def hello_world():
    print("Hello, World!")</code></pre>
```

When these two tags are used together, the `<pre>`{.html} tag:

* Preserves whitespace (including the indentation),
* Preserves line breaks,
* Is typically rendered in a monospace font by browser default styles (preserving the visual structure of the code)

While the `<code>`{.html} tag:

* Indicates that the content is code
* Can be styled differently to distinguish it from regular text

Either tag can be styled with CSS. JavaScript can also be used to apply or toggle CSS classes and styles. In the Atomic Learning platform, for example, the background color applied to the `<pre>`{.html} tag is a platform style used to emphasise the code block.
