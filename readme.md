### LaTex

LaTeX is a high-quality typesetting system; it includes features designed for the production of technical and scientific documentation. LaTeX is the de facto standard for the communication and publication of scientific documents. LaTeX is available as [free software](https://www.latex-project.org/lppl/).

**LATEX**（/ˈlɑːtɛx/，常被读作/ˈlɑːtɛk/或/ˈleɪtɛk/），文字形式写作**LaTeX**，是一种基于[TEX](https://zh.wikipedia.org/wiki/TeX)的[排版](https://zh.wikipedia.org/wiki/%E6%8E%92%E7%89%88)系统，由[美国](https://zh.wikipedia.org/wiki/%E7%BE%8E%E5%9B%BD)[计算机科学](https://zh.wikipedia.org/wiki/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%A7%91%E5%AD%A6)家[莱斯利·兰伯特](https://zh.wikipedia.org/wiki/%E8%8E%B1%E6%96%AF%E5%88%A9%C2%B7%E5%85%B0%E4%BC%AF%E7%89%B9)在20世纪80年代初期开发，利用这种格式系统的处理，即使使用者没有排版和程序设计的知识也可以充分发挥由TEX所提供的强大功能，不必一一亲自去设计或校对，能在几天，甚至几小时内生成很多具有书籍品质的印刷品。对于生成复杂表格和[数学](https://zh.wikipedia.org/wiki/%E6%95%B0%E5%AD%A6)公式，这一点表现得尤为突出。因此它非常适用于生成高印刷质量的[科技](https://zh.wikipedia.org/wiki/%E7%A7%91%E6%8A%80)和数学、物理文档。这个系统同样适用于生成从简单的信件到完整书籍的所有其他种类的文档。

LATEX使用TEX作为它的格式化引擎，当前的版本是LaTeX2e（写作LATEX2ε）。

```
/Users/oudream/Library/texlive
/Users/oudream/Library/texmf

Critical xeCJK error: "Require-XeTeX" The xeCJK package requires XeTeX to function. 
You must change your typesetting engine to "xelatex" instead of plain "latex" or "pdflatex" or "lualatex". 
Loading xeCJK will abort! For immediate help type H <return>.

\usepackage{xeCJK}
\setCJKmainfont[BoldFont={STHeiti},ItalicFont=STKaiti]{STSong}
\setCJKsansfont{STHeiti}
\setCJKmonofont{STFangsong}
\setCJKfamilyfont{zhsong}{STSong}
\setCJKfamilyfont{zhhei}{STHeiti}
\setCJKfamilyfont{zhkai}{STKaiti}
\setCJKfamilyfont{zhfs}{STFangsong}
\setCJKfamilyfont{zhli}{LiSu}
\setCJKfamilyfont{zhyou}{YouYuan}
\newcommand*{\songti}{\CJKfamily{zhsong}} % 宋体
\newcommand*{\heiti}{\CJKfamily{zhhei}}   % 黑体
\newcommand*{\kaishu}{\CJKfamily{zhkai}}  % 楷书
\newcommand*{\fangsong}{\CJKfamily{zhfs}} % 仿宋
\newcommand*{\lishu}{\CJKfamily{zhli}}    % 隶书
\newcommand*{\youyuan}{\CJKfamily{zhyou}} % 幼圆
```



