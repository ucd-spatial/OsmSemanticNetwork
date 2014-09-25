================================================================================
     The OSM Semantic Network
================================================================================

Project home page:
http://wiki.openstreetmap.org/wiki/OSMSemanticNetwork

These RDF graphs represent the concepts used in the OpenStreetMap dataset.
The RDF datasets contained in this folder have been extracted by 
the OpenStreetMap Wiki Crawler 
(http://github.com/ucd-spatial/OsmWikiCrawler).
The semantic network is represented as a SKOS vocabulary 
(see http://www.w3.org/2004/02/skos), validated using the service
http://demo.semantic-web.at:8080/SkosServices

This data is derived from information collected by OpenStreetMap  
(http://www.openstreetmap.org) and licensed under the same terms as the OSM
data, currently the Creative Commons Attribution-ShareAlike 2.0 license.

RDF is a standard Semantic Web format: http://www.w3.org/RDF
The files were validated with http://www.w3.org/RDF/Validator
This material is Open Knowledge. http://opendefinition.org

================================================================================
Author:  Andrea Ballatore
		 http://sites.google.com/site/andreaballatore
Contact: myname.mysurname@gmail.com
================================================================================
  RDF/SKOS content: 
================================================================================

* Concepts *
osmwiki:Key:⟨key⟩					OSM Key.
osmwiki:Tag:⟨key = value⟩			OSM Tag.
osmwiki:Proposed features/⟨tag⟩		OSM Proposed Tag.
osmwiki:Relations/Proposed/⟨tag⟩		OSM Proposed Relation.
osmwiki:⟨page⟩ 						OSM Cluster page.
others								LGD and Wikipedia nodes.

* Properties *
osmwiki#link				Internal hyperlink within OSM Wiki.
osmwiki#key					Link to OSM key page.
osmwiki#valueLabel		  	A value of a OSM tag.
osmwiki#keyLabel	 		OSM key.
rdf:rdf-schema#comment		OSM Tag description.
osmwiki#combinedWith		Tag is combined with target tag.
osmwiki#wikipediaLink		A link to a Wikipedia page.
osmwiki#redirect		 	Redirect to a OSM wiki page.
osmwiki#implies		 		Tag implies target tag.

* Examples *
amenity: http://wiki.openstreetmap.org/wiki/Key:amenity
amenity=university: http://wiki.openstreetmap.org/wiki/Tag:amenity%3Duniversity
waterway=river: http://wiki.openstreetmap.org/wiki/Tag:waterway%3Driver
shop=books: http://wiki.openstreetmap.org/wiki/Tag:shop%3Dbooks

================================================================================
Folder content: 
* NT files, e.g. OSM_Semantic_Network-yyyy-mm-dd.skos.nt|rdf
	the OSM semantic network extracted on a certain date (yyyy-mm-dd).
* RDF files: the same content as the NT files in RDF format.
* archive: previous versions of the OSM Semantic Network
================================================================================

REFERENCE:

If you use this work in your research, please reference this paper:

--------------------------------------------------------------------------------
 Ballatore, A., Bertolotto, M., & Wilson, D. C. (2013). Geographic knowledge extraction 
 and semantic similarity in OpenStreetMap. Knowledge and information systems, 37(1), 61-81.
--------------------------------------------------------------------------------

BIBTEX entry:

@article{ballatore2013geoknowledgeosm,
  title={Geographic knowledge extraction and semantic similarity in OpenStreetMap},
  author={Ballatore, Andrea and Bertolotto, Michela and Wilson, David C},
  journal={Knowledge and Information Systems},
  volume={37},
  number={1},
  pages={61--81},
  year={2013},
  publisher={Springer}
}

================================================================================
Last update: September 2014