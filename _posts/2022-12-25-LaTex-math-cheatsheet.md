---
layout: post
title:  "LaTex Math Cheatsheet"
date:   2021-12-10 00:00:00 -0000
modified_date: 2022-12-25 00:00:00 -0000
excerpt: 🗿🗿🗿 Become a real chad in LaTex math mode $-_-$
---

<!-- Mathjax Support -->
<script type="text/javascript" async
    src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

* toc
{:toc}

This cheatsheet is about math constructs and symbols in LaTex Math mode, remember to put the dollar sign `$` on both sides of the math equation.

## Variable-sized Symbols

| **Symbol** | **LaTex** |       **Symbol**       | **LaTex**            |
|:----------:|:----------|:----------------------:|:---------------------|
|  $$\sum$$  | `\sum`    |  $$\displaystyle\sum$$ | `\displaystyle\sum`  |
|  $$\int$$  | `\int`    |  $$\displaystyle\int$$ | `\displaystyle\int`  |
|  $$\prod$$ | `\prod`   | $$\displaystyle\prod$$ | `\displaystyle\prod` |
|  $$\iint$$ | `\iint`   | $$\displaystyle\iint$$ | `\displaystyle\iint` |
|  $$\oint$$ | `\oint`   | $$\displaystyle\oint$$ | `\displaystyle\oint` |

### Some Examples

|                  **Example**                  | **LaTex**                                   |
|:---------------------------------------------:|:--------------------------------------------|
|        $$\sum_{k=1}^{\infty}{0.5^k}=1$$       | `\sum_{k=1}^{\infty}{0.5^k}=1`              |
| $$\displaystyle\sum_{k=1}^{\infty}{0.5^k}=1$$ | `\displaystyle\sum_{k=1}^{\infty}{0.5^k}=1` |
|             $$\int_1^2{3x^2}dx=7$$            | `\int_1^2{3x^2}dx=7`                        |
|      $$\displaystyle\int_1^2{3x^2}dx=7$$      | `\displaystyle\int_1^2{3x^2}dx=7`           |
|             $$n!=\prod_{i=1}^n i$$            | `n!=\prod_{i=1}^n i`                        |
|      $$n!=\displaystyle\prod_{i=1}^n i$$      | `n!=\displaystyle\prod_{i=1}^n i`           |


## Greek Letters

| **Symbol** | **LaTex**    | **Symbol** | **LaTex** | **Symbol** | **LaTex**  |
|:--:|:--|:--:|:--|:--:|:--|
| $$\alpha$$      | `\alpha`      | $$\iota$$       | `\iota`    | $$\sigma$$      | `\sigma`    |
| $$\beta$$       | `\beta`       | $$\kappa$$      | `\kappa`   | $$\varsigma$$   | `\varsigma` |
| $$\gamma$$      | `\gamma`      | $$\lambda$$     | `\lambda`  | $$\tau$$        | `\tau`      |
| $$\delta$$      | `\delta`      | $$\mu$$         | `\mu`      | $$\upsilon$$    | `\upsilon`  |
| $$\epsilon$$    | `\epsilon`    | $$\nu$$         | `\nu`      | $$\phi$$        | `\phi`      |
| $$\varepsilon$$ | `\varepsilon` | $$\xi$$         | `\xi`      | $$\varphi$$     | `\varphi`   |
| $$\zeta$$       | `\zeta`       | $$\pi$$         | `\pi`      | $$\chi$$        | `\chi`      |
| $$\eta$$        | `\eta`        | $$\varpi$$      | `\varpi`   | $$\psi$$        | `\psi`      |
| $$\theta$$        | `\theta`      | $$\rho$$        | `\rho`     | $$\omega$$      | `\omega`    |
| $$\vartheta$$   | `\vartheta`   | $$\varrho$$     | `\varrho`  |                |                |
|                |                  |                |               |                |                |
| $$\Gamma$$      | `\Gamma`      | $$\Xi$$         | `\Xi`      | $$\Phi$$        | `\Phi`      |
| $$\Delta$$      | `\Delta`      | $$\Pi$$         | `\Pi`      | $$\Psi$$        | `\Psi`      |
| $$\Theta$$      | `\Theta`      | $$\Sigma$$      | `\Sigma`   | $$\Omega$$      | `\Omega`    |
| $$\Lambda$$     | `\Lambda`     | $$\Upsilon$$    | `\Upsilon` |                |                |  


