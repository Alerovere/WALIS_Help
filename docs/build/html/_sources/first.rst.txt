#################
Introduction
#################

********
Overview
********
The World Atlas of Last Interglacial Shorelines (WALIS) is a database containing information on published stratigraphic data (and dated samples) indicating the position of sea level during Marine Isotopic Stage 5. WALIS is composed by different elements: 1) the mySQL database, containing the data tables and associated relations; 2) a database interface based on PhP; 3) a series of Jupyter notebooks that download and process data. 

.. note::
   As of March 2021, the Jupyter notebooks are still in preparation, and not publicly available

The data insersion interface is available at `this page <https://warmcoasts.eu/world-atlas.html>`_. Geoscientists wishing to contribute data must register to our system. This will allow them to use an intuitive interface to insert both published and new sea level indicators, ages and metadata. During the compilation process, data remain private and are accessible only by the registered user. This is done to allow registered users to keep inserting and modifying data points until they are ready for publication. Registration to the system is (and will always be) free, but users must read and accept the WALIS data `policy <https://warmcoasts.eu/privacy.html>`_.

WALIS aims to make Last Interglacial sea level data open access and readily available. Within the database interface, a tool allows to export the data inserted by the logged user as a multi-sheet xls file. Data creators are encouraged, once their work is finalized, to submit this file to a repository where it will get a DOI. To this purpose, we set up a `Zenodo Repository <https://zenodo.org/communities/walis_database/>`_. As a user, you are free to decide to submit to another open-access repository, but if you do please let us know by writing a message to arovere@marum.de.

Once the data inserted by a data creator has been assigned a DOI from an open-access repository, it can be downloaded and re-used freely (complying with the simple rules at the bottom of this page). Periodically, WALIS data will be collated into a single release, containing all the data that were assigned a DOI up to the release date. The release will contain WALIS data in different formats, as well as scripts to query the database. The first release is planned to coincide with the closing of an ongoing Special Issue in the journal Earth System Science Data.

.. note::
   The first release of the database is foreseen by the end of 2021 

This document contains help tips to compile data using the interface and fully documents the database structure, including field types and table connections.

.. tip::
   For more information, see the atlas webpage: https://warmcoasts.eu/world-atlas.html.

****************
How to cite data
****************
If you use the database, we kindly ask you to provide credit where it is due following our citation guidelines.

.. warning::
   WALIS contains data that were originally published in research articles or technical reports. These data were standardized by data contributors, who might be different from the original authors. When exporting the database from the WALIS interface, a suggested acknowledgment is generated alongside with a suggested reference list. We strongly suggest not to remove these elements.

If you use WALIS, we kindly ask you to follow these simple rules to acknowledge those who worked on it: 

**1) Cite the original authors** - Please maintain the original citations of each datapoint. If you think that some datapoint needs further attribution, please inform us (see contact page).

**2) Acknowledge the database contributor** - A database contributor is a scientist or a group of scientists who standardized and in some instance re-interpreted the original research papers where the data was published. For each datapoint in WALIS, we provide the name of the first data creator and the last scientist who edited the data.

**3) Acknowledge the creators of the database and interface** - The database template used in this study was developed by the ERC Starting Grant "Warmcoasts" (ERC-StG-802414) and is a community effort under the PALSEA (PAGES / INQUA) working group. 

.. tip::
	**Suggested acknowledgment:** The data used in this study were [*extracted from / compiled in*] WALIS, a sea-level database interface developed by the ERC Starting Grant "WARMCOASTS" (ERC-StG-802414), in collaboration with PALSEA (PAGES / INQUA) working group. The database structure was designed by A. Rovere, D. Ryan, T. Lorscheid, A. Dutton, P. Chutcharavan, D. Brill, N. Jankowski, D. Mueller, M. Bartz, E. Gowan and K. Cohen. The data points used in this study were contributed to WALIS by [*list names of contributors here*].

*************************
How to cite this document
*************************
We suggest to cite this document whenever referring to the database. This work can be cited as: 

Rovere, Alessio, Ryan, Deirdre, Murray-Wallace, Colin, Simms, Alexander, Vacchi, Matteo, Dutton, Andrea, Lorscheid, Thomas, Chutcharavan, Peter, Brill, Dominik, Bartz, Melanie, Jankowski, Nathan, Mueller, Daniela, Cohen, Kim, Gowan, Evan, 2020. Descriptions of database fields for the World Atlas of Last Interglacial Shorelines (WALIS). doi:10.5281/zenodo.3961544

**Bibtex code**

.. code-block:: bibtex

	@misc{rovere_alessio_2020_3961544,
	author       = {Rovere, Alessio and
					Ryan, Deirdre and
					Murray-Wallace, Colin and
					Simms, Alexander and
					Vacchi, Matteo and
					Dutton, Andrea and
					Lorscheid, Thomas and
					Chutcharavan, Peter and
					Brill, Dominik and
					Bartz, Melanie and
					Jankowski, Nathan and
					Mueller, Daniela and
					Cohen, Kim and
					Gowan, Evan},
	title        = {{Descriptions of database fields for the World 
					Atlas of Last Interglacial Shorelines (WALIS)}},
	year         = 2020,
	publisher    = {Zenodo},
	version      = {1,0},
	doi          = {10.5281/zenodo.3961544},
	url          = {https://doi.org/10.5281/zenodo.3961544}}
	
*******
Funding
*******
WALIS - The World Atlas of Last Interglacial Shorelines is an online database collecting data and metadata on paleo sea level proxies. WALIS was built as part of the ERC Starting Grant "Warmcoasts" (ERC-StG-802414)

  .. image:: /img/WALIS_logos.jpg
   :width: 400
   :align: center

*******
License
*******
This work is licensed under a `Creative Commons Attribution-ShareAlike 4.0 International License <http://creativecommons.org/licenses/by-sa/4.0/>`_, **unless specified otherwise**.

  .. image:: https://i.creativecommons.org/l/by-sa/4.0/88x31.png
   :width: 100
   :align: center
   