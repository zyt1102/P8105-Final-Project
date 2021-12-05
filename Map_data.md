Map Data
================
Yiwen Zhao
12/1/2021

``` r
library(tidyverse)
```

``` r
read_csv("/Users/zhao/Desktop/P8105-Final-Project/Crimes_-_Map.csv")
```

    ## Rows: 203280 Columns: 17

    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (11): CASE#, DATE  OF OCCURRENCE, BLOCK, IUCR, PRIMARY DESCRIPTION, SECO...
    ## dbl  (6): BEAT, WARD, X COORDINATE, Y COORDINATE, LATITUDE, LONGITUDE

    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

    ## # A tibble: 203,280 × 17
    ##    `CASE#`  `DATE  OF OCCURRENCE`  BLOCK IUCR  `PRIMARY DESCRI… `SECONDARY DESC…
    ##    <chr>    <chr>                  <chr> <chr> <chr>            <chr>           
    ##  1 JE266628 06/15/2021 09:30:00 AM 080X… 0820  THEFT            $500 AND UNDER  
    ##  2 JE266536 06/15/2021 07:50:00 AM 042X… 0560  ASSAULT          SIMPLE          
    ##  3 JE266663 06/15/2021 08:40:00 AM 044X… 1153  DECEPTIVE PRACT… FINANCIAL IDENT…
    ##  4 JE267466 06/15/2021 09:01:00 PM 007X… 051B  ASSAULT          AGGRAVATED - OT…
    ##  5 JE266473 06/15/2021 07:47:00 AM 062X… 0110  HOMICIDE         FIRST DEGREE MU…
    ##  6 JE267222 06/15/2021 01:55:00 AM 015X… 4386  OTHER OFFENSE    VIOLATION OF CI…
    ##  7 JE266604 06/15/2021 09:20:00 AM 013X… 0430  BATTERY          AGGRAVATED - OT…
    ##  8 JE266568 06/15/2021 01:30:00 AM 055X… 0810  THEFT            OVER $500       
    ##  9 JE267023 06/15/2021 03:03:00 PM 082X… 0460  BATTERY          SIMPLE          
    ## 10 JE267234 06/15/2021 04:45:00 PM 107X… 0486  BATTERY          DOMESTIC BATTER…
    ## # … with 203,270 more rows, and 11 more variables: LOCATION DESCRIPTION <chr>,
    ## #   ARREST <chr>, DOMESTIC <chr>, BEAT <dbl>, WARD <dbl>, FBI CD <chr>,
    ## #   X COORDINATE <dbl>, Y COORDINATE <dbl>, LATITUDE <dbl>, LONGITUDE <dbl>,
    ## #   LOCATION <chr>
