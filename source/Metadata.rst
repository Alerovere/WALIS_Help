##########################
Metadata
##########################

.. note::
	This section has been designed by A. Rovere and D. Ryan

This section describes the fields included in the 'RSL indicators','Elevation measurement','Geographic positioning' and 'Sea level datums' files/sheets, created respectively from the 'rsl_ind','vrtmeastech','hrzpostech','sldatum' mySQL tables. In the interface, the fields below can be found under 'Metadata' page.

Type of RSL indicator
---------------------

.. note:: 
	In the interface, any data inserted in this section is by default made public. Every user will be able to select the same sea-level indicator 

Name of RSL indicator
=====================
Short name for the RSL indicator.

Description of RSL indicator
============================
Detailed descriptions of the RSL indicator. 

Description of RWL
===================
Description the Reference Water Level. As a reference, see Table 1 in `Khan et al., 2017 <https://www.sciencedirect.com/science/article/abs/pii/S0277379116303304>`_. For example, use (HAT to MSL)/2 for an index point having the Highest Astronomical Tide and Mean Sea Level as, respectively, upper and lower limits of the indicative meaning.

Description of IR
===================
Description of the Indicative Range. As a reference, see Table 1 in `Khan et al., 2017 <https://www.sciencedirect.com/science/article/abs/pii/S0277379116303304>`_. For example, use HAT to MSL for an index point having the Highest Astronomical Tide and Mean Sea Level as, respectively, upper and lower limits of the indicative meaning.

Indicator reference(s)
======================
Reference(s) describing the sea level indicator.

.. warning::
	In the interface, the values for this field are selected from the 'references' table. The ID values are stored as comma-separated. No foreign keys are defined in the database.

Geographic positioning
----------------------

.. note:: 
	In the interface, any data inserted in this section is by default made public. Every user will be able to select the same geographic positioning technique
	
Type
====
The type/name of the positioning technique.

Description
===========
Description of the geographic positioning technique. Insert here details on the technique used.

Typical accuracy
================
Typical accuracy of the geographic positioning technique (free text).

Sea level datum
----------------------

.. note:: 
	In the interface, any data inserted in this section is by default made public. Every user will be able to select the same sea level datum
	
Datum name
==========
Short name for the sea level datum used.

Datum description
=================
Sea level datum description, possibly with details on how it has been calculated/derived.

Datum uncertainty
==================
Estimated or calculated datum uncertainty.

Reference(s)
============
Reference for the sea level datum.

.. warning::
	In the interface, the values for this field are selected from the 'references' table. The ID values are stored as comma-separated. No foreign keys are defined in the database.

Elevation measurement
----------------------

.. note:: 
	In the interface, any data inserted in this section is by default made public. Every user will be able to select the measurement technique

Measurement technique
=====================
The type/name of the measurement elevation technique.

Description
===========
Description of the elevation measurement technique.

Typical accuracy
================
Typical accuracy of the elevation measurement technique.
