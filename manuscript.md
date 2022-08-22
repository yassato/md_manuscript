---
title: Size-dependent reproduction in the virtual plant *Brassica satoi*
output:
  word_document: default
  pdf_document: default
  html_document: default
bibliography: bibliography.bib
csl: genetics.csl
---

**Yasuhiro Sato**^1^  
^1^ <span class="comment-start" id="0" author="YS" date="8-June-2022">IEU stands for "Institut für Evolutionsbiologie und Umweltwissenschaften"</span>IEU<span class="comment-end" id="0"></span>, University of Zurich  

# Introduction (section)
[Plants]{.insertion author="YS" date="8-June-2022"}[Animals]{.deletion author="YS" date="8-June-2022"} are immobile and cannot actively select their habitat. 
The timing of reproduction is thus critical for plants to maximize their fitness in nature. 
Ecological studies showed that the timing of reproduction depended on the size of individual plants [@bonser2009interpreting].
Such size-dependent reproduction has been frequently reported for perennial plants [@kachi1985population; @wesselingh1997threshold; @jacquemyn2010size]. 
For example, @kachi1985population revealed that...      

<span class="comment-start" id="0" author="YS" date="8-Aug-2022">\*single asterisk\* for *italic*; \*\*double asterisk\*\* for **bold**; \\ for escape sequence</span>*Brassica satoi*<span class="comment-end" id="0"></span> is a virtual plant species created for manuscript writing demonstration in a markdown. 
The height of this species followed a normal distribution with the mean of 100 and standard deviation of 20. 
The number of seeds is known to follow Poisson distribution in unknown relation to the height. 
To explore size-dependent reproduction in *B. satoi*, here we analyzed the example dataset.  


# Materials and Methods  

## Study site (subsection)  
Our field survey was conducted in the Irchel-Campus of the University of Zurich....  

## Field survey
We marked 100 individuals of *B. satoi* and recorded their height on 1 May 2022. 
All the plants were harvested on 30 June, and dried overnight...  

## Data analysis  

### Statistical tests (subsubsection)
We used standard linear models or generalized linear model (GLM) to analyze relationship between the plant height and ...  

### Figure presentation (subsubsection)
We added trend lines to the bi-plots following the linear regression model:
$$y = a + bx$$
, where $y$ is the response variable; $x$ is the explanatory variable; $a$ indicates the intercept; $b$ represents the regression slope. 
Because a log link function was used in the Poisson GLM, a regression curve was given by $y = e^{(a + bx)}$ for the number of seeds.  


# Results
The dry weight and the number of seeds both showed positive relationships with the plant height ($p<0.05$: Fig. [1](#fig:biplot){reference-type="ref" reference="fig:biplot"}; Table [1](#table:GLM){reference-type="ref" reference="table:GLM"}). 
We also found that ....  
  
# Discussion  
This study dealt with virtual data and thereby provided no biological significance. 
Citation Style Language (.csl) is usually available at journal's page or other repository (https://github.com/citation-style-language/styles). 
If you need a more complex format, HTML or even LaTeX may be required. 
Try to minimize manual handling until you give up, and export to .docx lastly.  

To separate the paragraph, you should put " " (a space) twice, like this sente  

nces. A single space does not influence the word output. ~~Strike through~~ can be made using "\~\~something\~\~". Because .docx will be made through 'pandoc', other pandoc annotations are also valid. For example, "\~something\~" and "\^superscript\^" generate ~subscript~ and ^superscript^, respectively. See also the pandoc manual <https://pandoc.org/MANUAL.html#superscripts-and-subscripts> for further controls.

# Tables
[Table 1.]{#table:GLM label="tableS:GLM"} Effects of the plant height on the dry weight (a) or the number of seeds (b).
Estimated coefficients (Coef.), its standard error (SE), *Z*-value, and *p*-value are shown for each factor.

(a) Dry weight

| Factor      | Coef.   | SE      | *Z*     | *p*        |
|-------------|---------|---------|-------|----------|
| (Intercept) | 3.16219 | 0.93325 | 3.388 | 0.00101  |
| height_cm   | 0.09923 | 0.01125 | 8.823 | 4.33E-14 |

(b) No. of seeds

| Factor      | Coef.    | SE       | *Z*      | *p*         |
|-------------|----------|----------|--------|-----------|
| (Intercept) | 1.563315 | 0.123073 | 12.702 | <2.00E-16 |
| height_cm   | 0.010138 | 0.001406 | 7.209  | 5.63E-13  |

# Figures
![Figure 1. Dependency of the dry weight (right) or the number of seeds (right) on the plant height](./figure/plant_data_analysis.pdf){#fig:biplot}  


# References
