## Sources
This repository contains all the files created to define, support or test Plinian Core. This is a standard in the works 

## Documentation

About Plinian Core:
* https://github.com/tdwg/PlinianCore/wiki/About

Plinian Core terms and structure documentation:
*  https://github.com/tdwg/PlinianCore/wiki

## Recommended citation

Plinian Core Task Group. 2021. Plinian Core, a Species-level Data Specification. Biodiversity Information Standards (TDWG).
https://github.com/tdwg/PlinianCore

## Plinian Core Task Group Charter
This group works forward to develop a data specification -the Plinian Core-  that can be used to describe different aspects of  biological species information. By "biological species Information" all kinds of properties or traits related to taxa, --biological and non-biological -- are included. Thus, for instance, terms pertaining to descriptions,  legal aspects, conservation, management, demography, nomenclature, and related resources are incorporated.
 
The Plinian Core’s aim is to facilitate the exchange of information about species and higher taxa, covering biological and non biological aspects pertaining to all taxonomic groups.

### What is in scope?
*  Species level catalogs of any kind of biological objects or data.
*  Terminology associated with biological collection data.
*  Striving for compatibility with other biodiversity-related standards.
*  Facilitating the addition of components and attributes of biological data.

### Motivation
Species level information is one of the most demanded services or products from the taxonomic experts. We see species pages everywhere: from on-line floras and faunas to CITES manuals for custom agents, to guides for naturalists. As such, aiming to produce a data specification to facilitate data integration and interoperability among species pages is a mean with great potential to increase efficiency and cooperative work

### Goals outputs and outcomes (current status and plans)
* An assessment on how Plinian Core relates to other TDWG standards. Done: https://doi.org/10.3897/biss.2.25869 
* A detailed documentation on the different terms included in Plinian Core. Done: https://github.com/tdwg/PlinianCore/wiki 
* At least three implementations of species information systems based on Plinian Core. Done : See below, section “Relevant projects and initiatives”
* A SPARQL Endpoint and underlying ontology implemented and working. Done: https://datos.iepnb.es/visor/
* A standard specification complying with the TDWG SDS. The TG plans to make a formal submission of the documentation to the TDWG Executive by November 27th, 2020. In progress

(See current status below)

