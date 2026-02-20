# BUILDLOG

### v0.1.0: Miguel Julio Rodo (2026-02-20 19:54:06)

**Description**

Add question bank questions and answers

**Metadata**

- Total time: 
30s
- `projr` profile: 
default

**System Resources**

- OS: Linux 6.6.87.2-microsoft-standard-WSL2
- OS Version: #1 SMP PREEMPT_DYNAMIC Thu Jun  5 18:30:46 UTC 2025
- Architecture: x86_64
- Platform: x86_64-pc-linux-gnu
- CPU Cores: 20
- Total RAM: 15Gi
- Disk Space: 1007G total, 820G available

**`projr` config**

```yaml
directories:
  raw-reference:
    path: _reference
  raw-img:
    path: _raw/img
  raw-data:
    path: _raw/data
  raw-other:
    path: _raw/other
  cache:
    path: _tmp
  output:
    path: _output
  docs:
    path: docs
build:
  git: yes
  github:
    latest-2026:
      content:
      - raw-img
      - raw-other
      structure: latest
    slides-2026:
      content: docs
      structure: latest
    archive-2026:
      content:
      - raw-img
      - raw-other
dev:
  scripts:
  - QuestionBankAnswers.qmd
  - QuestionBankQuestions.qmd

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
 [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C              
 [3] LC_TIME=en_US.UTF-8        LC_COLLATE=en_US.UTF-8    
 [5] LC_MONETARY=en_US.UTF-8    LC_MESSAGES=en_US.UTF-8   
 [7] LC_PAPER=en_US.UTF-8       LC_NAME=C                 
 [9] LC_ADDRESS=C               LC_TELEPHONE=C            
[11] LC_MEASUREMENT=en_US.UTF-8 LC_IDENTIFICATION=C       

time zone: Etc/UTC
tzcode source: system (glibc)

attached base packages:
[1] stats     graphics  grDevices datasets  utils     methods   base     

loaded via a namespace (and not attached):
 [1] vctrs_0.7.1       httr_1.4.8        cli_3.6.5         knitr_1.50       
 [5] rlang_1.1.7       xfun_0.54         processx_3.8.6    renv_1.1.7.9000  
 [9] jsonlite_2.0.0    gitcreds_0.1.2    glue_1.8.0        rprojroot_2.1.1  
[13] htmltools_0.5.9   quarto_1.5.1      ps_1.9.1          rmarkdown_2.30   
[17] evaluate_1.0.5    tibble_3.3.0      ini_0.3.1         fastmap_1.2.0    
[21] yaml_2.3.12       lifecycle_1.0.5   projr_0.4.1       compiler_4.5.2   
[25] fs_1.6.6          Rcpp_1.1.1        pkgconfig_2.0.3   rstudioapi_0.18.0
[29] later_1.4.6       gh_1.5.0          digest_0.6.39     R6_2.6.1         
[33] parallel_4.5.2    curl_7.0.0        pillar_1.11.1     magrittr_2.0.4   
[37] tools_4.5.2      
```

----

