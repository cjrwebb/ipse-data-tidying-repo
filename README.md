# Investing in Prevention: Data Tidying Repository

Cite as: Webb, Calum (2024). Investing in Prevention & Support: Data tidying script and repository. The University of Sheffield. Dataset. https://doi.org/10.15131/shef.data.26348359

This is a published Open Data Repository for the IPSE Project (British Academy Postdoctoral Fellowship grant no. PF21\\210024)

This repository was last tested to recreate the merged administrative data files used in the Investing in Prevention project on 8th May 2024, with the following system:

```
R version 4.2.1 (2022-06-23)
Platform: x86_64-apple-darwin17.0 (64-bit)
Running under: macOS 14.3.1

Matrix products: default
LAPACK: /Library/Frameworks/R.framework/Versions/4.2/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] patchwork_1.2.0 janitor_2.2.0   lubridate_1.9.2 forcats_1.0.0   stringr_1.5.1   dplyr_1.1.4     purrr_1.0.2    
 [8] readr_2.1.4     tidyr_1.3.0     tibble_3.2.1    ggplot2_3.5.0   tidyverse_2.0.0

loaded via a namespace (and not attached):
 [1] cellranger_1.1.0  pillar_1.9.0      compiler_4.2.1    tools_4.2.1       bit_4.0.5         lifecycle_1.0.4  
 [7] gtable_0.3.4      timechange_0.2.0  pkgconfig_2.0.3   rlang_1.1.2       cli_3.6.2         rstudioapi_0.15.0
[13] parallel_4.2.1    withr_3.0.0       generics_0.1.3    vctrs_0.6.5       hms_1.1.3         bit64_4.0.5      
[19] grid_4.2.1        tidyselect_1.2.1  glue_1.7.0        snakecase_0.11.0  R6_2.5.1          fansi_1.0.6      
[25] readxl_1.4.2      vroom_1.6.3       farver_2.1.1      tzdb_0.4.0        magrittr_2.0.3    scales_1.3.0     
[31] colorspace_2.1-0  labeling_0.4.3    utf8_1.2.4        stringi_1.8.3     munsell_0.5.0     crayon_1.5.2    
```

The repository contains the `data-tidying.R` script, which includes all of the steps taken to tidy, rebase, combine, and transform all of the data at the local authority level used in the project. This script can be run from start to finish in order to generate the `merged-data.csv` file and accompanying codebook used throughout the project.

The `data` folder contains a record of all of the original data and sources (in each `source.txt` file) of these data. Unless otherwise stated, these data are published under the Open Government License by their relevant departments. This allows for every data point in the research study to be tracked back to its origin. 

