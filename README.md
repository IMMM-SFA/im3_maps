# im3_maps
Common maps that can be used by all IM3 participants

# Available maps

## Population per square kilometer; interconnection, US state, and PCA boundaries
(https://github.com/IMMM-SFA/im3_maps/blob/master/maps/conus_1km2-popdensity-2000-oneill_with-iconn-ba-state_nolabels.jpg)

## Population per square kilometer; interconnection, US state, and PCA boundaries - with PCA labels

# References and metadata

## Cartographic data
The following maps were built using [Natural Earth](https://www.naturalearthdata.com/downloads/) physical and cultural boundaries and accessed on April 10, 2019.

## Population data
Population data was assembled by Brian Kauffman, NCAR, September 2017.  This data is spatially explicit population scenario data (years 2010 thru 2100 in ten year increments) that is consistent with the Shared Socioeconomic Pathways (SSPs) and downscaled base year data (year 2000). Refer to the following publication for more information:

Jones, B., O’Neill, B.C., 2016. Spatially explicit global population scenarios consistent with the Shared Socioeconomic Pathways. Environmental Research Letters 11, 84003. DOI:10.1088/1748-9326/11/8/084003

This data is internally accessible here:  `/pic/projects/im3/Scenarios/Population/US_1km_projections_170920`

## Bondary data

### ReEDS Balancing Authority Areas (Power Control Areas - PCAs)
ReEDS regions are accessible for download using the [NREL Wind Prospector](https://maps.nrel.gov/wind-prospector/?visible=wind_3tier_site_metadata#/?aL=iBkrSK%255Bv%255D%3Dt&bL=groad&cE=0&lR=0&mC=36.70365959719456%2C-94.8779296875&zL=5).  Regions were spatially dissolved (grouped) by PCA.

### Interconnections
Interconnections boundaries were derived using NERC regions downloaded from [EIA](https://www.eia.gov/maps/layer_info-m.php).  NERC regions were spatially dissolved (grouped) by interconnection with dominance for overlapping regions given to [1] WECC, [2] ERCOT, [3] EIC.
