---
aliases: [Referencia Markdown]
---

[[#Separador]]
[[#Espacio]]
[[#Copyrigt]]
[[#Fondo negro]]
[[#Teletipo]]
[[#Subinidice y Superindice]]
[[#Alinear]]
[[#Tablas]]
[[#Comentarios]]
[[#YAML header]]
[[#Alfabeto griego]]


## Markdown útil
---

#### Separador  

<div align='center'>
<h3> *** </h3>
</div>

```
<div align='center'>
<h3> *** </h3>
</div>
```

---

#### Salto de página

```
<div style="page-break-after: always; visibility: hidden">
\pagebreak
</div>
```

---

#### Espacio

Creates four spaces between the text- `&emsp;`

Creates two spaces between the text - `&ensp;`

Creates a regular space between the text - `&nbsp;`

creates a narrow space ( similar to regular space but slight difference - `"&thinsp";`

spacing between sentences - `"</br>"`

---

#### Copyrigt

&copy

```
&copy
```

---

### Fondo negro

<kbd> aqui es un ejemplo </kbd>

`<kbd> aqui es un ejemplo </kbd>`

---

#### Subinidice y Superindice

Subscript \<sub>The quick brown fox jumps over the lazy dog.\</sub>
Superscript \<sup>The quick brown fox jumps over the lazy dog.\</sup>

```
Subscript <sub>The quick brown fox jumps over the lazy dog.</sub>
Superscript <sup>The quick brown fox jumps over the lazy dog.</sup>
```

---

### Teletipo

<TT> Este es un ejemplo </TT>

```
<TT> Este es un ejemplo </TT>
```

---

#### Alinear

<h3 align="center"> My latest Medium posts </h3>

`<h3 align="center"> My latest Medium posts \</h3>`

---

#### Tablas

<table>  
<tr>  
<td width="33%">  
The quick brown fox jumps over the lazy dog.  
</td>  
<td width="33%">  
The quick brown fox jumps over the lazy dog.  
</td>  
<td width="33%">  
The quick brown fox jumps over the lazy dog.  
</td>  
</tr>  
<tr>  
<td width="33%">  
The quick brown fox jumps over the lazy dog.  
</td>  
<td width="33%">  
The quick brown fox jumps over the lazy dog.  
</td>  
<td width="33%">  
The quick brown fox jumps over the lazy dog.  
</td>  
</tr> 
</table>

```
<tr>  
<td width="33%">  
The quick brown fox jumps over the lazy dog.  
</td>  
<td width="33%">  
The quick brown fox jumps over the lazy dog.  
</td>  
<td width="33%">  
The quick brown fox jumps over the lazy dog.  
</td>  
</tr>  
<tr>  
<td width="33%">  
The quick brown fox jumps over the lazy dog.  
</td>  
<td width="33%">  
The quick brown fox jumps over the lazy dog.  
</td>  
<td width="33%">  
The quick brown fox jumps over the lazy dog.  
</td>  
</tr> 
</table>
```

---

| Default | Left align | Center align | Right align |  
| - | :- | :-: | -: |  
| 9999999999 | 9999999999 | 9999999999 | 9999999999 |  
| 999999999 | 999999999 | 999999999 | 999999999 |  
| 99999999 | 99999999 | 99999999 | 99999999 |  
| 9999999 | 9999999 | 9999999 | 9999999 |
| Default    | Left align | Center align | Right align |  
| ---------- | :--------- | :----------: | ----------: |  
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |  
| 999999999  | 999999999  | 999999999    | 999999999   |  
| 99999999   | 99999999   | 99999999     | 99999999    |  
| 9999999    | 9999999    | 9999999      | 9999999     |
|Default    | Left align | Center align | Right align  
|---------- | :--------- | :----------: | ----------:  
9999999999 | 9999999999 | 9999999999   | 9999999999   
999999999  | 999999999  | 999999999    | 999999999    
99999999   | 99999999   | 99999999     | 99999999     
9999999    | 9999999    | 9999999      | 9999999

```
| Default | Left align | Center align | Right align |  
| - | :- | :-: | -: |  
| 9999999999 | 9999999999 | 9999999999 | 9999999999 |  
| 999999999 | 999999999 | 999999999 | 999999999 |  
| 99999999 | 99999999 | 99999999 | 99999999 |  
| 9999999 | 9999999 | 9999999 | 9999999 |
| Default    | Left align | Center align | Right align |  
| ---------- | :--------- | :----------: | ----------: |  
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |  
| 999999999  | 999999999  | 999999999    | 999999999   |  
| 99999999   | 99999999   | 99999999     | 99999999    |  
| 9999999    | 9999999    | 9999999      | 9999999     |
| Default    | Left align | Center align | Right align |
| ---------- | :--------- | :----------: | ----------: | 
| 9999999999 | 9999999999 | 9999999999   | 9999999999   
| 999999999  | 999999999  | 999999999    | 999999999    
| 99999999   | 99999999   | 99999999     | 99999999     
| 9999999    | 9999999    | 9999999      | 9999999
```

---

<table>  
<tr>  
<th>Heading 1</th>  
<th>Heading 2</th>  
</tr>  
<tr>  
 
<td>  
| A | B | C |  
|---|--- |---|  
| 1 | 2 | 3 |  
</td><td>  
  
| A | B | C |  
|---|---|---|  
| 1 | 2 | 3 |  
  
</td></tr> </table>

```
<table>  
<tr>  
<th>Heading 1</th>  
<th>Heading 2</th>  
</tr>  
<tr>  
 
<td>  
| A | B | C |  
|---|--- |---|  
| 1 | 2 | 3 |  
</td><td>  
  
| A | B | C |  
|---|---|---|  
| 1 | 2 | 3 |  
  
</td></tr> </table>
```

---

| A | B | C |  
|---|---|---|  
| 1 | 2 | 3 <br/> 4 <br/> 5 |

```
| A | B | C |  
|---|---|---|  
| 1 | 2 | 3 <br/> 4 <br/> 5 |
```

---

#### Comentarios

%%
Este es un comentario.
%%

```
%%
Este es un comentario.
%%
```

---
 #### YAML header

Insert, at the top of your R Markdown document, a bit of text like the following:

```
---
title: "An example Knitr/R Markdown document"
author: "Karl Broman"
date: "3 Feb 2015"
output: html_document
---
```

The final document will then contain a nicely formated title, along with the author name and date. You can include hyperlinks in there:

```
author: "[Karl Broman](https://kbroman.org)"
```

and even R code:

```
date: "`r Sys.Date()`"
```

This is called the [YAML](http://www.yaml.org) header. YAML is a simple text-based format for specifying data, sort of like [JSON](http://www.json.org) but more human-readable.

You can leave off the author and date if you want; you can leave off the title, too. Actually, you don’t need to include any of this. But `output: html_document` tells the [rmarkdown package](https://github.com/rstudio/rmarkdown) to convert the document to html. That’s the default, but you could also use `output: pdf_document` or even `output: word_document`, in which case your document will be converted to a PDF or Word `.docx` file, respectively.

[Fuente](https://kbroman.org/knitr_knutshell/pages/Rmarkdown.html)

---

#### Alfabeto griego

![[Pasted image 20211016142034.png]]

[Fuente](https://programmerclick.com/article/9139292621/)

|Mayúscula |Código |En minúscula |Código|
|---|---|---|---|
|A|	$A$ \$A$| 	α \alpha α |	\$\alpha$|
|B B B 	$B$ 	β \beta β 	$\beta$
|Γ \Gamma Γ 	$\Gamma$ 	γ \gamma γ 	$\gamma$
|Δ \Delta Δ 	$\Delta$ 	δ \delta δ 	$\delta$
|E E E 	$E$ 	ϵ \epsilon ϵ 	$\epsilon$
		ε \varepsilon ε 	$\varepsilon$
Z Z Z 	$Z$ 	ζ \zeta ζ 	$\zeta$
H H H 	$H$ 	η \eta η 	$\eta$
Θ \Theta Θ 	$\Theta$ 	θ \theta θ 	$\theta$
I I I 	$I$ 	ι \iota ι 	$\iota$
K K K 	$K$ 	κ \kappa κ 	$\kappa$
Λ \Lambda Λ 	$\Lambda$ 	λ \lambda λ 	$\lambda$
M M M 	$M$ 	μ \mu μ 	$\mu$
N N N 	$N$ 	ν \nu ν 	$\nu$
Ξ \Xi Ξ 	$\Xi$ 	ξ \xi ξ 	$\xi$
O O O 	$O$ 	ο \omicron ο 	$\omicron$
Π \Pi Π 	$\Pi$ 	π \pi π 	$\pi$
P P P 	$P$ 	ρ \rho ρ 	$\rho$
Σ \Sigma Σ 	\Sigma$ 	σ \sigma σ 	$\sigma$
T T T 	$T$ 	τ \tau τ 	$\tau$
Υ \Upsilon Υ 	$\Upsilon$ 	υ \upsilon υ 	$\upsilon$
Φ \Phi Φ 	$\Phi$ 	ϕ \phi ϕ 	$\phi$
X X X 	$X$ 	χ \chi χ 	$\chi$
Ψ \Psi Ψ 	$\Psi$ 	ψ \psi ψ 	$\psi$
Ω \Omega Ω 	$\Omega$ 	ω \omega ω 	$\omega$


```
Α &Alpha; GREEK CAPITAL LETTER ALPHA

Β &Beta; GREEK CAPITAL LETTER BETA

Γ &Gamma; GREEK CAPITAL LETTER GAMMA

Δ &Delta; GREEK CAPITAL LETTER DELTA

Ε &Epsilon; GREEK CAPITAL LETTER EPSILON

Ζ &Zeta; GREEK CAPITAL LETTER ZETA

Η &Eta; GREEK CAPITAL LETTER ETA

Θ &Theta; GREEK CAPITAL LETTER THETA

Ι &Iota; GREEK CAPITAL LETTER IOTA

Κ &Kappa; GREEK CAPITAL LETTER KAPPA

Λ &Lambda; GREEK CAPITAL LETTER LAMBDA

Μ &Mu; GREEK CAPITAL LETTER MU

Ν &Nu; GREEK CAPITAL LETTER NU

Ξ &Xi; GREEK CAPITAL LETTER XI

Ο &Omicron; GREEK CAPITAL LETTER OMICRON

Π &Pi; GREEK CAPITAL LETTER PI

Ρ &Rho; GREEK CAPITAL LETTER RHO

Σ &Sigma; GREEK CAPITAL LETTER SIGMA

Τ &Tau; GREEK CAPITAL LETTER TAU

Υ &Upsilon; GREEK CAPITAL LETTER UPSILON

Φ &Phi; GREEK CAPITAL LETTER PHI

Χ &Chi; GREEK CAPITAL LETTER CHI

Ψ &Psi; GREEK CAPITAL LETTER PSI

Ω &Omega; GREEK CAPITAL LETTER OMEGA

---

α &alpha; GREEK SMALL LETTER ALPHA

β &beta; GREEK SMALL LETTER BETA

γ &gamma; GREEK SMALL LETTER GAMMA

δ &delta; GREEK SMALL LETTER DELTA

ε &epsilon; GREEK SMALL LETTER EPSILON

ζ &zeta; GREEK SMALL LETTER ZETA

η &eta; GREEK SMALL LETTER ETA

θ &theta; GREEK SMALL LETTER THETA

ι &iota; GREEK SMALL LETTER IOTA

κ &kappa; GREEK SMALL LETTER KAPPA

λ &lambda; GREEK SMALL LETTER LAMBDA

μ &mu; GREEK SMALL LETTER MU

ν &nu; GREEK SMALL LETTER NU

ξ &xi; GREEK SMALL LETTER XI

ο &omicron; GREEK SMALL LETTER OMICRON

π &pi; GREEK SMALL LETTER PI

ρ &rho; GREEK SMALL LETTER RHO

ς &sigmaf; GREEK SMALL LETTER FINAL SIGMA

σ &sigma; GREEK SMALL LETTER SIGMA

τ &tau; GREEK SMALL LETTER TAU

υ &upsilon; GREEK SMALL LETTER UPSILON

φ &phi; GREEK SMALL LETTER PHI

χ &chi; GREEK SMALL LETTER CHI

ψ &psi; GREEK SMALL LETTER PSI

ω &omega; GREEK SMALL LETTER OMEGA

```

```
αA `$\alpha A$`

νN `$\nu N$`

βB `$\beta B$`

ξΞ `$\xi\Xi$`

γΓ `$\gamma \Gamma$`

oO `$o O$` (omicron)

δΔ `$\delta \Delta$`

πΠ `$\pi \Pi$`

ϵεE `$\epsilon \varepsilon E$`

ρϱP `$\rho\varrho P$`

ζZ `$\zeta Z \sigma \,\!$`

σΣ `$\sigma \Sigma$`

ηH `$\eta H$`

τT `$\tau T$`

θϑΘ `$\theta \vartheta \Theta$`

υΥ `$\upsilon \Upsilon$`

ιI `$\iota I$`

ϕφΦ `$\phi \varphi \Phi$`

κK `$\kappa K$`

χX `$\chi X$`

λΛ `$\lambda \Lambda$`

ψΨ `$\psi \Psi$`

μM `$\mu M$`

ωΩ `$\omega \Omega$`
```

---