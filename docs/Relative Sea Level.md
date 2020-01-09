##General Information
**Site name** - Name of the site. This could be a local geographic name, or the name of the town/city where the site is located.</br>
**Subsite** - Subsite, transect, geological section or outcrop identification name.</br>
**Nation** - The nation where the site is located.</br>
**Region** - The administrative region or province where the site is located.</br>
**Main reference** - Select the main reference reporting the site, i.e., the paper from which RSL information has been extracted.</br>
**Additional References** - Select further references describing the site. Ideally this field includes all the historical references reporting on the site.</br>
**Latidude (decimal degrees)** - Latitude of the site, in decimal degrees.</br>
**Longitude (decimal degrees)** - Longitude of the site, in decimal degrees.</br>
**Horizontal Positioning Technique** - Select the Horizontal positioning technique used to establish the site Lat/Long coordinates. New positioning techniques can be added as necessary, referring to the [Geographic positioning](Geographic positioning.md) table.</br>
**Is this a marine/terrestrial limiting record?** - Indicate if the record inserted is a marine or terrestrial limiting, or a sea level indicator. The following fields will update accordingly. For a definition of marine/terrestrial limiting in MIS 5e, see Rovere et al., 2016[^1]. See *Figure 1* for an example</br>
**Type of RSL Indicator** - Sea level indicator that was reported at the site. New indicators can be added from to the [Type of RSL indicator](Type of RSL indicator.md) table.</br></br>

<center><img src="https://raw.githubusercontent.com/Alerovere/WALIS_Help/master/docs/img/Terr_mar_limiting.JPG" width="800" height="200"></br>
*Figure 1. Graphical representation of Marine and Terrestrial limitind vs Sea Level Indicators, from Rovere et al., 2016[^1].*</center>

##Elevation and Paleo RSL
**Upper limit of modern analog (m)** - Insert here the highest elevation at which the modern analog is found. </br>
**Lower limit of modern analog (m)** - Insert here the lowest elevation at which the modern analog is found.</br>
**Quantification of Indicative meaning** - Indicate how the indicative meaning has been quantified. Two selections are possible:</br>
-IMCalc - Using the tool developed by Lorscheid and Rovere (2019)[^2].</br>
-Modern analog data - From modern analog data available for the study area. See example in Rovere et al., 2016[^1].</br>
**Sea level datum** - Sea level datum to which the elevations are referred. New sea level datums can be added from the [Sea Level Datum](Sea Level Datum.md) table.</br>
**Elevation measurement technique** - Method employed to measure elevations. New techniques can be added from the [Elevation Measurement](Elevation measurement.md) table.</br>
**Do you want to insert upper and lower elevation limits?** -  Select "Yes" if the sea level indicator was measured as two-points elevation (*Figure 2*).</br>
**Lower elevation of indicator** - The lower measured elevation of the sea level indicator, as shown in *Figure 2*</br>
**Upper elevation of indicator** - The upper measured elevation of the sea level indicator, as shown in *Figure 2*</br>
**Upper/Lower elevation measurement error (m)** - Insert here the elevation measurement error for the Upper and Lower elevation measurements. Insert ±1-sigma values.</br>
**RSL indicator elevation (m)** - Elevation of RSL indicator (single-point case).</br>
**RSL indicator elevation error (m)** - Elevation error associated with RSL indicator (single-point case).</br></br>

<center><img src="https://github.com/Alerovere/WALIS_Help/blob/master/docs/img/Limits.jpg?raw=true"  width="500" height="200"></br>
*Figure 2. Graphical representation of single point (default) vs two-point elevation.*</center>

**Notes on elevation** - Insert comments on how elevation data has been obtained / treated.</br>
**Reference Water Level (m)** - This value is auto-calculated from the previous ones, only if 'Sea level indicator' has been chosen in the 'Is this a marine/terrestrial limiting record?' field.</br>
**Indicative Range (m)** - This value is auto-calculated from the previous ones, only if 'Sea level indicator' has been chosen in the 'Is this a marine/terrestrial limiting record?' field.</br>
**Paleo Relative Sea Level (m)** - This value is auto-calculated from the previous ones, only if 'Sea level indicator' has been chosen in the 'Is this a marine/terrestrial limiting record?' field.</br>
**Paleo Relative Sea Level Uncertainty (m)** - This value is auto-calculated from the previous ones, only if 'Sea level indicator' has been chosen in the 'Is this a marine/terrestrial limiting record?' field.</br>
**Is data on vertical land movements (independent from the sea level record) available?** - Select 'Yes' or 'No' depending on the available data. If 'Yes' is selected, a new tab will open to insert vertical land movements accordingly.</br>

