map
================
Shengzhi Luo
05/12/2021

# Data loading

``` r
crime_2016 =
   read.csv("./Data/Crimes_-_2016.csv") %>% 
   drop_na() %>% 
   janitor::clean_names() %>%
   filter(arrest=="true",domestic=="true")
crime_2017 =
   read.csv("./Data/Crimes_-_2017.csv") %>% 
   drop_na() %>% 
   janitor::clean_names() %>%
   filter(arrest=="true",domestic=="true")
crime_2018 =
   read.csv("./Data/Crimes_-_2018.csv") %>% 
   drop_na() %>% 
   janitor::clean_names() %>%
   filter(arrest=="true",domestic=="true")
crime_2019 =
   read.csv("./Data/Crimes_-_2019.csv") %>% 
   drop_na() %>% 
   janitor::clean_names() %>%
   filter(arrest=="true",domestic=="true")
crime_2020 =
   read.csv("./Data/Crimes_-_2020.csv") %>% 
   drop_na() %>% 
   janitor::clean_names() %>%
   filter(arrest=="true",domestic=="true")
crime_2021 =
   read.csv("./Data/Crimes_-_2021.csv") %>% 
   drop_na() %>% 
   janitor::clean_names() %>%
   filter(arrest=="true",domestic=="true")
```
