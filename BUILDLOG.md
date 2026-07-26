# BUILDLOG

### v0.1.0: Miguel J. Rodo (2026-07-26 19:31:23)

**Description**

Update resources for pre-requisites, L1 and L3

**Metadata**

- Total time: 
1min 30s
- `projr` profile: 
default

**System Resources**

- OS: Linux 6.6.87.2-microsoft-standard-WSL2
- OS Version: #1 SMP PREEMPT_DYNAMIC Thu Jun  5 18:30:46 UTC 2025
- Architecture: x86_64
- Platform: x86_64-pc-linux-gnu
- CPU Cores: 8
- Total RAM: 7.7Gi
- Disk Space: 1007G total, 950G available

**`projr` config**

```yaml
directories:
  raw-data:
    path: _raw_data
  raw-reference-git:
    path: _reference
    ignore-git: no
  raw-reference-non-git:
    path: _reference/non_git
  raw-content:
    path: _content
  docs:
    path: docs
build:
  github:
    slides-2026-sta2005s:
      content:
      - raw-data
      - raw-reference-non-git
      - raw-content
      - docs
      - output
  scripts:
  - w0/OutlineReg.qmd
  - w0/NotesRegW1S0Prereq.qmd
  - w0/QARegNotesW1S0Prereq.qmd
  - w1/SlidesRegW1S1Intro.qmd
  - w1/SlidesRegW1S3MVN.qmd
  - w1/QARegSlidesW1S3IntroMVN.qmd
dev:
  scripts: w1/SlidesRegW1S3MVN.qmd

```

**Session info**

```
R version 4.5.2 (2025-10-31)
Platform: x86_64-pc-linux-gnu
Running under: Ubuntu 24.04.3 LTS

Matrix products: default
BLAS:   /usr/lib/x86_64-linux-gnu/openblas-pthread/libblas.so.3 
LAPACK: /usr/lib/x86_64-linux-gnu/openblas-pthread/libopenblasp-r0.3.26.so;  LAPACK version 3.12.0

locale:
 [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C               LC_TIME=en_US.UTF-8        LC_COLLATE=en_US.UTF-8     LC_MONETARY=en_US.UTF-8    LC_MESSAGES=en_US.UTF-8   
 [7] LC_PAPER=en_US.UTF-8       LC_NAME=C                  LC_ADDRESS=C               LC_TELEPHONE=C             LC_MEASUREMENT=en_US.UTF-8 LC_IDENTIFICATION=C       

time zone: Etc/UTC
tzcode source: system (glibc)

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
[1] ggplot2_4.0.3

loaded via a namespace (and not attached):
 [1] utf8_1.2.6         generics_0.1.4     projr_0.5.2-10     xml2_1.6.0         stringi_1.8.7      digest_0.6.39      magrittr_2.0.5     evaluate_1.0.5     grid_4.5.2        
[10] RColorBrewer_1.1-3 fastmap_1.2.0      rprojroot_2.1.1    jsonlite_2.0.0     processx_3.9.0     ini_0.3.1          ps_1.9.3           httr_1.4.8         viridisLite_0.4.3 
[19] scales_1.4.0       textshaping_1.0.5  cli_3.6.6          rlang_1.3.0        cowplot_1.2.0      withr_3.0.3        yaml_2.3.12        otel_0.2.0         parallel_4.5.2    
[28] tools_4.5.2        dplyr_1.2.1        kableExtra_1.4.1   curl_7.1.0         vctrs_0.7.3        R6_2.6.1           lifecycle_1.0.5    stringr_1.6.0      fs_2.1.0          
[37] ragg_1.5.0         pkgconfig_2.0.3    pillar_1.11.1      later_1.4.8        gtable_0.3.6       glue_1.8.1         gh_1.5.0           Rcpp_1.1.2         systemfonts_1.3.2 
[46] xfun_0.60          tibble_3.3.1       tidyselect_1.2.1   rstudioapi_0.19.0  knitr_1.51         farver_2.1.2       htmltools_0.5.9    quarto_1.5.1       rmarkdown_2.31    
[55] svglite_2.2.2      compiler_4.5.2     S7_0.2.2          
```

----

