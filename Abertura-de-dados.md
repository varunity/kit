---
published: true
permalink: / Opening-of-data /
layout: slate
filename: Opening-of-dados.md
TITLE: opening databases Procedure - Set Open Data
desc: This is the process that runs on each start up project data of the institution.
---

Database-opening
====

This is the process that runs on each start up project data
(For example, opening a project database of a system
information in a specific business area). Depending on the capacity
the institution, may be performed one or more instances of this process
simultaneously at any given time.

Note .: "open by default". <a name="restricao"> </a>
This process refers to the activities for opening data of a
pre-existing system / solution. Are actually "fixes" systems
that do not have open data. It is important that, in future,
systems are designed to provide data that already since its inception.
Every public informational system that does not deal with information that is
find within the exceçõs [LAI]({{}} site.baseurl Glossary # lai) must have their data
open by default.

[<Img alt = "Diagram of opening a data process" src="https://raw.githubusercontent.com/dadosgovbr/kit/master/public/img/Processo%20Abertura%20base%20de%20dados.png">](https://raw.githubusercontent.com/dadosgovbr/kit/master/public/img/Processo%20Abertura%20base%20de%20dados%20-%20com%20titulo.png)

## Plan Document Open Data - PDA

The PDA institution guide the process of opening
data on the scope, estimated timeframe, stakeholders, among others.
Should bring the Plan to Open Data Project Open Data
the parts dealing with the following aspects:

* Scope
  * ** Data **: what is (or what) databases, which are the tables,
    spreadsheets, part or section of data is feasible for this iteration of
    opening process;
  * ** ** Granularity: if the data are separated by some criterion
    temporal or spatial;
  * Minimum ** technological quality, defining, for example **:
    * The form of data availability (if one is developed
      [API]({{}} site.baseurl Glossary # api) open data or will only
      files available to the extraction, for example);
    * If any relationship with a source of data will be established
      external open data or not;
    * It will be held sanitization process data (eg,
      correct inconsistencies or duplicate records);
* Estimated considering:
    * Commitments that may have been made in
      other plans besides the PDA (eg .: institutional strategic planning and
      of information technology master plan for information technology,
      action plan [Open Government Partnership](http://www.cgu.gov.br/governoaberto/), etc.);
    * Ability to execute the project (quantity of skilled personnel,
      technology infrastructure maturity with the process of opening
      data processing);
* Stakeholders: representative of the committee that monitors the implementation of
    PDA, area manager responsible for databases, with experts
    business knowledge, manager of IT, developers,
    data analysts, potential users (organs, enterprises, experts),
    among others.

If the Plan Open Data has been silent on some of these
aspects, they should be defined during the
[Project kickoff meeting](# reunite% C3% A3o-in-a% C3% ADcio-of-project).

* Input to: *

* [Meeting project initiation](# reunite% C3% A3o-in-a% C3% ADcio-of-project)
* [Deciding minimum quality](# decide quality-m% C3% ADnima)

## Meeting of project initiation

At this first meeting between the stakeholders in the project will be reviewed
the scope and the estimated term of the project, as defined in [Plan Open Data](# document-data-plan-open)
the institution. Eventually some people participate across from
several projects opening data in the institution. For example, people
IT department running the activities of provision of infrastructure and / or developing software.

One aspect that has great impact on the scope and estimated time for the project is
the choice of the form of publication of the data. For example, developing an API
open data requires more effort than simply publish files
static.
But if the data volume is large, it may be advantageous for citizens to be able to
using the methods of consultation and filters that can offer an API for
receive only the data that interest you.
Some of the considerations in deciding whether or not the
development of API are shown in the article called
[* "Do you really need an API?" *](Https://www.peterkrantz.com/2012/publishing-open-data-api-design/).

* Next step: * [Request documentation](# requested documents% C3% A7% C3% A3o)

## Request documentation

Request schema and documentation database. Ex .: UML models or
entity-relationship data dictionary, etc. All kinds of documentation
implementation teams to help understand, together with experts
business, the best way to structure the data for publication.

Documentation related to the data set are very useful, especially
for consumers of open data and should also be coupled [cataloged
with the data on dados.gov.br](catalog #-in-dadosgovbr).

* Next step: * [Set data structure](# define-structure-of-data)

## Set data structure

At this stage the data output formats are also defined.
[XML]({{}} site.baseurl Glossary # xml) [CSV]({{}} site.baseurl Glossary # csv) and
[JSON]({{}} site.baseurl Glossary # json) are useful for specific situations.

The CSV sheets have the advantage of being easily opened and manipulated in
any spreadsheet editor, such as Calc and Excel, including a person who
not have programming knowledge. Moreover, they are also easy to
consumed by applications.

The XML and JSON files have the advantage that they permit the validation of various
data types such as integers or decimal numbers. Furthermore, let
the nesting hierarchy data structures, which facilitates work with
data as compared to the planar structure of the CSV columns.
Also allow the inclusion of markings of links to other resources data
through the web.

In case of publication CSV spreadsheet, define and write documentation of
what they are and what the columns mean and what are the types of data
acceptable in each column of each spreadsheet.

In case of publication of XML or JSON files, define the basic structure of
document. It is possible, but not necessary, to establish XML Schema documents
or JSON Schema for validation.

* Next step: * [Perform extraction](# place extra% C3% A7% C3% A3o)

## Perform extraction

Perform initial extraction of data from the production environment of the base
data, to where the base will be made available as open data.

For example, it has been decided to publish the data in csv files, this
step includes hosting the extraction csv file on a server to
web. If it has been decided to publish an API open data, this step
contemplates the load database which is accessed directly by layer
implementation of the API.

* Next step: * [Deciding minimum quality](# decide quality-m% C3% ADnima)

## Decide minimum quality

From the time that data is available to verify the
technical implementation team and business experts, will be evaluated
the need to sanitize the data before publication.

Set by agreement between the parties concerned the minimum data quality
open published, in order to facilitate their timely publication within
the capacity of the institution.

More considerations on data requirements can be found in
[Technical Primer for Publication of Open Data in Brazil](http://dados.gov.br/cartilha-publication data-abertos/)
Chapter 6.

* Next step: * [Develop API](# develop solution)

## Develop solution

The work to be done in this step varies widely, depending on the type of
open data solution chosen in
[Beginning of the project]((# reunite% C3% A3o-in-a% C3% ADcio-of-project)):
availability of files [CSV]({{}} site.baseurl Glossary # csv), some kind of
[_dumps _]({{}} Site.baseurl Glossary # dump) data, or even the creation of a
[API]({{}} site.baseurl Glossary # api) open data.

In cases of diponibilização files or _dumps_, this step includes
the creation of scripts [ETL]({{}} site.baseurl Glossary # etl) that make the cleaning
data determined in the [previous step](# decide-minimum quality).

In the case of developing an API, this step comprises
the development of software that will operate the service. The use is recommended
one ({{}} site.baseurl Glossary # method-Agile) [agile]method of software development.

This stage of development, one can gain a lot of productivity to
using [tools]({{}} # site.baseurl tools) appropriate to the type of solution
being developed.

In all cases, it is recommended that the available files or API
in development are visible to the entire internet, so
reduce barriers so that any interested in testing the solution
(Eg, another industry or organization with an interest in consuming
open data) can offer _feedback_ during development and
thus enhance the solution and ensure that when she is ready to answer
its purpose to be useful for data consumers.

* Next step: * [Automatic Update](# update% C3% A7% C3% A3o Auto-% C3% A1tica)

## Auto Update

Define and implement automatic periodic process of updating the data.
This step involves the negotiation of frequency and flow of
data between the environments that make up the solution architecture opening
data, as well as the creation of transformation scripts and load
([ETL]({{}} site.baseurl Glossary # etl)).

This moment is important to ensure the timeliness of published data,
that the more current, the more value they have.

* Next step: * [Disclose open data](# spread-open-data)

## Disclose open data

Once the solution is in open data quality conditions
sufficient for the closure of this opening project data,
can initiate the wide dissemination of their results.

This can be done by communication channels and that the agency has also
those who reach the audience that already anticipate being interested in the data,
such as mailing lists of [INDA]({{}} site.baseurl Glossary # inda) and
[Civic hackers]({{}} site.baseurl Glossary # hacker-civic), as well as the organizations
civil society that accompany the theme finalistic data.

At this moment we can not decide for or planning a future
[Hackaton]({{}} site.baseurl Glossary # hackathon) or contest open data.

Importantly, though the data logically comprise assets
Digital institution and therefore should be available and visible in
appropriate place on your own site.

* Next step: * [Cataloging in dados.gov.br](# cataloging-in-dadosgovbr)

## Cataloging in dados.gov.br

The purpose of this catalog is to make data "discoverable" on the web for their
interested. This increases the chances of people finding data
readily without resort to [sic]({{}} site.baseurl Glossary # sic) of their
organization.

To catalog the new dataset in [dados.gov.br](http://dados.gov.br)
is required to raise a minimum set of metadata that are used in the portal
These metadata are further described in
[Technical Primer for Publication of Open Data in Brazil](http://dados.gov.br/cartilha-publication data-abertos/)
Chapter 7.

