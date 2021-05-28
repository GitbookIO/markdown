<!-- <head>
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Inconsolata&display=swap" rel="stylesheet">
</head> -->

<div style="font-family:monospace;">

 <h1 style="font-family:monospace;">Titles</h1>

### As we started writing a markdown document, we need to add a **title** and some **sub-headers**.

Markdown supports two styles of headers, *Setext* and *atx*.

Setext-style headers are “underlined” using equal signs (for first-level headers) and dashes (for second-level headers). 

### **For example:**

```markdown
This is an H1
=============

This is an H2
-------------
```

### Any number of underlining =’s or -’s will work.

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. 

### **For example:**

```markdown
# This is an H1

## This is an H2

###### This is an H6
```

Optionally, you may “close” atx-style headers.
<br>
 This is purely cosmetic — you can use this if you think it looks better.
 <br> The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

```markdown
# This is an H1 #

## This is an H2 ##

### This is an H3 ######
```
</div>
