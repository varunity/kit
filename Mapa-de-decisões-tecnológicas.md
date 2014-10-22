---
published: true
permalink: / map-of-making-technology /
layout: slate
filename: Map-of-decision-tecnológicas.md
title: Map of decisions - Open Data Kit
desc: this map various forms of publishing open data are presented, giving the manager parameters for decision support.
---

## Map of technological decisions

The table below shows the most common solutions for publishing open data, sorted by complexity and implementation time.

<! ---
Below the HTML table, markdown not support colspan.
--->

<Table class = "table-technological decisions">
    <- <Colgroup>
      <Col width = "118" />
      <Col width = "424" />
      <Col width = "302" />
      <Col width = "200" />
    </ Colgroup> ->

    <Tr>

      <Th>
        Solu & brow furrowed Primary Color the
      </ Th>

      <Th>
        Pr & eacute; -Requirements
      </ Th>

      <Th>
        Deadline
      </ Th>

    </ Tr>

    <Tr>

      <Td rowspan = "2">
        <a href="#publicar-dump-the-base-of-dados"> Post dump data base </a>
      </ Td>

      <Td class = "half-cell">
        Access & worse; database
      </ Td>

      <Td rowspan = "2">
        Short <br />
      </ Td>

    </ Tr>

    <Tr>
      <Td>
        Web server for files
      </ Td>

    </ Tr>

    <Tr>

      <Td rowspan = "2">
        <a href="#publicar-data-on-file-csv"> Publish data in CSV files </a>
      </ Td>

      <Td class = "half-cell">
        ETL engine (if in relational database)
      </ Td>

      <Td rowspan = "2">
        Short <br />
      </ Td>

    </ Tr>

    <Tr>
      <Td>
        Web server for files
      </ Td>

    </ Tr>

    <Tr>

      <Td rowspan = "3">
        <a href="#publicar-data-on-file-json - xml"> Publish data in JSON / XML files </a>
      </ Td>

      <Td class = "half-cell">
        ETL engine (if in relational database)
      </ Td>

      <Td rowspan = "3">
        M & eacute; dio
      </ Td>

    </ Tr>

    <Tr>
      <Td class = "half-cell">
        Serve & brow furrowed the development
      </ Td>

    </ Tr>

    <Tr>
      <Td>
        Web server for files
      </ Td>

    </ Tr>

    <Tr>

      <Td rowspan = "2">
        <a href="#desenvolver-module-data-open-in-system-existente"> Develop m & oacute; module open data in existing system </a>
      </ Td>

      <Td class = "half-cell">
        Serve & brow furrowed the development
      </ Td>

      <Td rowspan = "2">
        Long
      </ Td>

    </ Tr>

    <Tr>
      <Td>
        Web server to deploy the new solution & brow furrowed Primary Color the
      </ Td>

    </ Tr>

    <Tr>

      <Td rowspan = "3">
        <a href="#desenvolver-api-restful-data-open-decoupled-the-soluo"> Developing RESTful API Decoupled open data
        solutions & brow furrowed Primary Color </a>
      </ Td>

      <Td class = "half-cell">
        ETL mechanism
      </ Td>

      <Td rowspan = "3">
        Long
      </ Td>

    </ Tr>

    <Tr>
      <Td class = "half-cell">
        Serve & brow furrowed the development
      </ Td>

    </ Tr>

    <Tr>
      <Td>
        Web server to deploy the new solution & brow furrowed Primary Color the
      </ Td>

    </ Tr>

    <Tr>

      <Td rowspan = "3">
        <a href="#novo-system-with-gesture-data-embedded-in-your-architecture"> New System, with gest Primary Color the data embedded in its architecture </a>
      </ Td>

      <Td class = "half-cell">
        ETL mechanism
      </ Td>

      <Td rowspan = "3">
        Long
      </ Td>

    </ Tr>

    <Tr>
      <Td class = "half-cell">
        Serve & brow furrowed the development
      </ Td>

    </ Tr>

    <Tr>
      <Td>
        Web server to deploy the new solution & brow furrowed Primary Color the
      </ Td>

    </ Tr>

    <Tr>

      <Td rowspan = "3">
        <a href="#publicar-data-on-file-rdf"> Publish data in RDF files </a>
      </ Td>

      <Td class = "half-cell">
        Ontology & á area of ​​knowledge of the system
      </ Td>

      <Td rowspan = "3">
        Long
      </ Td>

    </ Tr>

    <Tr>
      <Td class = "half-cell">
        ETL mechanism
      </ Td>

    </ Tr>

    <Tr>
      <Td>
        Web server for files
      </ Td>

    </ Tr>

    <Tr>

      <Td rowspan = "3">
        <a href="#disponibilizar-data-for-endpoint-sparql"> Provide data for SPARQL Endpoint </a>
      </ Td>

      <Td class = "half-cell">
        Ontology & á area of ​​knowledge of the system
      </ Td>

      <Td rowspan = "3">
        Longest
      </ Td>

    </ Tr>

    <Tr>
      <Td class = "half-cell">
        ETL mechanism
      </ Td>

    </ Tr>

    <Tr>
      <Td>
        Database of triple
      </ Td>

    </ Tr>

    <Tr>

      <Td rowspan = "5">
        <a href="#publicar-data-api-in-data-linked-linked-data"> Publish data in linked data API (Linked Data) </a>
      </ Td>

      <Td class = "half-cell">
        Ontology & á area of ​​knowledge of the system
      </ Td>

      <Td rowspan = "5">
        Longest
      </ Td>

    </ Tr>

    <Tr>
      <Td class = "half-cell">
        Database of triple
      </ Td>

    </ Tr>

    <Tr>
      <Td class = "half-cell">
        Serve & brow furrowed the development
      </ Td>

    </ Tr>

    <Tr>
      <Td class = "half-cell">
        ETL mechanism
      </ Td>

    </ Tr>

    <Tr>
      <Td>
        Web server to deploy the new solution & brow furrowed Primary Color the
      </ Td>

    </ Tr>
  </ Table>

