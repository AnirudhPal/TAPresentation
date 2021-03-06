Using Github Pages and Markdown
===

Index
---

1. [**Markdown**](https://github.com/AnirudhPal/TAPresentation#markdown)

      * [*Headers*](https://github.com/AnirudhPal/TAPresentation#headers)
      * [*Bold and Italic*](https://github.com/AnirudhPal/TAPresentation#bold-and-italic)
      * [*Listing*](https://github.com/AnirudhPal/TAPresentation#listing)
      * [*URL*](https://github.com/AnirudhPal/TAPresentation#url)
      * [*Images*](https://github.com/AnirudhPal/TAPresentation#images)
      * [*Code Block*](https://github.com/AnirudhPal/TAPresentation#code-block)
      * [*Philosophy Block or Blockqoutes*](https://github.com/AnirudhPal/TAPresentation#philosophy-block-or-blockqoutes)
      * [*Table*](https://github.com/AnirudhPal/TAPresentation#table)
      * [*Video*](https://github.com/AnirudhPal/TAPresentation#video)
      * [*Extras*](https://github.com/AnirudhPal/TAPresentation#extras)

2. [**Github Pages**](https://github.com/AnirudhPal/TAPresentation#github-pages)

      * [*Setup*](https://github.com/AnirudhPal/TAPresentation#setup)
      * [*Supported*](https://github.com/AnirudhPal/TAPresentation#supported)
      * [*Not Supported*](https://github.com/AnirudhPal/TAPresentation#not-supported)
      * [*Extras*](https://github.com/AnirudhPal/TAPresentation#extras-1)

Markdown
---

### Headers

```
# H1
H1
===
## H2
H2
---
### H3
```

# H1
H1
===
## H2
H2
---
### H3

### Bold and Italic

```
*Word*

**Word**
```

*Word*

**Word**

### Listing

```
1. A
2. B

* A
* B

1. A
     * B
```

1. A
2. B

* A
* B

1. A
     * B

### URL

```
[My Github](https://github.com/AnirudhPal)
```

[My Github](https://github.com/AnirudhPal)

### Images

```
![](https://upload.wikimedia.org/wikipedia/commons/1/16/S-IC_engines_and_Von_Braun.jpg)
```

![](https://upload.wikimedia.org/wikipedia/commons/1/16/S-IC_engines_and_Von_Braun.jpg)

### Code Block

```
\```
Plain Code
\```

\```c
C Code
#include <stdio.h>

int main() {
   printf("Hello, World!");
   return 0;
}
\```
```

```
Plain Code
```

```c
C Code
#include <stdio.h>

int main() {
   printf("Hello, World!");
   return 0;
}
```

### Philosophy Block or Blockqoutes

```
> I propose to consider the question, 'Can machines think? - Alan Turing
```

> I propose to consider the question, 'Can machines think? - Alan Turing

### Table

```
Sl No: | AAAAAAA | BBBBBBB
--- | :-: | --:
1 | 10 | 20
2 | 20 | 10
```

Sl No: | AAAAAAA | BBBBBBB
--- | :-: | --:
1 | 10 | 20
2 | 20 | 10

### Extras

```html
<p align="center">
     Figure 11. Importing all Neccessary Libs.
</p>
```

<p align="center">
     Figure 11. Importing all Neccessary Libs.
</p>

```
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Word
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Word

Look at Index in Raw

Github Pages
---

### Setup

1. Create Repo

2. Go to Repo *Settings*

3. Scroll Down to *GitHub Pages*

4. Change *None* to *master branch*

5. Click *Save*

### Supported

Simple stuff like html, images, javascript, css, php etc.

### Not Supported

Things like database hosting, large files like STL etc.

### Extras

A small python HTTP server that runs on CS Data.

*Terminal Usage:*
```bash
python server.py [port]
```

*Browser Usage:*
```
data.cs.purdue.edu:[port]
```
