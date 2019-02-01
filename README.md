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

[R|E|A|L PyIO](http://www.real.illinois.edu/pyio/) - 
PyIO is a module for Input-Output analysis, written in Python, a general-purpose open source computer programming language. Next to standard IO techniques PyIO also features matrix updating with the RAS method, key sector analysis, output decomposition analysis, and multiplier product matrix analysis.

[stefanpauliuk/pySUT](https://github.com/stefanpauliuk/pySUT) - 
Python module for handling supply and use tables and building IO tables from raw data.

[GreenDelta/usio](https://github.com/GreenDelta/usio) - 
Python module to create input-output tables from United States [BEA](http://www.bea.gov/) make and use tables. Written by the authors of [openLCA](http://www.openlca.org/), but can be used independently.

[majeau-bettez/allocation_construct](https://github.com/majeau-bettez/allocation_construct) - 
Python module for lifecycle assessment allocations and input-output constructs

[majeau-bettez/ecospold2matrix](https://github.com/majeau-bettez/ecospold2matrix) - 
Class for recasting Ecospold2 LCA dataset into Leontief matrix representations or Supply and Use Tables

[bquast/wiod ](https://github.com/bquast/wiod) - 
R package for "Data sets from the World Input Output database, for the years 1995-2011"

[usepa/IO-Model-Builder](https://github.com/usepa/io-model-builder/) - 
iomb is an open source Python library for creating environmentally extended input-output models (EEIO models) from CSV files in a simple data format. It includes functions to calculate different result types (e.g. life cycle assessment results, direct and upstream contributions, etc.) from such models and convert them into JSON-LD data packages that can be imported into openLCA.

[Paradiso-Project](https://github.com/haasad/PyPardisoProject) -
Python interface to the Intel MKL Pardiso library to solve large sparse linear systems of equations. Use PyPardiso with the anaconda python distribution (use miniconda if you need to install it). PyPardiso makes use of the Intel Math Kernel Library that is included for free with conda and therefore doesn't work with other distributions (at least for the moment).

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

The [LCA-ActivityBrowser](https://github.com/LCA-ActivityBrowser/activity-browser) serves as GUI for Brightway2.

#### Lcopt

Lcopt (**L**ife **C**ycle **opt**ions appraisal) is an LCA foreground modelling tool (written in Python) with a GUI which runs in a web browser. It can be used to generate fully parameterised LCA foreground models with multiple scenarios. The models can be analysed (using the Brightway2 framework) and the results visualised from within the GUI.

* [*Getting started* Video](http://lcopt.readthedocs.io/en/latest/2_Getting_Started.html#video)
* [Main website/documentation](http://lcopt.readthedocs.io)
* [Source code (published version)](https://github.com/pjamesjoyce/lcopt)
* [Source code (development version)](https://github.com/pjamesjoyce/lcopt/tree/development) - new features (including faster calculation, mass flow sankey diagram, import of existing models as `BW2Package` file) added, with more [in the works](https://github.com/pjamesjoyce/lcopt/issues?q=is%3Aopen+is%3Aissue+label%3Aenhancement)


#### Lcopt-cv

[Lcopt-cv](https://github.com/pjamesjoyce/lcopt_cv) is an experimental piece of software which lets you take a photo of a hand-drawn process flow chart and, using computer vision techniques, automatically turns it into a working LCA foreground model. The LCA model it generates can be visualised/edited in [lcopt](http://lcopt.readthedocs.io) and analysed using [Brightway2](http://brightwaylca.org/).

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

### Dynamic MFA and dynamic stock modelling

[ODYM](https://github.com/IndEcol/ODYM) - 
Open dynamic material systems model (ODYM). Framework for dynamic MFA models with multiple aspects (products, regions, materials, alloys, elements, ...). Python classes for MFA systems, stocks, flows, model parameters, and dynamic stock modelling. Platform for organizing MFA systems and data to build custom-made MFA models of any resolution and complexity.

[dynamic_stock_model](https://github.com/stefanpauliuk/dynamic_stock_model) - 
Python class for dynamic stock modelling. Supports inflow-driven and stock-driven models.

[MaTrace_Global](https://github.com/stefanpauliuk/MaTrace_Global) - 
Python model code for MaTrace Global, a supply-driven dynamic stock model to trace end-of-life materials through global value chains

[dpmfa-simulator](https://pypi.python.org/pypi/dpmfa-simulator) - The dpmfa framework supports the generation and use of dynamic probabilistic material flow models. It enables to model of time dynamic flow models on a period base. Incomplete knowledge about the true values of a system parameter about the absolute inflows to the system over time and the relative transfer coefficients for the flows between the system compartments is represented as Bayesian probability distribution. It is propagated to dependent model variables using Monte-Carlo simulation, while ensuring mass-balance in every element of the Monte-Carlo sample. 

### Metabolism of Cities

[paulhoekman/mfa-tools](https://github.com/paulhoekman/mfa-tools) - Source code of the [Metabolism of Cities](http://metabolismofcities.org/) website. PHP/MySQL-driven website providing a centralized repository for urban metabolism-related publications, research projects, and data. It also includes online MFA software ([OMAT](http://metabolismofcities.org/omat/about)). 

[tomravalde/urban-metabolism-process-database](https://github.com/tomravalde/urban-metabolism-process-database) - "A YAML database of resource management processes to support urban metabolism studies", created for the article [A Database to Facilitate a Process-Oriented Approach to Urban Metabolism](http://onlinelibrary.wiley.com/doi/10.1111/jiec.12429/abstract).

### Visualisation

[ricklupton/d3-sankey-diagram](https://github.com/ricklupton/d3-sankey-diagram) - Sankey diagram tool for the D3.js library. Features automatic routing, loops, and reversed flows.
* [Source code](https://github.com/ricklupton/d3-sankey-diagram)
* [Examples](https://ricklupton.github.io/d3-sankey-diagram/)
* [Display Sankey diagrams in IPython / Jupyter notebook using d3-sankey-diagram](https://github.com/ricklupton/ipysankeywidget)

[ricklupton/floweaver](https://github.com/ricklupton/floweaver) - floWeaver takes a database of flow data and transforms it into a Sankey diagram.
* [floWeaver's documentation and news](https://floweaver.readthedocs.io/en/latest/)

[tomshanley/d3-sankey-circular](https://github.com/tomshanley/d3-sankey-circular) - A fork of the d3-sankey library to allow circular links. 

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

## <a name="Collaboration-initiatives-and-data-sharing-platforms"></a> Collaboration initiatives and data sharing platforms

### BONSAI

BONSAI (Big Open Network for Sustainability Assessment Information) is an open project to create a framework for supplying reliable, unbiased sustainability information on products – “product footprints” – readily and freely available whenever and wherever it is needed to support product comparisons and decisions.
* [BONSAI Homepage](https://bonsai.uno/)
* [BONSAI code and Wiki](https://github.com/BONSAMURAIS/bonsai)

### Liberated data 

[nheeren/liberated_data](https://github.com/nheeren/liberated_data) – A platform to share the data that you so diligently extracted from figures, tables, etc. in publications.

### Industrial Ecology Data Commons (IEDC)

[IndEcol/IE_data_commons](https://github.com/IndEcol/IE_data_commons) – A general, cross-method data model and relational database structure for socioeconomic metabolism and industrial ecology research.

## <a name="miscellaneous"></a> Miscellaneous 

[cfrancois7/IEO-ontology](https://github.com/cfrancois7/IEO-ontology) - 
The Industrial Ecology Ontology(IEO): the ontology to represent the knowledge of the Industrial Ecology. Includes the different knowledge items of life cycle assessment (LCA), Supply-Use Tables (SUT) and Input-Output Tables (IOT).

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

### Open Energy Modelling Framework (oemof)
The Open Energy System Modelling Framework (oemof) provides a free, open source and clearly documented toolbox to analyse energy supply systems. It is developed in Python and designed as a framework with a modular structure containing several packages which communicate through well defined interfaces.

* [oemof - Base packages for energy system modelling and optimisation](https://github.com/oemof/oemof)

### The MESSAGEix framework
MESSAGEix is a versatile, open-source, dynamic systems-optimization model. It was developed for strategic energy planning and integrated assessment of energy-engineering-economy-environment systems. It can be applied to analyse scenarios of the energy system transformation under technical-engineering constraints and political-societal considerations. The optimization model can be linked to the general-economy MACRO model to incorporate feedback between prices and demand levels for energy and commodities. The equations are implemented in the mathematical programming system GAMS for numerical solution of a model instance.

* [MESSAGEix framework docu](http://messageix.iiasa.ac.at/)
* [MESSAGEix model code](https://github.com/iiasa/message_ix/tree/master)
