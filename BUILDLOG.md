# BUILDLOG

### v0.2.0: rstudio (2026-10-26 19:49:54)

**Description**

Revise regression outline and prediction material; fix rendering

**Metadata**

- Total time:
7min 50s
- `projr` profile:
localonly

**System Resources**

- OS: Linux 6.6.87.2-microsoft-standard-WSL2
- OS Version: #1 SMP PREEMPT_DYNAMIC Thu Jun  5 18:30:46 UTC 2025
- Architecture: x86_64
- Platform: x86_64-pc-linux-gnu
- CPU Cores: 8
- Total RAM: 11Gi
- Disk Space: 1007G total, 926G available

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
  scripts:
  - w0/NotesRegProofs.qmd
  - w0/NotesRegW1S0Prereq.qmd
  - w0/OutlineReg.qmd
  - w0/QARegNotesW1S0Prereq.qmd
  - w1/DemRegW1S2IntroEndToEnd.qmd
  - w1/DemRegW1S2IntroScenario.qmd
  - w1/QARegSlidesW1S1Intro.qmd
  - w1/QARegSlidesW1S3IntroMVN.qmd
  - w1/SlidesRegW1S1Intro.qmd
  - w1/SlidesRegW1S3MVN.qmd
  - w2/DocsRegW2GLMMultiple.qmd
  - w2/QARegW2S1LM.qmd
  - w2/SlidesRegW2S1LM.qmd
  - w3/QARegW3S1ConfInt.qmd
  - w3/QARegW3S2HypTest.qmd
  - w3/SlidesRegW3S1ConfIntOrig.qmd
  - w3/SlidesRegW3S2HypTest.qmd
  - w4/DemW4S1ANOVA.qmd
  - w4/FactsRegW4S2ModelChecking.qmd
  - w4/QARegW4S1ANOVA.qmd
  - w4/QARegW4S2ExtraKSSW.qmd
  - w4/QARegW4S2ModelChecking.qmd
  - w4/SlidesRegW4S1ANOVA.qmd
  - w4/SlidesRegW4S2ModelChecking.qmd
  - w5/FactsRegW5S1Transformations.qmd
  - w5/FactsRegW5S2Prediction.qmd
  - w5/QARegW5S1Transformations.qmd
  - w5/QARegW5S2Prediction.qmd
  - w5/SlidesRegW5S1Transformations.qmd
  - w5/SlidesRegW5S2Interactions.qmd
  - w5/SlidesRegW5S3Prediction.qmd
  - w5/SlidesRegW5S4GM.qmd
  - w6/FactsRegW6S1Boot.qmd
  - w6/FactsRegW6S2PCA.qmd
  - w6/SlidesRegW6S1Boot.qmd
  - w6/SlidesRegW6S2PCA.qmd
  git: no
  restrictions:
    not_behind: no
dev:
  scripts: w2/SlidesRegW2S1LM.qmd

```

**Session info**

```
R version 4.4.2 (2024-10-31)
Platform: x86_64-pc-linux-gnu
Running under: Ubuntu 24.04.1 LTS

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
[1] stats     graphics  grDevices utils     datasets  methods   base

other attached packages:
[1] projr_0.5.2-10

loaded via a namespace (and not attached):
 [1] tidyselect_1.2.1             viridisLite_0.4.2
 [3] jsonvalidate_1.5.0           dplyr_1.1.4
 [5] farver_2.1.2                 fastmap_1.2.0
 [7] digest_0.6.37                lifecycle_1.0.4
 [9] Deriv_4.2.0                  survival_3.8-3
[11] processx_3.8.4               magrittr_2.0.3
[13] compiler_4.4.2               rlang_1.1.4
[15] tools_4.4.2                  yaml_2.3.10
[17] knitr_1.49                   labeling_0.4.3
[19] curl_6.0.1                   xml2_1.3.6
[21] RColorBrewer_1.1-3           abind_1.4-8
[23] purrr_1.0.2                  numDeriv_2016.8-1.1
[25] grid_4.4.2                   ggplot2_3.5.2
[27] scales_1.4.0                 MASS_7.3-61
[29] isoband_0.2.7                cli_3.6.6
[31] rmarkdown_2.29               reformulas_0.4.1
[33] generics_0.1.4               rstudioapi_0.17.1
[35] codemeta_0.1.1               modelr_0.1.11
[37] cffr_1.2.0                   minqa_1.2.8
[39] stringr_1.5.1                splines_4.4.2
[41] parallel_4.4.2               vctrs_0.6.5
[43] V8_6.0.4                     boot_1.3-31
[45] Matrix_1.7-1                 jsonlite_1.8.9
[47] SparseM_1.84-2               carData_3.0-5
[49] car_3.1-3                    pbkrtest_0.5.5
[51] ggrepel_0.9.6                Formula_1.2-5
[53] systemfonts_1.2.3            tidyr_1.3.1
[55] glue_1.8.0                   nloptr_2.2.1
[57] ps_1.8.1                     cowplot_1.2.0
[59] stringi_1.8.4                gtable_0.3.6
[61] later_1.4.1                  quarto_1.4.4
[63] lme4_1.1-37                  tibble_3.2.1
[65] pillar_1.10.0                htmltools_0.5.8.1
[67] quantreg_6.1                 doBy_4.7.0
[69] R6_2.5.1                     RcppEigen_0.3.4.0.2
[71] microbenchmark_1.5.0         textshaping_0.4.1
[73] Rdpack_2.6.4                 rprojroot_2.0.4
[75] kableExtra_1.4.0             evaluate_1.0.1
[77] lattice_0.22-6               rbibutils_2.3
[79] backports_1.5.0              broom_1.0.8
[81] MatrixModels_0.5-4           DataTidy23RodoHonsMult_0.9.0
[83] Rcpp_1.0.13-1                svglite_2.2.1
[85] nlme_3.1-166                 xfun_0.49
[87] fs_1.6.5                     pkgconfig_2.0.3
```

----

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

