#RetailDemo

Example for using DSE Search to perform Basic Text Search, Multi-condition Query, Fuzzy and Range Search, Faceting Query and Geospatial Query on a simulated dataset
derived from Amazon Product Data (http://jmcauley.ucsd.edu/data/amazon/).

##Usage:

Load data:

python dataload.py data/metadata_10k.json data/geodata.csv

Then use browser to access http://<node0_public_ip>:7001 for all exercise notebooks.

###Docs

pull in your submodules

    git submodule update --init
    git submodule sync

then run the server

    hugo server ./content