<! ---
### List of Solutions

#### Post dump database

This is the simplest form of publication, if the database is not in the proper environment, just ask the extraction service, available on the web server and provide domain + persistent URL.

Advantages and Disadvantages **: ** short implementation time, hard data visualization.

Post #### data in CSV files

For this publication a minimum ETL mechanism to be able to turn the tables in the DBMS 'tables' CSV is required.

Advantages and Disadvantages **: ** short term, easy viewing through familiar tools.

Post #### data in JSON / XML files

In the case of CSV suffice transform and normalize a table in another table (DBMS -> SQL). For this publication, a more customized processing is needed, respecting the structure of JSON and XML formats.

Advantages and Disadvantages **: ** more laborious to implement, easy to work with these formats in programming languages ​​and apis viewing.

#### Develop module open data in existing system

This option is only viable if the system has a modular architecture.

Advantages and Disadvantages **: ** cohesion of the solution; single interface for users; higher cost of development.

#### Developing RESTful API Decoupled open data solution

An important decision for this option is the separation or not the database of the API production, which has several implications (performance, timeliness of data etc)

Advantages and Disadvantages **: ** possibility of more specific queries; Development cost.

#### New System, with embedded data management in its architecture

Advantages and Disadvantages **: ** System designed predicting attendance of Law Access to information, automation of data extraction

Post #### data in RDF files


#### Provide data for SPARQL Endpoint


Post #### data in linked data API (Linked Data)
->

### Glossary Formats

#### Basic formats

##### SQL Dump

Generically, a '_ [dump](https://pt.wikipedia.org/wiki/Dump_de_banco_de_dados) _ "
is a discharge of the entire contents of a database, structured in a
form that can be reloaded into a database management system
(DBMS) identical or compatible, producing a base by the process
Data which is a faithful copy of the original.

There are several types of _dump_. The textual formats can be inspected on a
text editor and often use SQL syntax in particular dialect of DBMS
used. There are also binary formats produce smaller files that
textual, but compatibility with different versions of DBMS tends to be
even more restrictive than the compatibility of textual formats.

The DBMS generally have defined processes and objective documentation of how
generate and load a _dump_.

`` ++++++:
* Less laborious Form to publish data
* Short-term production
* Preserves the structure of data as they are in production