## Math Constructs and Accents

|        **Example**       | **LaTex**              |  **Example**  | **LaTex**   |
|:------------------------:|:-----------------------|:-------------:|:------------|
|          $$x^2$$         | `x^2`                  |  $$\hat{x}$$  | `\hat{x}`   |
|          $$x_0$$         | `x_0`                  |  $$\bar{x}$$  | `\bar{x}`   |
|     $$\frac{ab}{xy}$$    | `\frac{ab}{xy}`        |  $$\dot{x}$$  | `\dot{x}`   |
|     $$\binom{n}{k}$$     | `\binom{n}{k}`         |  $$\ddot{x}$$ | `\ddot{x}`  |
|       $$\sqrt{xy}$$      | `\sqrt{xy}`            | $$\tilde{x}$$ | `\tilde{x}` |
|     $$\sqrt[n]{xy}$$     | `\sqrt[n]{xy}`         |  $$\vec{x}$$  | `\vec{x}`   |
|     $$\widehat{xyz}$$    | `\widehat{xyz}`        | $$\check{x}$$ | `\check{x}` |
|    $$\overline{xyz}$$    | `\overline{xyz}`       | $$\acute{x}$$ | `\acute{x}` |
|    $$\underline{xyz}$$   | `\underline{xyz}`      | $$\grave{x}$$ | `\grave{x}` |
| $$\overrightarrow{xyz}$$ | `\overrightarrow{xyz}` | $$\breve{x}$$ | `\breve{x}` |
|  $$\overleftarrow{xyz}$$ | `\overleftarrow{xyz}`  |               |             |


## Commonly Used Symbols

### Arithmetic & Calculus

| **Symbol** | **LaTex** |  **Symbol** | **LaTex** |  **Symbol**  | **LaTex**  |
|:----------:|:----------|:-----------:|:----------|:------------:|:-----------|
|   $$\pm$$  | `\pm`     |  $$\cdot$$  | `\cdot`   |  $$\nabla$$  | `\nabla`   |
|   $$\mp$$  | `\mp`     | $$\bullet$$ | `\bullet` | $$\partial$$ | `\partial` |
| $$\times$$ | `\times`  |  $$\prime$$ | `\prime`  |    $$\Re$$   | `\Re`      |
|  $$\div$$  | `\div`    |  $$\infty$$ | `\infty`  |    $$\Im$$   | `\Im`      |

### Relational

|   **Symbol**  | **LaTex**   |  **Symbol** | **LaTex** |   **Symbol**   | **LaTex**    |
|:-------------:|:------------|:-----------:|:----------|:--------------:|:-------------|
|    $$\geq$$   | `\geq`      |   $$\ll$$   | `\ll`     |   $$\propto$$  | `\propto`    |
|    $$\leq$$   | `\leq`      |   $$\neq$$  | `\neq`    | $$\triangleq$$ | `\triangleq` |
| $$\geqslant$$ | `\geqslant` |  $$\equiv$$ | `\equiv`  |   $$\doteq$$   | `\doteq`     |
| $$\leqslant$$ | `\leqslant` | $$\approx$$ | `\approx` |  $$\lessgtr$$  | `\lessgtr`   |
|    $$\gg$$    | `\gg`       |   $$\sim$$  | `\sim`    |  $$\gtrless$$  | `\gtrless`   |
|               |             |  $$\cong$$  | `\cong`   |                |              |

### Geometry

