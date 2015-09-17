# Titles

Comme nous avons commencer à écrir un document en Markdown, nous avons besoin d'ajouter un titre et certain sous titre.

Le Markdown support deux styles d'en tête, Setex et atx.

Les en tête Setext sont soulignés en utilisant le signe "égal" (pour les en-têtes de premier niveau) et en utilisant le signe "tiret" (pour les en-têtes de second niveau.)

Par exemple:

```
Ceci est un H1
=============

Ceci est un H2
-------------
```

Any number of underlining =’s or -’s will work.

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:

```
# This is an H1

## This is an H2

###### This is an H6
```


Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better. The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

```
# This is an H1 #

## This is an H2 ##

### This is an H3 ######
```


---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Headers need space between the hash characters and the text.

Select the valid headers:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Only '=' and '-' are accepted for underlining an header.

---


