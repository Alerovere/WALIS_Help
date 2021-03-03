################################
General fields for dated samples
################################

.. note::
	This section has been designed by A. Rovere, D. Ryan, P. Chutcharavan, A. Dutton, D. Brill, M. Bartz.

This section describes the general fields designed to collect information on U-Series, AAR, ESR and luminescence dated samples. These fields are included at the beginning of each file/sheet containing information on dated samples. In the interface, the fields below can be found within the 'Analysis metadata' and 'Geographic metadata' tabs of each dating technique.

Analysis metadata
--------------------
**Reference(s)** - Reference(s) from where the U-Series data have been extracted.

.. warning::
	The values for this field are selected from the 'references' table. The ID values are stored as comma-separated. No foreign keys are defined in the database.

**IGSN** - International Geo Sample Number associated to the sample.

**Sample ID** - Sample identifier. The first two letters and numbers indicate the author and year of the study which the sample was first measured in (e.g. CH91 = Chen et al., 1991), while the following three digits indicate the sample within the study (i.e. CH91-001 = the first coral analyzed in Chen et al., 1991). If this is an original date, the first four characters will correspond to the author surname and the year of analysis.

**Analysis ID** - Subsample identifier. The last three digits are the subsample ID (e.g. CH91-001-002 is the second subsample/aliquot of coral CH91-001). If only one subsample was analysed, the last three digits must be set to "001". If this is an original date, the first four characters will correspond to the author surname and the year of analysis.

**Reported ID** - Published sample identifier, or Laboratory ID as it appears in the original publication.

**Date of analysis** - Insert the date when the analysis was performed.

**Accepted?** - Select wether the date is accepted or rejected. In case of rejection, provide an explanation in the field below.

**Reason for rejection** - Provide an explanation for the rejection of the age.


Geographic metedata
--------------------

**Latitude (decimal degrees)** - Insert the latitude of the sample in decimal degrees.

**Longitude (decimal degrees)** - Insert the Longitude of the sample in decimal degrees.

**Reported Latitude** - Insert the latititude as reported originally. The field accepts numbers and characters.

**Reported Longitude** - Insert the longitude as reported originally. The field accepts numbers and characters.

**Are Lat/Long estimated?** - Select 'Yes' if Lat and Long were not provided in the original study, but estimated a posteriori through maps or other means.

**Original elevation datum used** - Select the sea level datum to which the elevations are referred. New sea level datums can be added from the [Sea Level Datum](Sea Level Datum.md) table.

**Elevation measurement method** - Method employed to measure elevations. New techniques can be added from the [Elevation Measurement](Elevation measurement.md) table.

**Reported elevation (m)** - Elevation of the sample as reported in the original publication. This field accepts text values up to 50 characters. Default is N/A.

**Reported elevation uncertainty (m)** - Elevation uncertainty of the sample as reported in the original publication. This field accepts text values up to 50 characters. Default is N/A.

**Elevation above MSL (m)** - Elevation of the sample in meters above mean sea level. If not provided in the original publication, calculate it from the reported elevation and the datum used, indicating how the elevation above MSL has been derived. Default is N/A.

**Elevation uncertainty used (m)** - Final elevation uncertainty used, including measurement and datum uncertainty. Default is N/A.

**Elevation comments** - Insert here how MSL elevations have been derived from the original datum, including uncertainties.
