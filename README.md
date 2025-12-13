# Recruit Rockfish Abundance at Santa Cruz Island Through "The Blob"

This repository contains the final project materials for EDS 222 - *Statistics for Environmental Data Science*.

## About
Rockfish (genus *Sebastes*) are an important commercial and recreational fishing target on the west coast. The early life stages of Rockfish are spent in the water column until they grow strong enough to swim to structure. With global ocean temperatures increasing, I aim to analyze how increases in water temperature during Pelagic Larval Duration (PLD) affects the abundance of new rockfish, or Young of Year (YOY). I will utilize timeseries data of YOY abundance collected at the Northern Channel Islands. During data collection, California experienced a marine heatwave often referred to as "The Blob" during 2014-2016. I will analyze the effects of temperature on YOY abundance from 2012 to 2019 in order to determine if the warmer waters during the Blob influenced abundance and give insight to how the population may change has global ocean temperatures increase due to climate change. Additionally, I will incorporate the impacts of upwelling, which supplies nutrients to YOY during the PLD.

## About the data

The data quantifying Rockfish recruitment comes from the Partnership of Interdisciplinary Sciences of Coastal Oceans (PISCO) long-term fish recruitment monitoring in the Channel Islands. The YOYs were collected using Standardized Monitoring Units for the Recruitment of Fishes (SMURFs) that were placed just off the coast of the Northern Channel Islands in an attempt to collect recruit fish as they swam to structure. Monitoring took place from 2000-2018, with collections occuring year round starting in 2012.

NOAA data is used to quantify temperature with Sea Surface Temperature (SST) lag 30 days from time of collection to predict SST during PLD. Upwelling was quanitified using the Biological Effective Upwelling Transport Index (BEUTI) lag 30 days. 

## Hypotheses

H0: Temperature has no effect on rockfish recruitment

Ha: Increased temperature has an effect on rockfish recruitment

## Statistical Notation
$$FishPresence ~ binomial(1, p)$$ 
$$logit(p) = B0 + B1 * SST$$

$$Fishcount ~ NegativeBinomial(\mu, \theta)$$ 
$$log(\mu) = B2 + B3 * SST$$

## References
ERDDAP - SST, Aqua MODIS, NPP, 0.0125°, West US, Day time (11 microns), 2002-present (1 Day Composite) - Data Access Form. (2016). Noaa.gov. https://coastwatch.pfeg.noaa.gov/erddap/griddap/erdMWsstd1day.html

Jennifer E. Caselle, Peter M. Carlson, Chris Honeyman, Avrey Parsons-Field, & Katie D. Koehn. (2020). PISCO UCSB Subtidal Fish Recruitment Data. PISCO MN. doi:10.6085/AA/PISCO_UCSB_Fish_Recruitment.1.3.