### History/context 
* Plinian Core started in 2004 as a dialog between Maria Mora (INBio, Costa Rica) and Francisco Pando (GBIF-Spain) around the idea of developing a common system to gather, manage and publish "species-level information. The basis and use cases for these ideas were INBIO's "species pages" (UBIS) and the “CD-ROM of Flora Iberica".
* More concrete ideas were developed during the GBIF-organized meeting "Building SpeciesBanks: How Shall We Shape the Future?” (Amsterdam, 2005).
* In 2005-2006, an intense collaboration between INBio and GBIF.ES was maintained, from which the first version of the standard expressed as xsd is created, and receives its current name: Plinian Core.
* 2007-2009 University of Granada (Spain) and the Colombian Biodiversity Information System (SiB -Colombia) adheres to the initiative.
* INBio develops the first "implementable" version of the PliC: that is dubbed "Flat Plinian".
* A portal of "species and specimens" is developed on the architecture of the GBIF data portal (Tapir), by INBio, in the context of IABIN (the Inter-American Biodiversity Information Network), and with the collaboration of GBIF.ES
* 2011 Collaboration with Encyclopedia of Life started. Strategic decision to separate a conceptual model (later called "Abstract Model) from implementations adopted. CONABIO (Mexico) becomes an active partner in the development of PliC
* 2012 Plinian Core activities start aligning with TDWG and procedures; globalization of the developments. 
* 2012-Partnership for the development of Plinian Core in this new phase incorporated the University of Granada (UG, Spain), the Colombian Biodiversity information System (SiB-Colombia, Colombia), the National Commission for the Knowledge and Use of Biodiversity (Conabio, Mexico) and the University of São Paulo (USP, Brazil), and workshops and working sessions were organized, some sponsored by the involved participants, some by GBIF.
* As a result of the process started in 2012, a new version, Plinian Core v3.1 was defined. This provides more flexibility to fully represent the information of a species in a variety of scenarios. New elements to deal with aspects such as IPR, related resources, references, etc. were introduced, and elements already included were better-defined and documented.
* The “Species Information Interest Group”was approved by the TDWG Executive in 2013. Plinian Core is identified as a priority task within that IG.
* 2014-2018 First full implementations of Plinian core are put in Production (see section “Relevant projects and initiatives”)
* 2017 -2019 Advancing implementation of Plinian Core in the Living Atlases in coordination with the LA community for the BIE module of Living Atlases.  (see: Vargas & al., 2018)

### Convenor
Francisco Pando - Real Jardín Botánico -CSIC. Madrid (pando@rjb.csic.es)

### Core Members
| Name | Role  |
|------------------|:-----------------------------------|
| María Mora | Biodiversity informatics expertise  | 
| William Ulate| Biodiversity informatics expertise |
| Manuel Vargas | Biodiversity informatics expertise |
| Camila Plata | Biodiversity informatics expertise  |
| Gloria Martínez Sagarra  |  Biodiversity expertise |
| José Cuadra| Biodiversity informatics expertise |

### Becoming involved
This group welcomes participation from all interested parties on implementing species catalogs, species pages or other usages or profiles of the standard. Also individuals who have a vested interest in maintaining the stability and interoperability of Plinian Core. 

 If you are interested in participating in the group, please contact the convenor or a core member.
 
### Latest developments and current status (2021)
During this year the Plinian Core “core members” has been meeting and working on a weekly basis. We can articulate the work done in  three areas:
 
Improving the coherence and detail of PliC terms' definitions
Improving the documentation available in the PliC GitHub repository
Presenting the documentation standard in a format compliant with TDWG's SDS 
 
In this latest area, we have counted with the invaluable help of Steve Baskauf , who has provided us  with constant advice on how to do things (e.g. dealing with terms borrowed from other standards, treatment of controlled vocabularies, etc.) and also with scripts to produce the normative documentation for Plinian Core. Draft documentation in SDS compliant form has been already produced.

	
https://github.com/mfvargas/rs.tdwg.org/blob/master/process/page_build_scripts/pc.md

We are now (Oct. 2021) in the final stages prior to submit Plinian Core for evaluation and eventual approval by the TDWG executive and the community at large.

### Relevant projects and initiatives
 
#### Atlas de la Biodiversidad de Costa Rica – CRBio:

   See species pages

http://www.crbio.cr/crbio/?page_id=61&lang=en 

#### Spanish Ministry for the Ecological transition

##### Species Information System:
	
https://www.miteco.gob.es/es/biodiversidad/servicios/banco-datos-naturaleza/Eidos_acceso.aspx 
	
##### SPARQL Endpoint
	
https://datos.iepnb.es/visor/ 
		
Underlying ontology
	
https://datos.iepnb.es/def/sector-publico/medio-ambiente/pliniancore/
		
...which may be visualized here:
		
http://www.visualdataweb.de/webvowl/#iri=https://datos.iepnb.es/def/sector-publico/medio-ambiente/pliniancore/3.0.0 

#### Vasque Country (Spain) Official Nature Information System:

https://www.ivap.euskadi.eus/contenidos/ds_informes_estudios/plinian_core/eu_def/adjuntos/plinian.pdf 
	
Specification for creating DwC-Archives based on Plinian Core 
	
https://opendata.euskadi.eus/catalogo/-/txostenak-ikerketak/euskadiko-naturari-buruzko-informazio-sisteman-jasota-dauden-espezieak-deskribatzen-dituen-informazioa/
	
#### Colombian Biodiversity Catalog

Catalog:
	
https://catalogo.biodiversidad.co/
		
Documentación for exotic and threatened species:
	
http://repository.humboldt.org.co/handle/20.500.11761/9691
		
http://repository.humboldt.org.co/handle/20.500.11761/9690
		
Documentation about species pages editor:
		http://repository.humboldt.org.co/handle/20.500.11761/9689

#### Enciclovida, Mexican species catalog:

https://enciclovida.mx/

### References and resources
Gerbracht J (2018) A Content Management System and underlying models for avian taxonomic monographs. Biodiversity Information Science and Standards 2: e25693. https://doi.org/10.3897/biss.2.25693 

Pando F (2017) How species interactions are managed in Plinian Core: Status and questions. Proceedings of TDWG 1: e20556. https://doi.org/10.3897/tdwgproceedings.1.20556 ;  https://api.zotero.org/users/7403307/publications/items/YNS4J57J/file/view (full presentation)

Pando F (2018) Comparison of species information TDWG standards from the point of view of the Plinian Core specification. Biodiversity Information Science and Standards 2: e25869. 
https://doi.org/10.3897/biss.2.25869

Plinian Core pages at TDWG’s GitHub: specification, documentation, issues and developments: https://github.com/tdwg/PlinianCore 

Vargas M, Mora M, Ulate W, Cuadra J (2018) The Living Atlases Community in Action: Sharing Species Pages through the Atlas of Living Costa Rica. Biodiversity Information Science and Standards 2: e25990. https://doi.org/10.3897/biss.2.25990

Vargas M, Mora Cross M, Cuadra J, Ulate Rodríguez W (2019) Sharing Species Pages in the Atlas of Living Costa Rica using Plinian Core. Biodiversity Information Science and Standards 3: e35474. 
https://doi.org/10.3897/biss.3.35474