|   **Symbol**  | **LaTex**   |     **Symbol**    | **LaTex**       |   **Symbol**   | **LaTex**    |
|:-------------:|:------------|:-----------------:|:----------------|:--------------:|:-------------|
|   $$\angle$$  | `\angle`    | $$\overline{AB}$$ | `\overline{AB}` |  $$\parallel$$ | `\parallel`  |
| $$\triangle$$ | `\triangle` |    $$\vec{AB}$$   | `\vec{AB}`      | $$\nparallel$$ | `\nparallel` |
|  $$\square$$  | `\square`   | $$\vert AB\vert$$ | `\vert AB\vert` |    $$\perp$$   | `\perp`      |
|               |             | $$\Vert AB\Vert$$ | `\Vert AB\Vert` |                |              |

### Set Theory

|     **Symbol**    | **LaTex**       |     **Symbol**    | **LaTex**       |  **Symbol** | **LaTex** |
|:-----------------:|:----------------|:-----------------:|:----------------|:-----------:|:----------|
|   $$\emptyset$$   | `\emptyset`     |   $$\mathbb{R}$$  | `\mathbb{R}`    |  $$\aleph$$ | `\aleph`  |
|  $$\varnothing$$  | `\varnothing`   |   $$\mathbb{Z}$$  | `\mathbb{Z}`    |  $$\beth$$  | `\beth`   |
|      $$\cup$$     | `\cup`          |  $$A^\mathrm{C}$$ | `A^\mathrm{C}`  |  $$\uplus$$ | `\uplus`  |
|      $$\cap$$     | `\cap`          |   $$\setminus$$   | `\setminus`     |
|    $$\subset$$    | `\subset`       |    $$\supset$$    | `\supset`       |   $$\in$$   | `\in`     |
|   $$\subseteq$$   | `\subseteq`     |   $$\supseteq$$   | `\supseteq`     |  $$\notin$$ | `\notin`  |
|  $$\not\subset$$  | `\not\subset`   |  $$\not\supset$$  | `\not\supset`   |   $$\ni$$   | `\ni`     |
| $$\not\subseteq$$ | `\not\subseteq` | $$\not\supseteq$$ | `\not\supseteq` | $$\not\ni$$ | `\not\ni` |

### Logic

|  **Symbol**  | **LaTex**  |   **Symbol**   | **LaTex**    |    **Symbol**    | **LaTex**        |
|:------------:|:-----------|:--------------:|:-------------|:----------------:|:-----------------|
|  $$\forall$$ | `\forall`  |   $$\oplus$$   | `\oplus`     |     $$\top$$     | `\top`           |
|  $$\exists$$ | `\exists`  |   $$\veebar$$  | `\veebar`    |     $$\bot$$     | `\bot`           |
| $$\nexists$$ | `\nexists` |    $$\iff$$    | `\iff`       |    $$\vdash$$    | `\vdash`         |
|   $$\land$$  | `\land`    |  $$\implies$$  | `\implies`   |    $$\models$$   | `\models`        |
|   $$\lor$$   | `\lor`     |  $$\because$$  | `\because`   | $$\blacksquare$$ | `\ blacksquare ` |
|   $$\lnot$$  | `\lnot`    | $$\therefore$$ | `\threrfore` |     $$\Box$$     | `\Box`           |

### Arrows

|    **Symbol**    | **LaTex**      |        **Symbol**       | **LaTex**             |
|:----------------:|:---------------|:-----------------------:|:----------------------|
|   $$\uparrow$$   | `\uparrow`     |   $$\leftrightarrow$$   | `\leftrightarrow`     |
|  $$\downarrow$$  | `\downarrow`   |   $$\Leftrightarrow$$   | `\Leftrightarrow`     |
|  $$\leftarrow$$  | `\leftarrow`   | $$\longleftrightarrow$$ | `\longleftrightarrow` |
|  $$\rightarrow$$ | `\rightarrow`  | $$\Longleftrightarrow$$ | `\Longleftrightarrow` |
|   $$\Uparrow$$   | `\Uparrow`     |       $$\nwarrow$$      | `\nwarrow`            |
|  $$\Downarrow$$  | `\Downarrow`   |       $$\nearrow$$      | `\nearrow`            |
|  $$\Leftarrow$$  | `\Leftarrow`   |       $$\swarrow$$      | `\swarrow`            |
|  $$\Rightarrow$$ | `\Rightarrow`  |       $$\searrow$$      | `\searrow`            |
| $$\updownarrow$$ | `\updownarrow` |  $$\rightleftharpoons$$ | `\rightleftharpoons`  |
| $$\Updownarrow$$ | `\Updownarrow` |     $$\upuparrows$$     | `\upuparrows`         |

