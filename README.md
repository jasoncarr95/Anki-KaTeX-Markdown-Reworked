# Anki-KaTeX-Markdown (Reworked)

Fork of : https://github.com/Jwrede/Anki-KaTeX-Markdown. Special Thanks to [Jwrede](https://github.com/Jwrede) for starting this project.

Adding support and improvements of how cards are displayed.
Allowing for clozes inside code blocks. Better night mode support & readability. Coloring of the cloze elements. 

Creates a new Basic and a new Cloze Note Type that support Markdown and KaTeX: *Markdown and KaTeX Basic (Color)* and *Markdown and KaTeX Cloze (Color)*.
```md
# Markdown and KaTex {{c1::plugin}}
```js
console.log("{{c2::Markdown}}");
``‎`
$\sum_{i=0}^ni$

{{c3::$\sum_{i=0}^ni$}}
```
![](https://github.com/alexthillen/Anki-KaTeX-Markdown-Reworked/blob/main/example-cloze-color.gif)


## Features
<ul>
<li><a href="https://www.intmath.com/cg5/katex-mathjax-comparison.php" rel="nofollow">KaTeX is considered way faster than MathJax</a></li>
<li>Works on any device as long as there is internet connection</li>
<li><a href="https://markdown-it.github.io/" rel="nofollow">Markdown is a great all in one solution for Anki cards</a></li>
<li>Access KaTeX by <code>$...$</code> for inline math or <code>$$...$$</code> for displaystyle math, a list of supported functions can be found <a href="https://katex.org/docs/supported.html" rel="nofollow">here</a> </li>
<li>MathJax can also be accessed via <code>\[ ... \]</code> and <code>\(...\)</code></li>
</ul>

## Used Libraries
<a href="https://github.com/markdown-it/markdown-it">Markdown-It</a>  
<a href="https://github.com/KaTeX/KaTeX">KaTeX</a>

## Installation
* Go to
<a href="https://ankiweb.net/shared/info/1786114227"><img src="https://preview.redd.it/fka0b5cc48t41.png?auto=webp&s=c26da98dca2863e1d0dddbfd59b5bea6165f4bcb" width="24"></a>
to see how to install this addon for anki
* To install locally download the latest [release](https://github.com/Jwrede/Anki-KaTeX-Markdown/releases) and install by opening **Anki → Tools → Add-ons → Install** from file, then select **MDKaTeX.ankiaddon**
