================================================================================
 OpenStreetMap (OSM) Semantic Network
================================================================================

The RDF datasets contained in this folder have been extracted by 
the OpenStreetMap Wiki Crawler 
(http://github.com/ucd-spatial/OsmWikiCrawler).
This data is derived from information collected by OpenStreetMap  
(http://www.openstreetmap.org) and licensed under the same terms as the OSM
data, currently the Creative Commons Attribution-ShareAlike 2.0 license.

Please note that this project uses data provided by OpenStreetMap
(http://www.openstreetmap.org), but is not affiliated with the project.
RDF is a standard Semantic Web format: http://www.w3.org/RDF
This material is Open Knowledge. http://opendefinition.org

================================================================================
  RDF content: 
================================================================================

* Vertices *

osmwiki:Key:⟨key⟩					OSM Key.
osmwiki:Tag:⟨key = value⟩			OSM Tag.
osmwiki:Proposed features/⟨tag⟩		OSM Proposed Tag.
osmwiki:Relations/Proposed/⟨tag⟩		OSM Proposed Relation.
osmwiki:⟨page⟩ 						OSM Cluster page.
others								LGD and Wikipedia nodes.

* Edges *

osmwiki:link				Internal hyperlink within OSM Wiki.
osmwiki:key					Link to OSM key page.
osmwiki:valueLabel		  	A value of a OSM tag.
osmwiki:keyLabel	 		OSM key.
rdf:rdf-schema#comment		OSM Tag description.
osmwiki:combinedWith		Tag is combined with target tag.
osmwiki:wikipediaLink		A link to a Wikipedia page.
osmwiki:redirect		 	Redirect to a OSM wiki page.
owl:owl#equivalentClass		Equivalent class in other ontology.
osmwiki:implies		 		Tag implies target tag.

================================================================================
Folder content: 
* NT files, e.g. OSM_Semantic_Network-yyyy-mm-dd.nt: the OSM semantic network
	extracted on a certain date (yyyy-mm-dd).
* RDF files: the same content as the NT files in RDF format.
================================================================================
Author: Andrea Ballatore (School of Computer Science and Informatics,
	University College Dublin)
Project home page: http://github.com/ucd-spatial
================================================================================
