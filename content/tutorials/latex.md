---
title: LaTeX
author: Joanna Morris
date: '2022-06-03'
slug: [eeglab-erplab]
image: img/tutorials/LaTeX_logo.png
showonlyimage: false
categories: []
tags: []
---

In the lab we use LaTex (pronounced lay-tech or, alternatively, la as in lava and tech as in technology) for writing papers and general documentation. 

<!--more-->

LaTeX is a [markup](https://en.wikipedia.org/wiki/Markup_language) language.  

The advantages of using a markup language like LaTeX rather than a [WYSISYG text editor](https://en.wikipedia.org/wiki/WYSIWYG) like MS Word is that your documents are written in plain text, so it is easier to collaborate with others and to manage drafts using version control software like [`git`](https://www.morrislabpc.org/tutorials/git-tutorial/). LaTeX handles mathematical formulas much better than many word processors and it is platform independent.

- [What is LaTex?](https://guides.lib.wayne.edu/latex/home)

- [How does writing in Latex differ from writing in MS Word?](https://www.baeldung.com/cs/latex-vs-word-main-differences)

- [Writing a Latex document](https://guides.lib.wayne.edu/latex/write)

- [Compiling a LaTex document](https://guides.lib.wayne.edu/latex/write)

- [LaTex packages](https://guides.lib.wayne.edu/latex/packages)

- [Bibliographies in LaTex](https://www.andy-roberts.net/latex/bibliographies/)

- [About the `biblatex` package](https://www.overleaf.com/learn/latex/Articles/Getting_started_with_BibLaTeX)

- [About the `natbib` package](http://merkel.texture.rocks/Latex/natbib.php)

- [Graphics in Latex](https://www.reed.edu/it/help/LaTeX/Graphics.html)

***Note for Bibliographies***
APA style requires that in text citations with mutliple authors use the word "and" but  parenthetical citations with multiple authors should use an ampersand.  To do this wrap the citation in the command `{\renewcommand\&{and}}`  as follows:

`{\renewcommand\&{and}\citet{rastleMorphologicalDecompositionBased2008}}`