### Miscellaneous

|  **Symbol**  | **LaTex**  |    **Symbol**   | **LaTex**     |    **Symbol**    | **LaTex**      |
|:------------:|:-----------|:---------------:|:--------------|:----------------:|:---------------|
|   $$\circ$$  | `\circ`    |   $$\dagger$$   | `\dagger`     |     $$\hbar$$    | `\hbar`        |
| $$\bigcirc$$ | `\bigcirc` |   $$\ddagger$$  | `\ddagger`    |    $$\imath$$    | `\imath`       |
|   $$\odot$$  | `\odot`    |   $$\diamond$$  | `\diamond`    |    $$\jmath$$    | `\jmath`       |
|  $$\ominus$$ | `\ominus`  |     $$\lhd$$    | `\lhd`        |     $$\ell$$     | `\ell`         |
|  $$\oplus$$  | `\oplus`   |     $$\rhd$$    | `\rhd`        |     $$\eth$$     | `\eth`         |
|  $$\oslash$$ | `\oslash`  |    $$\unlhd$$   | `\unlhd`      |      $$\wp$$     | `\wp`          |
|  $$\otimes$$ | `\otimes`  |    $$\unrhd$$   | `\unrhd`      |     $$\flat$$    | `\flat`        |
|   $$\prec$$  | `\prec`    |     $$\vee$$    | `\vee`        |   $$\natural$$   | `\natural`     |
|   $$\succ$$  | `\succ`    |    $$\wedge$$   | `\wedge`      |     $$\mho$$     | `\mho`         |
|  $$\preceq$$ | `\preceq`  |     $$\wr$$     | `\wr`         |     $$\surd$$    | `\surd`        |
|  $$\succeq$$ | `\succeq`  |   $$\ltimes$$   | `\ltimes`     |  $$\spadesuit$$  | `\spadesuit`   |
|  $$\smile$$  | `\smile`   |   $$\rtimes$$   | `\rtimes`     |  $$\heartsuit$$  | `\heartsuit`   |
|  $$\frown$$  | `\frown`   |    $$\Join$$    | `\Join`       |   $$\clubsuit$$  | `\clubsuit`    |
|  $$\asymp$$  | `\asymp`   | $$\circledast$$ | `\circledast` | $$\diamondsuit$$ | `\diamondsuit` |


## Matrix

### Bracket and dot symbols

|      **Symbol**     | **LaTex**         |      **Symbol**      | **LaTex**          |
|:-------------------:|:------------------|:--------------------:|:-------------------|
|       $$(A)$$       | `(A)`             |        $$[A]$$       | `[A]`              |
| $$\left( A\right)$$ | `\left( A\right)` |  $$\left[ A\right]$$ | `\left[ A\right]`  |
|   $$\vert A\vert$$  | `|A|`             |      $$\{ A\}$$      | `\{ A\}`           |
|   $$\vert A\vert$$  | `\vert A\vert`    |  $$\lceil A\rceil$$  | `\lceil A\rceil`   |
|      $$\| A\|$$     | `\| A\|`          | $$\lfloor A\rfloor$$ | `\lfloor A\rfloor` |
|   $$\Vert A\Vert$$  | `\Vert A\Vert`    | $$\langle A\rangle$$ | `\langle A\rangle` |
||
| $$\cdots$$ | `\cdots` | $$\ldots$$ | `\ldots` |
| $$\vdots$$ | `\vdots` | $$\ddots$$ | `\ddots` |

### Matrix examples

