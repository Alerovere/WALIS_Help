################################
Samples dated with U-Series
################################

.. note::
	This section was designed by A. Dutton and P. Chutcharavan, based on a previous template by Hibbert et al. (2016, Quaternary Science Reviews)

.. warning::
	The U-Series fields displayed in the interface change according to the different possible choices (e.g., U-Series entered as sea level datapoint from single coral or speleothem, or U-Series age on corals/speleothems/algae or mollusks.

Initial choice
--------------------

**Select the dated material** - Select which dated material will be entered. This field is automatically filled according to the selection in the main menu (corals, mollusks, algae).

**Details on dated material** - Further details on the dated material.

**Select whether U-Series data were recalculated** - Select if only originally reported data area available or they were recalculated.

**Type of spectrometry** - Select if alpha or mass spectrometer.

**Are RSL estimates for the coral available?** - Select if paleo RSL estimates were derived from this single coral record. This field is automatically compiled according to the choices in the interface.

**Do you want to insert data related to tectonics?** - Select if tectonic estimates are available from the single coral record.

Paleo Sea Level
--------------------

.. note::
	This section is only available when RSL datapoint from single coral is selected

**Original elevation datum used** - Select the sea level datum to which the elevations are referred

**Elevation measurement method** - How the elevation of the sample was measured

**Reported elevation (m)** - Elevation of the sample as reported in the original publication. This field accepts text values up to 50 characters. Default is N/A	

**Reported elevation uncertainty (m)** - Elevation uncertainty of the sample as reported in the original publication. This field accepts text values up to 50 characters. Default is N/A

**Interpreted elevation relative to mean sea level (m)** - Elevation of the sample in meters above mean sea level. If not provided in the original publication, calculate it from the reported elevation and the datum used, indicating how the elevation above MSL has been derived.

**Interpreted elevation uncertainty (m)** - Final elevation uncertainty used, including measurement and datum uncertainty

**Interpreted elevation relative to MLLW/MLWS (m)** - Elevation relative to mean lower low water or mean low water springs (sometimes used for coral microatolls)

**Elevation comments** - Comments on elevation 

**Published paleo water depth estimate** - Describe the original paleo depth interpretation	

**Upper limit of living range** - Upper limit of the coral living range. This defines the minimum depth at which the coral can survive or lives in the modern reef.

**Lower limit of living range** - Lower limit of the coral living range. This defines the maximum depth at which the coral lives in the modern reef

**Comments on reported and estimated paleo water depth** - Insert here any additional comment on the paleo water depth entered above	

Ecological metadata
--------------------

.. note::
	This section is only available under U-Series ages on corals or mollusks/algae
	
**Terrace ID** - Identified terrace the sample came from.

**Facies description** - Sedimentary facies context and outcrop information on coral or mollusk sample.

**Reported as in situ?** - If the samples was explicitly stated as being in situ in the original publication. Note: for drill cores it must be assumed that samples are not in situ unless explicitly stated, or if referred to as "coral framework" or equivalent. If the sample is considered to be in "growth position", then it must be also assumed to be in situ.

**Reported as in growth position?** - If the sample was explicitly stated as being in growth position in the original publication.

**Taxa information (as reported)** - Taxonomic identification of sample as reported in original manuscript.

**Family**	- Insert the family the sample belongs to.

**Genus** - Insert the genus the sample belongs to.

**Species**	- Insert the species the sample belongs to.

**Comments on taxa** - Insert any further comments on the species/genus/family reported above.

Speleothem
-----------

.. note::
	This section is only available under U-Series ages on speleothems

**Reported in situ?** - Is the speleothem in original growth orientation? Note: Samples that are not in their original growth orientation (e.g. "in situ rubble") are NOT considered in situ here.

**Type of deposit** - Type of speleothem deposit (e.g. flowstone, stalactite, stalagmite, etc.).

**Distance from base of deposit (m)** - How far along the growth axis the sample is from the base of the speleothem. If the speleothem base is at a lower elevation then the samples, use positive distance. If the speleothem base is higher in elevation, make it negative. If the deposit is at the same elevation as the base, report as positive and make a note in the "Comments (elevation)" column.	

**Sampled material** - The type of material sampled (e.g. speleothem, serpulid worm tube, phreatic overgrowth on speleothem).

**Additional sample context** - Any other information that can place the sample in context to the rest of the deposit (e.g. if the sample is directly above/below a depositional hiatus)

.. note::
	The two fields below are only available when RSL datapoints from single speleothem is selected

**Paleo RSL from speleothem (m)** - Insert the paleo RSL associated with the speleothem

**Paleo RSL from speleothem uncertaity (m)** - Insert the paleo RSL uncertainty associated with the speleothem

Analytical details
-------------------

**Pa/Th age?** - Is there is a Pa/Th age for the sample?

\ :sup:`14`\ **C age?** - Is there a \ :sup:`14`\C age available for the sample?

**Instrument** - Type of mass spectrometer used for U-series isotopic Analysis.

**Decay constants** - Select the decay constants used as follows:

- D1 = \ :sup:`234`\U decay constant from Holden (1989) and \ :sup:`230`\Th decay constants of Meadows et al (1980)

- D2 = \ :sup:`234`\U and \ :sup:`230`\Th decay constants from Cheng et al. (2000)

- D3 = \ :sup:`234`\U and \ :sup:`230`\Th decay constants from Cheng et al. (2013)

- No Info, therefore assumed D1

**Comments on decay constants** - Insert here any comment related to the field above.

**Calibration method for** \ :sup:`230`\ **Th/** \ :sup:`238`\ **U ratio** - Indicate how the \ :sup:`230`\ Th/ \ :sup:`238`\ U ratios of the spike were calibrated: either a secular equilibrium (SE) or gravimetric (G) standard

**Calibration method for** \ :sup:`234`\** U/** \ :sup:`238`\ **U ratio** - Indicate how the \ :sup:`234`\ U/ \ :sup:`238`\ U ratios of the spike were calibrated: either a secular equilibrium (SE) or gravimetric (G) standard

**Comments on spike calibration** - Insert here comments on the fields above.<br>

**How was mineralogy determined?** - List any methods used to determine the composition of the sampled material (e.g. XRD, ICP-MS, thin section)

**Other screening techniques applied** - Other approaches besides XRD that were used to assess sample preservation

**Published % calcite** *(Only for corals and mollusks)* - Reported % calcite content of the sample determined via X-ray diffraction (XRD).

**Interpreted % calcite** *(Only for corals and mollusks)* - Interpretation of calcite content based on what was reported for '% calcite'.

**Other screening techniques applied** - Other approaches besides XRD that were used to assess sample preservation (incorporates older information from "determined by" column in Hibbert et al., 2016)

Analytical data
---------------

.. note::
	Insert the analytical data if available.

**[** \ :sup:`230`\ **Th/** \ :sup:`232`\ **Th]** \ :sub:`ACT`\ **backcalculated?** 

**[** \ :sup:`232`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\ **backcalculated?**

**Atomic ratio (** \ :sup:`232`\ **Th/** \ :sup:`238`\ **U)x10** \ :sup:`5`\ 

**Initial** \ :sup:`230`\ **Th/** \ :sup:`232`\ **Th**

**[** \ :sup:`232`\ **Th] (ppb)**

**[** \ :sup:`232`\ **Th] (ppb) uncertainty (±2-sigma)**

**[** \ :sup:`230`\ **Th/** \ :sup:`232`\ **Th]** \ :sub:`ACT`\

**[** \ :sup:`230`\ **Th/** \ :sup:`232`\ **Th]** \ :sub:`ACT`\ **uncertainty (±2-sigma)**

**[** \ :sup:`232`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\

**[** \ :sup:`232`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\ **uncertainty (±2-sigma)**

**[** \ :sup:`238`\ **U] (ppm)**

**[** \ :sup:`238`\ **U] (ppm) uncertainty (±2-sigma)**

Originally reported
--------------------

.. note::
	Insert the following values, as reported in the original study

**[** \ :sup:`230`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\ **backcalculated?**

**[** \ :sup:`234`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\ **backcalculated?**

**[** \ :sup:`230`\ **Th/** \ :sup:`234`\ **U]** \ :sub:`ACT`\

**[** \ :sup:`230`\ **Th/** \ :sup:`234`\ **U]** \ :sub:`ACT`\ **uncertainty (±2-sigma)**

**[** \ :sup:`230`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\

**[** \ :sup:`230`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\ **uncertainty (±2-sigma)**

**[** \ :sup:`234`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\

**[** \ :sup:`234`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\ **uncertainty (±2-sigma)**

**Reported age (ka)** *(Only for corals and speleothems)*

**Reported age uncertainty (ka, ±2-sigma)** *(Only for corals and speleothems)*

**Corrected reported age (ka)** - *(Only for speleothems)*

**Corrected reported age uncertainty (ka)** - *(Only for speleothems)*

**Initial** \ :sup:`234`\ **U/** \ :sup:`238`\ **U**

**Initial** \ :sup:`234`\ **U/** \ :sup:`238`\ **U uncertainty (±2-sigma)**

**Measured** \ :sup:`234`\ **U/** \ :sup:`238`\ **U**

**Measured** \ :sup:`234`\ **U/** \ :sup:`238`\ **U uncertainty (±2-sigma)**

**Reported delta** \ :sup:`234`\ **U initial (‰)**

**Reported delta** \ :sup:`234`\ **U (per mille) uncertainty (±2-sigma)**

**Measured delta** \ :sup:`234`\ **U initial (per mille)**

**Measured delta** \ :sup:`234`\ **U (per mille) uncertainty (±2-sigma)**

**Comments on reported age**

HU-1 spike correction
---------------------

**Reference material name for** \ :sup:`230`\ **Th/** \ :sup:`238`\ **U** - Name of standard if SE standard used to calibrate activity ratio.

**Reference material name for** \ :sup:`234`\ **U/** \ :sup:`238`\ **U** - Name of standard if SE standard used to calibrate activity ratio.

**Correction factor for** \ :sup:`230`\ **Th/** \ :sup:`238`\ **U** - HU-1 correction factor.

**Correction factor for** \ :sup:`230`\ **Th/** \ :sup:`238`\ **U uncertainty (±2-sigma)** - HU-1 correction factor uncertainty.

**Correction factor for** \ :sup:`234`\ **U/** \ :sup:`238`\ **U** - HU-1 correction factor.

**Correction factor for** \ :sup:`234`\ **U/** \ :sup:`238`\ **U uncertainty (±2-sigma)** - HU-1 correction factor uncertainty.

Recalculated
-------------
.. note::
	Insert the following values, if recalculated from the original study
	
**[** \ :sup:`230`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\ 

**[** \ :sup:`230`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\ **uncertainty (±2-sigma)**

**[** \ :sup:`234`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\

**[** \ :sup:`234`\ **Th/** \ :sup:`238`\ **U]** \ :sub:`ACT`\ **uncertainty (±2-sigma)**

**Recalculated Conventional Age (ka)** *(Only for corals and speleothems)*

**Recalculated Conventional Age uncert. (±2-sigma)** *(Only for corals and speleothems)*

**Recalculated delta 234Ui (per mille)**

**Recalculated delta 234Ui uncertainty (±2-sigma)**

**Recalculated Conventional Age uncert. w/ decay constant uncertainties (±2-sigma)**

**Recalculated delta 234Ui uncert. (±2-sigma) w/ decay constant uncertainties**

**Comments (age and delta** \ :sup:`234`\ **Ui)**

Age constraints
----------------
.. warning::
	The fields below can be filled only for U-series ages on algae or mollusks

**Age is Older/Equal/Younger than** - Select one option among those listed.

**Marine Isotopic Stage** - Select a MIS from the list. Add new MIS definitions if necessary. If the MIS is already present in the list but a different definition is needed, use the text box below (Comments/details on MIS designation).

**Age determination** - Provide comments or details on the designation above.
