<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Inconsolata&display=swap" rel="stylesheet">

<div style="font-family: 'Inconsolata', monospace;">

# Images In Markdown:
## How to add your images to a markdown file.

### Take a look at the code we will use to insert an image:

```markdown
![Alternative text](/path/to/img.jpg "Optional title")

# Reference

![Alternative text][id]
[id]: url/to/image "Optional title"
```

## <ins>Tanslating the code: </ins>

Inside the square braces - `[]` - we write our *alternative text*. When the image can not be displayed, your text will be shown. <br>
Say your image is representing the *scope structure* in JavaScript, then call your alternative text *scope structure*. <br>

In the brackets - `()` - we place the path of the image, just like an image url online, but a local version.
#

## <ins> Overview: </ins>

- The square brackets must be prefixed with an exclamation mark and inside they may have some alternative text.
- A description of the image, which is displayed if the image can't be loaded.

</div>


