Readme

Title: "Craft Beer:Alcohol Content and Bitterness Preference Analysis
Authors: "Michael Catalano + Hayley Horn"
Date: "October 20, 2018"
Due: Thursday, October 18th 2018 One hour before live session. 

Purpose
    This analysis focuses craft beer data, analysing the data on two measurements of beer composition, and some geographic details. The first measurement is Alcohol By Volume (ABV) which is a percentage that represents how much of a beer is alcohol versus other ingredients. The other measurement we will consider is International Bitterness Units (IBU) which is measured on a scale of 0 to 100 and describes the bitterness from hops in a beer. 

Role in Readme creation
     Hayley typed with Michael's input

Inputs
    The Beers dataset contains a list of 2,410 US craft beers and Breweries dataset contains 558 US breweries. The datasets descriptions are as follows.

    Beers.csv
     Name: Name of the beer.
     Beer_ID: Unique identifier of the beer.
     ABV: Alcohol by volume of the beer.
     IBU: International Bitterness Units of the beer.
     Brewery_ID: Brewery id associated with the beer.
     Style: Style of the beer.
     Ounces: Ounces of beer.

    Breweries.csv
     Brew_ID: Unique identifier of the brewery.
     Name: Name of the brewery.
     City: City where the brewery is located.
     State: U.S. State where the brewery is located.

Objects
    ABV_IBU_combined: Merge of ABV_state and IBU_state, by  the field "State"
    ABV_state: Aggregation of the ABV data from BandBs
    ABV_state_sorted: a sorted version of ABV_State
    BandBs: The combination of the Brew and Beer dataframes on the field "Brew_ID"
    Beer:  Contains the initial data from the beer.csv 
    Brew: Contains the data from the brewery.csv
    Brew_summary:  a dataframe for the summary of breweries from the breweries file
    IBU_state: Aggregation of the IBV data from BandBs
    IBU_state_sorted: a sorted version of IBU_State
    na_BandBs : this object counts the NAs in each field of the BandBs data set.

Outputs
     Craft_Beer_Analysis.Rmd
     Craft_Beer_Analysis_Catalano_Horn.html
     Craft Beer Analysis_Presentation_Catalano_Horn.pptx

Software Information
    R version 3.5.1 (2018-07-02)
    Platform: x86_64-w64-mingw32/x64 (64-bit)
    Running under: Windows >= 8 x64 (build 9200)

    Matrix products: default

    locale:
    [1] LC_COLLATE=English_United States.1252  LC_CTYPE=English_United States.1252   
    [3] LC_MONETARY=English_United States.1252 LC_NUMERIC=C                          
    [5] LC_TIME=English_United States.1252    

    attached base packages:
    [1] stats     graphics  grDevices utils     datasets  methods   base     

    other attached packages:
    [1] data.table_1.11.8

    loaded via a namespace (and not attached):
    [1] Rcpp_0.12.19     rstudioapi_0.8   bindr_0.1.1      knitr_1.20       magrittr_1.5     tidyselect_0.2.4
    [7] munsell_0.5.0    colorspace_1.3-2 R6_2.3.0         rlang_0.2.2      stringr_1.3.1    plyr_1.8.4      
    [13] dplyr_0.7.6      tools_3.5.1      grid_3.5.1       gtable_0.2.0     htmltools_0.3.6  rprojroot_1.3-2 
    [19] yaml_2.2.0       lazyeval_0.2.1   assertthat_0.2.0 digest_0.6.17    tibble_1.4.2     crayon_1.3.4    
    [25] bindrcpp_0.2.2   purrr_0.2.5      ggplot2_3.0.0    htmlwidgets_1.3  rsconnect_0.8.8  evaluate_0.11   
    [31] glue_1.3.0       rmarkdown_1.10   stringi_1.1.7    compiler_3.5.1   pillar_1.3.0     backports_1.1.2 
    [37] scales_1.0.0     pkgconfig_2.0.2 

