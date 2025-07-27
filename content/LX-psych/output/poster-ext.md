---
# title: "xtitle: coherence & presuppositions observations in :schizophrenia: threads"
# author: "st. schwarz"
# date: "2025-07-27"
# output: 
#     # bookdown::html_document2:
#     #   base_format: tufte::tufte_html
#     #   keep_md: true
#     #   self_contained: true
#     bookdown::tufte_html_book:
#       keep_md: true
#       toc: true
#       css: ../../bookdown/assets/style.css
#      # self_contained: true
# 
#     # #fig_path: "plots/"
#   # md_document:
#   #   variant: markdown_github
#   #   pandoc_args: ["--wrap=none"]
# 
#   #keep_md: yes
# bibliography: /Users/guhl/Documents/GitHub/SPUND-LX/psych/HA/poster/psych.bib
# nocite: '@*'
#keep_md: true
---



<style type="text/css">
/*table {
  width: 100% !important;
  
}*/
pre {
border: 1px solid black;
border-radius: 0.25rem;
background-color: rgba(0, 0, 0, 0.04);

}
</style>





# top
eval output M11, normalised to obs, distance ceiling =  outliers removed.

## legende

``` r
legend<-data.frame(variable=c("target","q","det",paste0("q:",letters[1:6])),
                   explanation=c("corpus","condition","antecedent POS==DET",rep("query condition",6)),
                   values=c("obs,ref","a,b,c,d,e,f","TRUE,FALSE",
                            ".*","this,that,those,these","the","a,an,any,some","my","his,her,their,your")
                   )
#library(kableExtra)

# k<-kable(legend,caption = "model vars")
# k<-kable_styling(k,full_width = TRUE)
# k
kable(legend, caption = "model vars",format="markdown")
```

## anova analysis
### anova plain, formula: [``` dist_rel_obs ~ target*q*det ```]


### anova of linear regression model: [`anova(summary(lmer))`]



### linear regression coefficients, formula: [``` dist_rel_obs ~ target*q*det+(1|lemma)+(1|aut_id) ```]


## plots
<div class="figure">
<img src="poster-ext_files/figure-html/boxplot1-1.png" alt="compare distances by corpus, normalised to obs, distance ceiling =  outliers removed" width="672" />
<p class="caption">(\#fig:boxplot1)compare distances by corpus, normalised to obs, distance ceiling =  outliers removed</p>
</div>

<div class="figure">
<img src="poster-ext_files/figure-html/barplot-median-1.png" alt="mean distances over query/corpus, normalised to obs, distance ceiling =  outliers removed" width="672" />
<p class="caption">(\#fig:barplot-median)mean distances over query/corpus, normalised to obs, distance ceiling =  outliers removed</p>
</div>





<div class="figure">
<img src="poster-ext_files/figure-html/barplot-mean-1.png" alt="median distances over query/corpus, normalised to obs, distance ceiling =  outliers removed" width="672" />
<p class="caption">(\#fig:barplot-mean)median distances over query/corpus, normalised to obs, distance ceiling =  outliers removed</p>
</div>

<div class="figure">
<img src="poster-ext_files/figure-html/lmeplot-1.png" alt="distances relation, normalised to obs, distance ceiling =  outliers removed" width="672" />
<p class="caption">(\#fig:lmeplot)distances relation, normalised to obs, distance ceiling =  outliers removed</p>
</div>

<div class="figure">
<img src="poster-ext_files/figure-html/gplot-1.png" alt="distances normalised vs. raw" width="672" />
<p class="caption">(\#fig:gplot)distances normalised vs. raw</p>
</div>
-----

# REF
literature used and alii...   


