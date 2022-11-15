# rfiona
A collection of tools and practises for effective managament and data wrangling in Statistics Finland's Fiona.

## Installation

The package is currently being developed in the Fiona remote access system.

## Packages

rfiona is a meta package that brings together three packages: rfionadata, rfionawrangle and rfionarecode.

### Setting up, organising and reading data: rfionadata

rfionadata provides tools for organising, setting up, resaving, reading data and creating pseudodata in Fiona. 

Data saving and reading functions that read and construct data in standard form fast but with reasonable consumption of data storage, specialized reading functions that directly construct panel data of arbitrary frequency out of spell data or balanced or unbalanced panels out of annual data and add specific variables to data on demand, imputation of missing spell end information using information from other spells, creation of random pseudodata for testing and demonstration.

### Wrangling data: rfionawrangle

Tools for solving common data wrangling problems in Fiona and elsewhere.

Cleaning spell data by connecting duplicate, intersecting and successive spells with small breaks, removing duplicate observations with non-identical rows, transforming spell data into panel data of arbitrary frequencies, computing number of days in spell during arbitrary time intervals.

### Recoding variables: rfionarecode

Tools for getting keys, recoding and naming categorical variables and getting variable information in Fiona.

Access Fiona's classification directory directly from R to search and retrieve classification keys, recode or name region, occcupation, industry and other categorical variables, add regions to data, deal with municipal mergers.


Ask me more!
