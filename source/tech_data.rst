##############
Technical data
##############
WALIS is composed by a database, a user interface and a series of Jupyter notebooks that allow extracting and processing the database records. These three elements are briefly introduced below.

*********
Database
*********
WALIS data is contained in a mySQL (5.7) database, hosted on an Amazon Web Services instance. The database is managed offline with `HeidiSQL <https://www.heidisql.com/>`_. and `MySQL Workbench <https://www.mysql.com/products/workbench/>`_. The database contains 23 tables and 1 view. Seven of the 23 tables are used for user and groups management within the interface, while the remaining 16 tables and 1 view are dedicated to sea-level data and meta-data. 

.. warning::
	Only one-to-one relationships are defined in the database directly. One-to-many and many-to-many relationships are defined via comma-separated fields and managed in the PhP interface directly.

*********
Interface
*********
The WALIS interface is written in PhP (7.0). It allows users to register and insert data. The bulk of the interface was done with `Scriptcase <https://www.scriptcase.net>`_, a commercial PhP Web Development tool. Within the interface, there is the possibility to download a multi-sheet Excel file containing all data inserted by the logged user. This tool is coded in Python, served via a `Flask <https://flask.palletsprojects.com/en/1.1.x/>`_ web app.

.. note::
	A modification of the Flask web app is in preparation, to allow the user to export a zip file containing not only Excel file (a proprietary format), but also a series of csv and json files.

Interface versions
--------------------

The following table shows the main changes corresponding with each interface versions

.. csv-table::
   :file: DB_Structure/Interface_versions.csv
   :widths: 5,10,8
   :header-rows: 1

********************
Jupyter notebooks
********************
A series of Jupyter notebooks allows extracting the data and making simple maps/statistics.

.. note::
   As of January 2021, the Jupyter notebooks are still in preparation, and not publicly available