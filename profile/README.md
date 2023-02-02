# OpenCost: Automated, standardized delivery and open provision of publication costs and publishing agreements.


The goal of the openCost project is to create a technical infrastructure that
allows publication costs to be shared freely via standardized interfaces and
formats. This will enable cost transparency on an institutional, national and
international level.

To this end, a metadata schema will be developed, that allows scientific
institutions to handle all costs relevant to scientific publications in a
structured, machine readable form. Starting out with publications costs
associated with Open Access publishing governed by _A_rticle _P_rocessing
_C_arges (APC) openCost will add other cost types before tackling more complex
constructions like transformative agreements or memberships etc.

For automatic exchange, openCost proposes the established OAI-PMH interface and
will thus starts out to serialize the proposed formats in XML, while keeping
other serializations like JSON in mind.

As a _proof of concept_ publication servers from the partners at Bielefeld and
Regensburg University as well as the institutions in the JOIN² collaboration
will provide their collected data in the newly invented openCost structures and
expose them vai OAI-PMH. To demonstrate the viability of our approach on the
recipient side the well established aggregation service OpenAPC hosted by
Bielefeld University will be enhanced to handle the full openCost data set and
use the provided data by the partners.  However, this should not hinder other
interested parties to join in and do the same.

To further cost transparency for scientists, another working package focuses on
the extension of the Electronic Journals Library (EZB) to incorporate
publication cost data in their end user displays. For this purpose, an interface
between OpenAPC and the EZB based on the openCost formats will be implemented.
Furthermore, additions to the EZB backend will allow libraries to enter
information on cost coverage procedures on site, institution-specific agreements
like memberships or transformative agreements. These informations will be made
available to users based on journal selected and affiliation and thus enable EZB
to act as a central information platform for researchers.

openCost thus focuses on


- the development of a standardized metadata schema for the collection and
  transfer of data on publication costs
- the implementation of an open interface for harvesting and querying this data
- extension of the EZB for managing and displaying information on 
  publication costs and their coverage at the users institution

For more details recent news and developments visit our web page at [https://opencost.de](https://opencost.de)

<!-- vim: spell spelllang=en_gb bomb
-->

