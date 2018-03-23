# weddingposter

For our wedding, I made a [poster](poster.pdf) using **{rmarkdown}** and **{LaTeX}**. To make the poster, render [poster.Rmd](poster.Rmd).

Required fonts are **Adobe Garamond Pro**, **Apple Chancery**, and **Snell Roundhand**. You can edit the font code (shown below) in [pre.text](pre.tex).

``` tex
\setmainfont[Scale=1.50]{Adobe Garamond Pro}
\setmonofont[Scale=2.50]{Apple Chancery}
\setsansfont[Scale=3.50]{Snell Roundhand}
```

The icons were made using **Font Awesome**.

``` tex
\usepackage{fontawesome}
```

