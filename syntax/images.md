# Images

```markdown
# Inline
![Alternative text](/path/to/img.jpg "Optional title")

# Reference
![Alternative text][id]
[id]: url/to/image  "Optional title"
```
As you may have noticed, images in  Markdown are very similar to links. The difference is that:
* the square brackets must be prefixed with an exclamation mark and
* inside they may have some alternative text. A description of the image, which is displayed if the image can't be loaded.

---

Here's a quiz about markdown images.

Select the valid images:
- [ ] `[Google logo](https://www.google.ru/logo.png)`
- [x] `![](https://www.google.ru/logo.png)`

> Images must be prefixed with an exclamation mark.
The alternative text and a title are optional.

What is true about the following line: ```![Funny cat](http://cats.ru/funny.png "Share this")```
- [x] if the url is 404, "Funny cat" will be displayed
- [ ] exclamation mark can be omitted in this case
- [ ] if the url is 404, "Share this" will be displayed
- [x] on mouse over the image "Share this" will be displayed

> Similarly to links, images can have 3 parts: the alternative text, the url and a title. An exclamation mark is nesessary.

---
