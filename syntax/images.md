# Images

```markdown
# Inline
![Alternative text](/path/to/img.jpg "Optional title")

# Reference
![Alternative text][id]
[id]: url/to/image  "Optional title"
```
Comme vous avez dû le remarquer, les images en Markdown sont très semblables aux liens.  
La différence est la suivante :
* les crochets doivent être précédés par un point d'exclamation ;
* ils peuvent contenir un texte alternatif, qui s'affiche quand l'image ne peut être chargée.

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