##Vertical Land Movements
***This tab is open only if 'Yes' is selected in the field above.***</br>
**Tectonic category** - Select the tectonic category from a dropdown menu.</br>
**Tectonic category comments** - Comments on the tectonic category selection.</br>
**Published VLM rate (m/ky)** - Vertical land motion rate as reported in the original study.</br>
**Published VLM rate uncertainty (m/ky)**- Vertical land motion rate uncertainty as reported in the original study.</br>
**Interpreted VLM rate (m/ky)** - Vertical land motion rate, if re-calculated from the original study.</br>
**Interpreted VLM rate (m/ky) uncertainty** - Vertical land motion rate uncertainties, if re-calculated from the original study.</br>
**Comments on VLM rates** - Insert here any further comment on vertical land motion rates.</br>

##Age Constraints
**Age attribution** - Select one age attribution method from the list. The space below will populate accordingly.</br>
**U-series ages** - Select one or more U-series ages. New ages can be added in the 'U-Series' table.</br>
**Amino Acid Racemization** - Select one or more AAR ages. New ages can be added in the 'AAR' table.</br>
**Luminescence** - Select one or more Luminescence ages. New ages can be added in the 'Luminescence' table.</br>
**Electro Spin Resonance** - Select one or more ESR ages. New ages can be added in the 'ESR' table.</br>
**Stratigraphic context/age** - Select one or more stratigraphic context ages. New ages can be added in the 'Chronostratigraphy' table.</br>
**Other age constraints** - Select one or more other age constraints. New ages can be added in the 'Other age constraints' table.</br>

##Quality
**Quality of RSL data** - Rate the quality of the record for which concents RSL data, on a 1 (poor) to 5 (excellent) scale. If the record is rejected, select 0 stars and insert the reason for rejection below. A guide on the evaluation of quality can be found in *Table 1*</br>
**Quality of age information** - Rate the quality of the record for which concerns age information, on a 1 (poor) to 5 (excellent) scale. If the record is rejected, select 0 stars and insert the reason for rejection below. A guide on the evaluation of quality can be found in *Table 2*</br>
**Quality notes** - Detail the reason for the quality score assigned to the record or the reason for rejection.</br></br>

*Table 1. Guidelines for the evaluation of RSL data quality.*

| Description                                                                                                                                                    | Quality rating |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| Elevation precisely measured, referred to a clear datum and RSL indicator with a very narrow indicative range. Final RSL uncertainty is submetric.             | 5 (excellent)  |
| Elevation precisely measured, referred to a clear datum and RSL indicator with a narrow indicative range. Final RSL uncertainty is between one and two meters. | 4 (good)       |
| Uncertainties in elevation, datum or indicative range sum up to a value between two and three meters.                                                          | 3 (average)    |
| Final paleo RSL uncertainty is higher than three meters                                                                                                        | 2 (poor)       |
| Elevation and / or indicative range must be regarded as very uncertain due to poor measurement / description / RSL indicator quality                           | 1 (very poor)  |
| There is not enough information to accept the record as a valid RSL indicator (e.g. marine or terrestial limiting)                                             | 0 (rejected)   |

*Table 2. Guidelines for the evaluation of age information quality.*

| Description                                                                                                                    | Quality rating |
|--------------------------------------------------------------------------------------------------------------------------------|----------------|
| Very narrow age range, e.g. few ka, that allow the attribution to a specific timing within a substage of MIS 5 (e.g. 117±2 ka) | 5 (excellent)  |
| Narrow age range, allowing the attribution to a specific substage of MIS 5 (e.g., MIS 5e)                                      | 4 (good)       |
| The RSL data point can be attributed only to a generic interglacial (e.g. MIS 5)                                               | 3 (average)    |
| Only partial information or minimum age constraints are available                                                              | 2 (poor)       |
| Different age constraints point to different interglacials                                                                     | 1 (very poor)  |
| Not enough information to attribute the RSL data point to any pleistocene interglacial.                                        | 0 (rejected)   |

[^1]: Rovere, A., Raymo, M.E., Vacchi, M., Lorscheid, T., Stocchi, P., Gomez-Pujol, L., Harris, D.L., Casella, E., O'Leary, M.J. and Hearty, P.J., 2016. The analysis of Last Interglacial (MIS 5e) relative sea-level indicators: Reconstructing sea-level in a warmer world. Earth-Science Reviews, 159, pp.404-427.
[^2]: Lorscheid T, Rovere A (2019) The indicative meaning calculator – quantification of paleo sea-level relationships by using global wave and tide datasets. Open Geospatial Data, Softw Stand 4:10. doi: 10.1186/s40965-019-0069-8