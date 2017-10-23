# Welcome to the industrial ecology dashboard on GitHub!

Here you find a list of repositories that are relevant for industrial ecology researchers. Feel free to add relevant content! 

## Contents
* [Input-Output Analysis](#input-output-analysis)
* [Life Cycle Assessment](#life-cycle-assessment)
* [Material Flow Analysis](#material-flow-analysis)
* [Industrial Symbiosis / Eco-Industrial Parks](#industrial-symbiosis--eco-industrial-parks)
* [Collaboration initiatives and data sharing platforms](#Collaboration-initiatives-and-data-sharing-platforms)
* [Miscellaneous](#miscellaneous)
* [Models from other commmunities](#Models-from-other-communities)

## Input-Output Analysis

[npspringer/WorldTradeModel](https://github.com/npspringer/WorldTradeModel) - 
Python code for the World Trade Model, a linear programming model utilizing input-output economics.  This version includes the Rectangular Choice-of-Technology (RCOT) as well as the option to solve for bilateral trade (WTMBT)

[konstantinstadler/pymrio](https://github.com/konstantinstadler/pymrio) - 
A python module for automating input output calculations and generating reports. The module can handle single region IO as well as MRIO.

[stefanpauliuk/pySUT](https://github.com/stefanpauliuk/pySUT) - 
Python module for handling supply and use tables

[GreenDelta/usio](https://github.com/GreenDelta/usio) - 
Python module to create input-output tables from United States [BEA](http://www.bea.gov/) make and use tables. Written by the authors of [openLCA](http://www.openlca.org/), but can be used independently.

[majeau-bettez/allocation_construct](https://github.com/majeau-bettez/allocation_construct) - 
Python module for lifecycle assessment allocations and input-output constructs

[majeau-bettez/ecospold2matrix](https://github.com/majeau-bettez/ecospold2matrix) - 
Class for recasting Ecospold2 LCA dataset into Leontief matrix representations or Supply and Use Tables

[bquast/wiod ](https://github.com/bquast/wiod) - 
R package for "Data sets from the World Input Output database, for the years 1995-2011"


## Life Cycle Assessment

### Software

#### openLCA
[openLCA](http://www.openlca.org/) is an open source and free software for Sustainability and Life Cycle Assessment. 

* [Main webpage](http://www.openlca.org/)
* [Source code](https://github.com/GreenDelta/olca-app)
* [Tutorial for accessing the openLCA API (application programming interface) with Python](https://github.com/GreenDelta/openlca-python-tutorial)

#### Brightway2

Brightway2 is a framework for life cycle assessment. The main webpage is http://brightwaylca.org/.

The core modules handle data management and calculation:

* [cmutel/brightway2-data/](https://bitbucket.org/cmutel/brightway2-data/)
* [cmutel/brightway2-calc/](https://bitbucket.org/cmutel/brightway2-calc/)
* [cmutel/brightway2-io/](https://bitbucket.org/cmutel/brightway2-io/)

There are also additional packages for e.g. user interfaces, analysis, regionalization, dynamic LCA, found on the webpage and documentation.

### Data

#### Wurst

[Wurst](https://github.com/IndEcol/wurst) is a tool for linking and modifying industrial ecology models, with a focus on sparse matrices in life cycle assessment. It is used to add new data (e.g. better region-specific) or future scenarios to inventory databases in a reproducible and self-documenting fashion. Where is also a [Wurst examples](https://github.com/IndEcol/wurst-examples) repository.

#### Ocelot

The [Ocelot project](https://ocelot.space/) is a joint effort by the Paul Scherrer Institut and the ecoinvent centre to build an open source library for applying system models in life cycle assessment. System models are a set of linking rules and assumptions, including how to handle activities that produce multiple outputs, how to construct markets in time and space, what products are substitutable, and who gets credit for the production of recyclable materials. 

#### Semantic Catalogs of LCA Data

Supporting code & data for the article [Semantic catalogs for life cycle assessment data](http://www.sciencedirect.com/science/article/pii/S0959652616311210).  This works provides a multi-database catalog of life cycle data in an open, linked-data format.

* [bkuczenski.github.io/lca-tools-datafiles](http://bkuczenski.github.io/lca-tools-datafiles/)
* [bkuczenski/lca-tools](https://github.com/bkuczenski/lca-tools)
* [bkuczenski/lca-tools-datafiles](https://github.com/bkuczenski/lca-tools-datafiles)

## Material Flow Analysis

### Data reconciliation and probabilistic modelling

[PYMFA 2.1 by Esther Thiébaud at EMPA](https://bitbucket.org/Xeelk/pymfa2/src) - 
Tool for probabilistic modelling of dynamic MFA studies

[ricklupton/bayesian-mfa-paper](https://github.com/ricklupton/bayesian-mfa-paper) - Code and data supporting the paper "Incremental Material Flow Analysis with Bayesian Inference" 

### Dynamic stock modelling

[stefanpauliuk/dynamic_stock_model](https://github.com/stefanpauliuk/dynamic_stock_model) - 
Python class for dynamic stock modelling

[stefanpauliuk/MaTrace_Global](https://github.com/stefanpauliuk/MaTrace_Global) - 
Python model code for MaTrace Global, a supply-driven dynamic stock model to trace end-of-life materials through global value chains


### Metabolism of Cities

[paulhoekman/mfa-tools](https://github.com/paulhoekman/mfa-tools) - Source code of the [Metabolism of Cities](http://metabolismofcities.org/) website. PHP/MySQL-driven website providing a centralized repository for urban metabolism-related publications, research projects, and data. It also includes online MFA software ([OMAT](http://metabolismofcities.org/omat/about)). 

[tomravalde/urban-metabolism-process-database](https://github.com/tomravalde/urban-metabolism-process-database) - "A YAML database of resource management processes to support urban metabolism studies", created for the article [A Database to Facilitate a Process-Oriented Approach to Urban Metabolism](http://onlinelibrary.wiley.com/doi/10.1111/jiec.12429/abstract).

### Visualisation

[ricklupton/d3-sankey-diagram](https://github.com/ricklupton/d3-sankey-diagram) - Sankey diagram tool for the D3.js library. Features automatic routing, loops, and reversed flows.
* [Source code](https://github.com/ricklupton/d3-sankey-diagram)
* [Examples](https://ricklupton.github.io/d3-sankey-diagram/)
* [IPython widget for the d3 Sankey plugin](https://github.com/ricklupton/ipython-d3-sankey)
* [Display Sankey diagrams in IPython / Jupyter notebook using d3-sankey-diagram](https://github.com/ricklupton/ipysankeywidget)


## Industrial Symbiosis / Eco-Industrial Parks

On [isdata-org](https://github.com/isdata-org/) there is a collection of several repositories:

* [isdata-org/industrial-symbiosis-literature](https://github.com/isdata-org/industrial-symbiosis-literature) - interactive visualization of literature related to IS and EIPs
* [isdata-org/what-links-to-what](https://github.com/isdata-org/what-links-to-what) - linked data for translating between different product and industry classifications
* [isdata-org/awesome-industrial-symbiosis](https://github.com/isdata-org/awesome-industrial-symbiosis/) - links to data sources relevant for Industrial Symbiosis

[complexly/EIPs](https://github.com/complexly/EIPs) - "R package with network data of Eco-Industrial Park(EIP)".  Contains information in R data frames about exchanges documented in 15 different EIPs. 

### Event Sequence Analysis

Software developed for the article [Building capacity for sustainable regional industrial systems: an event sequence analysis of developments in the Sloe Area and Canal Zone](http://www.sciencedirect.com/science/article/pii/S0959652614008506):

* [WouterSpekkink/DynamicNetworks](https://github.com/WouterSpekkink/DynamicNetworks)
* [WouterSpekkink/EventGraphLayout_0.8.2](https://github.com/WouterSpekkink/EventGraphLayout_0.8.2)

## Collaboration initiatives and data sharing platforms

BONSAI (Big Open Network for Sustainability Assessment Information) is an open project to create a framework for supplying reliable, unbiased sustainability information on products – “product footprints” – readily and freely available whenever and wherever it is needed to support product comparisons and decisions.
* [BONSAI Homepate](https://bonsai.uno/)
* [BONSAI code and Wiki](http://jgcri.github.io/gcam-doc/)

## Miscellaneous 

[majeau-bettez/styles](https://github.com/majeau-bettez/styles) - 
Official repository for Citation Style Language (CSL) citation styles.

[konstantinstadler/sci_python_template](https://github.com/konstantinstadler/sci_python_template) - 
Python template for scientific scripts

[konstantinstadler/country_converter](https://github.com/konstantinstadler/country_converter) - 
The country converter (coco) - a Python package for converting country names between different classifications and between different naming versions.

## <a name="Models-from-other-communities"></a> Models from other communities

### Global Change Assessment Model (GCAM) 
The Joint Global Change Research Institute (JGCRI) is the home and primary development institution for GCAM, an integrated assessment tool for exploring consequences and responses to global change. GCAM is a dynamic-recursive model with technology-rich representations of the economy, energy sector, land use and water linked to a climate model that can be used to explore climate change mitigation policies including carbon taxes, carbon trading, regulations and accelerated deployment of energy technology. GCAM has been used to explore the potential role of emerging energy supply technologies and the greenhouse gas consequences of specific policy measures or energy technology adoption including; CO2 capture and storage, bioenergy, hydrogen systems, nuclear energy, renewable energy technology, and energy use technology in buildings, industry and the transportation sectors. GCAM is an Representative Concentration Pathway (RCP)-class model.

* [GCAM Documentation](http://jgcri.github.io/gcam-doc/)
* [Getting Started with GCAM](http://jgcri.github.io/gcam-doc/user-guide.html)
* [GCAM Community](http://www.globalchange.umd.edu/models/gcam/gcam-community/)
* [2015 Tutorial Slides](http://www.globalchange.umd.edu/data/annual-meetings/2015/GCAM_Tutorial_2015.pdf)
