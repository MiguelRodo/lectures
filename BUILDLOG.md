# BUILDLOG

### v0.1.0: Miguel J. Rodo (2026-07-27 19:00:10)

**Description**

Add initial content

**Metadata**

- Total time: 
1min 2s
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
  scripts:
  - l1/SlidesL1PCA.qmd
  - l1/PracL1PCA.qmd
  github:
    archive-2026-sta5077z:
      content:
      - raw-data
      - raw-reference-non-git
      - docs
    latest-2026-sta5077z:
      content: raw-content
dev:
  scripts: l1/PracL1PCA.qmd

```

**Session info**

```
R version 4.6.1 (2026-06-24)
Platform: x86_64-pc-linux-gnu
Running under: Ubuntu 24.04.4 LTS

Matrix products: default
BLAS:   /usr/lib/x86_64-linux-gnu/openblas-pthread/libblas.so.3 
LAPACK: /usr/lib/x86_64-linux-gnu/openblas-pthread/libopenblasp-r0.3.26.so;  LAPACK version 3.12.0

locale:
 [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C               LC_TIME=en_US.UTF-8        LC_COLLATE=en_US.UTF-8     LC_MONETARY=en_US.UTF-8   
 [6] LC_MESSAGES=en_US.UTF-8    LC_PAPER=en_US.UTF-8       LC_NAME=C                  LC_ADDRESS=C               LC_TELEPHONE=C            
[11] LC_MEASUREMENT=en_US.UTF-8 LC_IDENTIFICATION=C       

time zone: Etc/UTC
tzcode source: system (glibc)

attached base packages:
[1] grid      stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] lubridate_1.9.5 forcats_1.0.1   stringr_1.6.0   readr_2.2.0     tidyverse_2.0.0 ggrepel_0.9.8   cowplot_1.2.0   ggplot2_4.0.3   purrr_1.2.2     tidyr_1.3.2    
[11] dplyr_1.2.1     tibble_3.3.1   

loaded via a namespace (and not attached):
 [1] gtable_0.3.6       xfun_0.60          remotes_2.5.0      gh_1.6.0           processx_3.9.0     callr_3.8.0        tzdb_0.5.0         projr_0.5.2-10    
 [9] vctrs_0.7.3        tools_4.6.1        pak_0.10.0         ps_1.9.3           generics_0.1.4     curl_7.1.0         parallel_4.6.1     pkgconfig_2.0.3   
[17] RColorBrewer_1.1-3 S7_0.2.2           lifecycle_1.0.5    ini_0.3.1          compiler_4.6.1     farver_2.1.2       textshaping_1.0.5  htmltools_0.5.9   
[25] usethis_3.2.1      yaml_2.3.12        later_1.4.8        pillar_1.11.1      tidyselect_1.2.1   digest_0.6.39      stringi_1.8.7      labeling_0.4.3    
[33] quarto_1.5.1       rprojroot_2.1.1    fastmap_1.2.0      cli_3.6.6          magrittr_2.0.5     utf8_1.2.6         withr_3.0.3        scales_1.4.0      
[41] timechange_0.4.0   rmarkdown_2.31     httr_1.4.8         gitcreds_0.1.2     jpeg_0.1-11        otel_0.2.0         ragg_1.5.2         hms_1.1.4         
[49] evaluate_1.0.5     knitr_1.51         rlang_1.3.0        Rcpp_1.1.2         glue_1.8.1         rstudioapi_0.19.0  jsonlite_2.0.0     R6_2.6.1          
[57] systemfonts_1.3.2  fs_2.1.0          
```

----