| **Example** | **LaTex** |
|:--:|:--|
| $$\begin{bmatrix}a & b\\c & d\end{bmatrix}$$ | `\begin{bmatrix}a & b\\c & d\end{bmatrix}` |
| $$\begin{pmatrix}a & b\\c & d\end{pmatrix}$$ | `\begin{pmatrix}a & b\\c & d\end{pmatrix}` |
| $$\begin{vmatrix}a & b\\c & d\end{vmatrix}$$ | `\begin{vmatrix}a & b\\c & d\end{vmatrix}` |
| $$\begin{Vmatrix}a & b\\c & d\end{Vmatrix}$$ | `\begin{Vmatrix}a & b\\c & d\end{Vmatrix}` |
| $$\begin{bmatrix} a_{11} & a_{12} & \dots & a_{1N}\\ \vdots & \vdots & \ddots & \vdots \\ a_{N1} & a_{N2} & \cdots & a_{NN} \end{bmatrix}$$ | `\begin{bmatrix} a_{11} & a_{12} & \dots & a_{1N}\\ \vdots & \vdots & \ddots & \vdots \\ a_{N1} & a_{N2} & \cdots & a_{NN} \end{bmatrix}` |


## Standard Function Names

Typing the function name directly will result in italic font, which is not ideal. Therefore, it is recommended to add a backslash before the function name to use the standard name in LaTex, e.g.

$$\cos(x)$$ `\cos(x)` is ideal,

$$cos(x)$$ `cos(x)` is not.

|   **Name**  | **LaTex** | **Name** | **LaTex** |   **Name**  | **LaTex** |  **Name** | **LaTex** |
|:-----------:|:----------|:--------:|:----------|:-----------:|:----------|:---------:|:----------|
| $$\arccos$$ | `\arccos` | $$\csc$$ | `\csc`    |   $$\ker$$  | `\ker`    |  $$\min$$ | `\min`    |
| $$\arcsin$$ | `\arcsin` | $$\deg$$ | `\deg`    |   $$\log$$  | `\log`    |  $$\Pr$$  | `\Pr`     |
| $$\arctan$$ | `\arctan` | $$\det$$ | `\det`    |   $$\lim$$  | `\lim`    |  $$\sec$$ | `\sec`    |
|   $$\arg$$  | `\arg`    | $$\dim$$ | `\dim`    | $$\liminf$$ | `\liminf` |  $$\sin$$ | `\sin`    |
|   $$\cos$$  | `\cos`    | $$\exp$$ | `\exp`    | $$\limsup$$ | `\limsup` | $$\sinh$$ | `\sinh`   |
|  $$\cosh$$  | `\cosh`   | $$\gcd$$ | `\gcd`    |   $$\ln$$   | `\ln`     |  $$\sup$$ | `\sup`    |
|   $$\cot$$  | `\cot`    | $$\hom$$ | `\hom`    |   $$\log$$  | `\log`    |  $$\tan$$ | `\tan`    |
|  $$\coth$$  | `\coth`   | $$\inf$$ | `\inf`    |   $$\max$$  | `\max`    | $$\tanh$$ | `\tanh`   |


## Math Fonts

|    **Font**   | **Examples**                              |
|:-------------:|:------------------------------------------|
|     normal    | $$ABCDEFGHIJKLMNOPQRSTUVWXYZ$$            |
|  `\mathcal{}` | $$\mathcal{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$$  |
| `\mathfrak{}` | $$\mathfrak{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$$ |
|  `\mathbb{}`  | $$\mathbb{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$$   |
||
| normal      | $$abc+xyz-ij\times pq, 1234567890$$          |
| `\mathrm{}` | $$\mathrm{abc+xyz-ij\times pq, 1234567890}$$ |
| `\mathit{}` | $$\mathit{abc+xyz-ij\times pq, 1234567890}$$ |
| `\mathbf{}` | $$\mathbf{abc+xyz-ij\times pq, 1234567890}$$ |
| `\mathsf{}` | $$\mathsf{abc+xyz-ij\times pq, 1234567890}$$ |
| `\mathtt{}` | $$\mathtt{abc+xyz-ij\times pq, 1234567890}$$ |


## More information

- <https://www.overleaf.com/learn/latex/Mathematical_expressions>
- <https://en.wikipedia.org/wiki/List_of_mathematical_symbols_by_subject>
- <http://tug.ctan.org/info/short-math-guide/short-math-guide.pdf>
