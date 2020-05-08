# wintercrop_albedo
Changes in albedo and latent heat flux with conversion to winter cover crops

## general information
This repository houses data from an experiment at the USDA research station in Lubbock, Texas examining the effect of conversion to winter cover crops on albedo and latent heat flux. The dataset corresponds to the article *Winter cover crops increase winter albedo and latent heat flux in a Texas High Plains agro-ecosystem* by McNellis and Smith. [link to article to be added following publication]

## authors
Risa McNellis (risa.mcnellis@gmail.com) and Nick Smith (nick.gregory.smith@gmail.com)

## DOI badge

## folder descriptions
### /data
This folder contains all of the data files.

## file descriptions
### /data/seasonal_albedo_leaf.csv
This file contains stomatal conductance, leaf chlorophyll, leaf thickness, leaf area, and leaf mass. The specific column information is:
- *date*: the date of measurement, corresponds to *date* column in all other files
- *ID*: the sample ID indicating date_species_plot, corresponds to *ID* column in all other files
- *rep*: the replicate within the plot
- *conductance*: stomatal conductance measured with a Meter Porometer SC-1 (mmol m<sup>-2</sup> s<sup>-1</sup>)
- *temperature*: leaf temperature measured with a Meter Porometer SC-1 (degrees Celsius)
- *leaf_angle*: the angle of the leaf from 0 - 90 measured with a PhotosynQ MultispeQ v2 (degrees)
- *rel_chlorophyll*: relative chlorophyll content measured with a PhotosynQ MultispeQ v2 using a modified version of the SPAD parameter
- *thickness*: thickness of the leaf measured with a PhotosynQ MultispeQ v2 (µm)
- *leaf_area*: area of leaf (mm<sup>2</sup>)
- *leaf_mass*: mass of leaf (mg)

### /data/seasonal_albedo_radiation.csv
This file contains minimum, maximum, and average one-minute incoming and reflected shortwave radiation measured with a Kipp & Zonen SMP3. The specific column information is:
- *date*: the date of measurement, corresponds to *date* column in all other files
- *time*: the time of measurement
- *ID*: the sample ID indicating date_species_plot, corresponds to *ID* column in all other files
- *refl_rad_min*: minimum one-minute reflected radiation (W m<sup>-2</sup>)
- *refl_rad_avg*: average one-minute reflected radiation (W m<sup>-2</sup>)
- *refl_rad_max*: maximum one-minute reflected radiation (W m<sup>-2</sup>)
- *in_rad_min*: minimum one-minute incoming radiation (W m<sup>-2</sup>)
- *in_rad_avg*: average one-minute incoming radiation (W m<sup>-2</sup>)
- *in_rad_max*: maximum one-minute incoming radiation (W m<sup>-2</sup>)

### /data/seasonal_albedo_site.csv
This file contains plot data including species, planting date, leaf area index, soil moisture, plant height, and soil albedo. The specific column information is:
- *date*: the date of measurement, corresponds to *date* column in all other files
- *DOY*: the measurement day of year
- *ID*: the sample ID indicating site_species_plot, corresponds to *ID* column in all other files
- *cover_type*: the type of cover using the USDA symbol for species, where FAL is fallow, SECE is *Secale cereale* (rye), and TRITI2 is *xTriticosecale [Secale x Triticum]* (triticale)
- *plant_date*: the approximate planting date
- *clear_sky*: visual estimate of the percent of sky free of clouds during measurement period (%)
- *LAI*: leaf area index measured with a Li-Cor LAI-2200C (m<sup>2</sup> m<sup>-2</sup>)
- *VWC*: volumetric water content measured with a Delta T Devices HH2 Moisture Meter and ML3 Theta Probe (m<sup>3</sup> m<sup>-3</sup>)
- *plant_height*: height of  tallest plant in the plot (cm)
- *soil_L*: CIELAB color space lightness (L) value of soil
- *soil_a*: CIELAB color space green to red (a) value of soil
- *soil_b*: CIELAB color space blue to yellow (b) value of soil
- *soil_value*: Munsell value of soil
- *soil_alb*: albedo of soil
