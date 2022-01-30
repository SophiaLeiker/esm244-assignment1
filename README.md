# ESM 244 Assignment 1

## Part 1

- Data wrangling and visualization

This report will explore amphibian abundance data recorded by the Sierra Lakes Inventory Project. From the Environmental Data Initiative repository: “The Sierra Lakes Inventory Project (SLIP) was a research endeavor that ran from 1995-2002 and has supported research and management of Sierra Nevada aquatic ecosystems and their terrestrial interfaces. We described the physical characteristics of and surveyed aquatic communities for >8,000 lentic water bodies in the southern Sierra Nevada, including lakes, ponds, marshes, and meadows.”

The data used comes from: [Sierra Amphibians Dataset](https://doi.org/10.6073/pasta/d835832d7fd00d9e4466e44eea87fab3) and metadata, including methods used for data collection can be found here [The Sierra Lakes Inventory Project: Non-Native fish and community composition of lakes and ponds in the Sierra Nevada, California](https://portal.edirepository.org/nis/metadataviewer?packageid=edi.577.2).


## Part 2

- Multiple Linear Regression

This report will read in a small subset of seawater sample data from CalCOFI, then compare the performance of two competing linear regression models that predict oxygen saturation based on several physical and chemical variables, using AIC and cross validation.

The analysis will be used to explore the relationship between O2 saturation of seawater off California’s coast and several physical and chemical variables. From the CalCOFI site: “Since 1949, hydrographic and biological data of the California Current System have been collected on CalCOFI cruises. The 70+ year hydrographic time-series includes temperature, salinity, oxygen and phosphate observations. In 1961, nutrient analysis expanded to include silicate, nitrate and nitrite; in 1973, chlorophyll was added; in 1984, C14 primary productivity incubations were added; and in 1993, CTD profiling began.” ([CalCOFI](https://calcofi.org/ccdata.html))


The data used comes from: [CalCOFI](https://calcofi.org/ccdata.html) and a subset of data, including *oxygen saturation*, *temperature of water*, *salinity of water*, *depth in meters*, *acetone extracted chlorophyll-a measured fluorometrically*, *phosphate concentration*, and *nitrate concentration* used for this analysis can be found [here](https://drive.google.com/file/d/1uXS6_enkcCmbIoawkFU8EXvLtomBP2r7/view?usp=sharing).