------ ``:
* Probable need for prior removal of personal data
* Need to carry load data into DBMS to access them
* There is no standardization between dumps SGBSs different formats: in general
  is needed-the same software and version that generated the dump

##### CSV

Can mean [Comma-Separated Values](https://pt.wikipedia.org/wiki/Comma-separated_values)
(Comma separated values), or
still, Character-Separated Values ​​(separated by character values). It is a
tabular format for storing text data. The encoding is
very simple: each line of the file represents a row in the table, and
columns are separated by commas. Fields which may contain point must be
delimited by double quotes. CSV is recommended for representing structure
simpler data, tabular nature, where there are subproperties or
lists, resulting in a smaller and lighter file for processing. CSV files
are directly processable by spreadsheet editors such as OpenOffice and the
MS Excel. (The [Glossary](/% C3% A1rio Gloss / # csv))

`` ++++++:
* Simplicity. Records in tabular structure.
* Ease of generation (any database exports)
* Ease of use (handles any spreadsheet editor)
* Succinct (the generated files are smaller)

------ ``:
Lack of standardization of the format
* Does not support typing values
* Difficult to represent connections between the data

JSON #####

It is an acronym for
[_JavaScript Object Notation_](https://pt.wikipedia.org/wiki/JSON).
It is an open standard data structuring text-based and readable
human. The specification is the [RFC 7159](https://tools.ietf.org/html/rfc7159).
JSON gained increased use with the use of dynamic load Content
web pages with Javascript (technique called "Ajax"). The serialization
JSON is very simple and results in a
little verbose structure which shows a great alternative to XML.
JSON serialization allows the structure of complex objects, such as lists and
subproperties. JSON is becoming the most widely used standard for integration
data between repositories and frameworks, is also becoming the standard
native storage in some modern databases.
(The [Glossary](/% C3% A1rio Gloss / # json))

`` ++++++:
* Ease to represent hierarchies
* Supports typing values
* Ease of use (any programming language easily read)
* Can be used directly in web browsers (read by javascript)
* Standardized Format ([RFC 7159 of the IETF](https://tools.ietf.org/html/rfc7159)
  [ECMA-404](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf))
* Possibility to define the validation scheme
* Lighter to process the XML

------ ``:

##### XML

Means XML [Extensible Markup Language](http://pt.wikipedia.org/wiki/XML)
and is a syntax for encoding documents in a machine-readable format.
It is text-based and has as some of its
[Goals](http://www.w3.org/TR/REC-xml/#sec-origin-goals) ease of
use and readability.
XML is widely used as a data exchange format on the Web Classics
SOAP Services. Despite the widespread use, it is becoming less encouraged
use this format for application integration. Instead,
recommend using JSON for saving bandwidth and be processing more
lightweight. (The [Glossary](/% C3% A1rio Gloss / # xml)).

`` ++++++:
* Ease to represent hierarchies
* Supports typing values
* Extensive support tools
* Standardized Format ([W3C](http://www.w3.org/TR/2006/REC-xml11-20060816/))
* Possilidade set of schema validation

------ ``:
* Verbose (the generated files are larger)
* Increased spent processing for generation and consumption over JSON.

#### Geo Formats

Some file formats cater specifically to represent data
geographic. The following are the main open standards related to
geo data, along with the advantages and disadvantages of each.

##### GeoJSON

It is an open format based on [JSON](/% C3% A1rio Gloss / json #) to represent
geographical information. Enables representing forms such as points, lines and
polygons with geographic coordinates, along with their attributes
non-spatial.
The GeoJSON is not maintained by a formal standardization body, as some
other formats for geographic information. Instead, it is
[Specified](http://geojson.org/geojson-spec.html)
by a working group of developers.
(The [Glossary](/% C3% A1rio Gloss / # GeoJSON)).

`` ++++++:
* All the benefits of JSON
* Good support tools
* Lightweight processing

------ ``:
* Lack standardization (although the specification is open)

##### KML

Acronym for
[Keyhole Markup Language](https://en.wikipedia.org/wiki/Keyhole_Markup_Language) _. _
It is an XML-based format, originally developed by Google and later
[Standardized](http://www.opengeospatial.org/standards/kml) by Open Geospatial
Consortium. May represent geographical information, such as
placemarks, images, polygons, three dimensional models, or descriptions
textual, using latitude, longitude and elevation coordinates as
[WGS84](https://en.wikipedia.org/wiki/World_Geodetic_System). system
(The [Glossary](/% C3% A1rio Gloss / # kml)).

`` ++++++:
* Standardized Format
* Good support tools

------ ``:
* Heavier processing the GeoJSON

ESRI Shapefile #####

Open for geospatial data format developed by ESRI, which
produces software solutions for geographic information systems (GIS).
Despite being maintained by a company, its
[Specification](http://www.esri.com/library/whitepapers/pdfs/shapefile.pdf)
is open and is implemented by virtually all GIS tools.
(The [Glossary](/% C3% A1rio Gloss / # shapefile)).

`` ++++++:
* Extensive support tools

------ ``:
* Lack standardization (although the specification is open)
* Need multiple files to a single map
* It has limitations in storage attributes

#### Based on RDF formats

The family of formats
[RDF](https://pt.wikipedia.org/wiki/Resource_Description_Framework)
is based on a metamodel graph to indicate the relationships between
nodes, where each node can be anything about which wants to assert
something. This metamodel allows to establish semantic relations between the
data, to describe them as a model (vocabulary or ontology)
preset information for that domain.

This meta-data as graphs can be stored in databases
specialized data, called stores_ _triple or triple banks, a
reference to how to describe the graph listing each triple node-edge-node,
representing subject, predicate and object.

When recording RDF data in a file, however, you must choose one of
multiple syntaxes possible to represent the graph as a sequence of
characters: XML, N-Triples, Turtle, JSON-LD, RDFa, etc.
(The [Glossary](/% C3% A1rio Gloss / rdf #)).

The following are some advantages and disadvantages of using RDF in general for the
publication of data. Then, we present a brief description and
advantages and disadvantages of each file (syntax) formats
specific data in RDF.

`` ++++++:
* Possibility of using semantics to describe the data
* Facilitates the crossing and link data between different sources
* Maximizes the reuse of specialized tools for data given domain information
* Facilitates knowledge discovery by allowing more complex queries using data from various domains

------ ``:
* Needs to develop
  [Ontology](https://pt.wikipedia.org/wiki/Ontologia_ (ci AAncia_da_computa% C3% A7% C3%% C3% A3o))
  that describes the concepts related to data
* Greater complexity of the metamodel (graph)
* Greater heterogeneity in the data structure

##### Turtle

Turtle _ means "[Terse RDF Triple Language](https://en.wikipedia.org/wiki/Turtle_ (syntax))" _,
or succinct language of RDF triples. Was created as a simplified syntax
read by both humans and by machines and
[Standardized](http://www.w3.org/TR/turtle/) in 2014.
The indentation and the use of prefixes are
elements that facilitate the reading, as well as the grouping of triples that
have the same subject or having the same subject and the same predicate.

`` ++++++:
* Succinct (the generated files are smaller)
* Simplicity reading by humans
* Standardized Format
* Good support tools
* Lightweight processing

------ ``:

##### RDF / XML

The original syntax, when the RDF was initially set standard, was
based on XML. As the first syntax for RDF, your support
tools is excellent. Moreover, the verbosity of the XML and
its hierarchical structure, the generated files are usually complex and
difficult to read.

`` ++++++:
* Standardized Format
* Extensive support tools

------ ``:
* Difficulty reading by humans
* Uses hierarchical structure to represent a model of graphs
* Verbose (the generated files are larger)
* Heavier processing

##### JSON-LD

It is a format based on
[JSON for Linked Data](https://en.wikipedia.org/wiki/JSON-LD), also
[Standardized](http://www.w3.org/TR/json-ld/) in 2014.
Brings all the advantages of JSON format. A mapping framework for IRIs
can optionally be separated into a JSON document context, which leaves
the main JSON, where the data are essentially the same structure that
JSON a common document.

`` ++++++:
* Standardized Format
* Lightweight processing
* Can be used directly in web browsers (read by javascript)

------ ``:
* Lower support tools to be a more recent pattern

