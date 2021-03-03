################
Database tables
################
In the following section, each database table contained in WALIS is described. Six fields are given:

1. Field: Column name as it appears in the database
2. Type: Type of data accepted by the mySQL database 
3. Collation: Econding
4. Null: are null values are allowed?
5. Key: primary (PRI) or foreign (MUL) key
6. Comment: label within the PhP interface

*************
Table: rsl
*************
This table contains data and metadata related to paleo relative sea level datapoints from stratigraphic or geomorphic sea level indicators.

.. csv-table::
   :file: DB_Structure/rsl.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************
Table: vertmeastech
**********************
This table contains elevation measurement techniques used in WALIS.

.. csv-table::
   :file: DB_Structure/vertmeastech.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************
Table: hrzmeastech
**********************
This table contains geographic positioning techniques used in WALIS.

.. csv-table::
   :file: DB_Structure/hrzpostech.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************
Table: countries
**********************
This table contains the countries selectable in the interface.

.. csv-table::
   :file: DB_Structure/countries.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************
Table: regions
**********************
This table contains the administrative regions selectable in the interface.

.. csv-table::
   :file: DB_Structure/regions.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************
Table: MIS_ages
**********************
This table contains the Marine Isotopic Stages selectable in the interface.

.. csv-table::
   :file: DB_Structure/MIS_ages.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************
Table: rsl_ind
**********************
This table contains the types of RSL indicators inserted in WALIS.

.. csv-table::
   :file: DB_Structure/rsl_ind.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************
Table: sldatum
**********************
This table contains the sea level datums inserted in WALIS.

.. csv-table::
   :file: DB_Structure/sldatum.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************
Table: references
**********************
This table contains the references inserted in WALIS.

.. csv-table::
   :file: DB_Structure/references.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************   
Table: Useries_Corals
**********************
This table contains samples of corals, mollusks or speleothems dated with U-Series techniques.

.. csv-table::
   :file: DB_Structure/Useries_Corals.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************   
Table: aar
**********************
This table contains samples dated with Amino Acid Racemization.

.. csv-table::
   :file: DB_Structure/aar.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************  
Table: esr
**********************
This table contains samples dated with Electron Spin Resonance.

.. csv-table::
   :file: DB_Structure/esr.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************   
Table: luminescence
**********************
This table contains samples dated with luminescence techniques.

.. csv-table::
   :file: DB_Structure/luminescence.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1

**********************   
Table: strat
**********************
This table contains chronostratigraphic age constraints.

.. csv-table::
   :file: DB_Structure/strat.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1
   
**********************
Table: other_dating
**********************
This table contains samples dated with age techniques not detailed in WALIS.

.. csv-table::
   :file: DB_Structure/other_dating.csv
   :widths: 20,15,25,15,10,20
   :header-rows: 1