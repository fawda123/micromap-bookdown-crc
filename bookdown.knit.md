--- 
title: "A Chapman & Hall/CRC Book Example Using bookdown"
author: "Frida Gomam"
date: "2021-09-28"
documentclass: krantz
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
colorlinks: yes
lot: yes
lof: yes
site: bookdown::bookdown_site
description: "A book example for a Chapman & Hall book."
github-repo: yihui/bookdown-crc
graphics: yes
#cover-image: images/cover.jpg
---



# Preface {-}

Hi there, this is my great book.

## Why read this book {-}

It is very important...

## Structure of the book {-}

Chapters \@ref(introduction) introduces a new topic, and ...

## Software information and conventions {-}

I used the **knitr**\index{knitr} package [@xie2015] and the **bookdown**\index{bookdown} package [@R-bookdown] to compile my book. My R session information is shown below:


```r
xfun::session_info()
```

```
## R version 4.0.2 (2020-06-22)
## Platform: x86_64-w64-mingw32/x64 (64-bit)
## Running under: Windows 10 x64 (build 19043)
## 
## Locale:
##   LC_COLLATE=English_United States.1252 
##   LC_CTYPE=English_United States.1252   
##   LC_MONETARY=English_United States.1252
##   LC_NUMERIC=C                          
##   LC_TIME=English_United States.1252    
## 
## Package version:
##   base64enc_0.1.3 bookdown_0.21   bslib_0.3.0    
##   compiler_4.0.2  digest_0.6.28   evaluate_0.14  
##   fastmap_1.1.0   fs_1.5.0        glue_1.4.2     
##   graphics_4.0.2  grDevices_4.0.2 highr_0.8      
##   htmltools_0.5.2 jquerylib_0.1.4 jsonlite_1.7.2 
##   knitr_1.31      magrittr_2.0.1  markdown_1.1   
##   methods_4.0.2   mime_0.11       R6_2.5.1       
##   rappdirs_0.3.3  rlang_0.4.11    rmarkdown_2.8  
##   rstudioapi_0.13 sass_0.4.0      stats_4.0.2    
##   stringi_1.7.4   stringr_1.4.0   tinytex_0.31   
##   tools_4.0.2     utils_4.0.2     xfun_0.25      
##   yaml_2.2.1
```

Package names are in bold text (e.g., **rmarkdown**), and inline code and filenames are formatted in a typewriter font (e.g., `knitr::knit('foo.Rmd')`). Function names are followed by parentheses (e.g., `bookdown::render_book()`).

## Acknowledgments {-}

A lot of people helped me when I was writing the book.

\BeginKnitrBlock{flushright}<p class="flushright">Frida Gomam  
on the Mars</p>\EndKnitrBlock{flushright}


<!--chapter:end:index.Rmd-->

# About the Author {-}

Frida Gomam is a famous lady. Police will always let her go.

<!--chapter:end:00-author.Rmd-->


# Introduction

Placeholder



<!--chapter:end:01-introduction.Rmd-->

# The FOO Method

We talk about the _FOO_ method\index{FOO} in this chapter.


<!--chapter:end:02-foo.Rmd-->

\cleardoublepage 

# (APPENDIX) Appendix {-}

# More to Say

Yeah! I have finished my book, but I have more to say about some topics. Let me explain them in this appendix.

To know more about **bookdown**, see https://bookdown.org.

<!--chapter:end:90-more.Rmd-->

# References {-}




<!--chapter:end:99-references.Rmd-->

