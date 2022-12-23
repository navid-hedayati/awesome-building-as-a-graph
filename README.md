# awesome-building-as-a-graph

A curated list of ressources about using graphs to represent data in the AEC (Architecture, Engineering, Construction) domain.


## Research groups and projects

- [Topologic](https://topologic.app/); Research Group focussing on topological aspects.

### Workshops and Conferences

- [LDAC - Linked Data in Architecture and Construction](http://www.linkedbuildingdata.net/ldac/index.html); The LDAC workshop series provides a focused overview on technical and applied research on the usage of semantic web, linked data and web of data technologies for architecture and construction (design, engineering, construction, operation, etc.)


## Tools and Technologies

- [BHoM](https://github.com/BHoM/BHoM); Open source interoperability framework for creating, and sharing data related to the built environment.

- [Topologic](https://topologic.app/software/); Software for

- [IFCOpenShell](https://ifcopenshell.org/); Open Source IFC toolkit and geometry engine. Helpful when integrating graphs with IFC.

- [linked data bim web applicatoin](https://ld-bim.web.app/); Online tool to render IFC files and query these (e.g. via SPARQL)

- [Archilogic](https://www.archilogic.com/); A tool for space planning. Recently new features have been created to desplay layouts in graph data as well. (see [lin](khttps://www.linkedin.com/posts/atfritsch_3dmodels-graphdatabase-javascript-activity-6937417840807288832-7aEM?utm_source=linkedin_share&utm_medium=member_desktop_web))

## Learning Sources

## Startup and Companies

- [Gropyus](https://www.gropyus.com/de); German startup focussing on timber mass prefabrication, covering full lifecycle. Using massively graph technogloy.
-

### Property graph based

General discussion goes here

### Triple graph based

General pros and cons goes here

### Historical development

## Literature

- Krijnen and Beetz, [“A SPARQL Query Engine for Binary-Formatted IFC Building Models.”](https://linkinghub.elsevier.com/retrieve/pii/S092658051731049X)
- Guo, Onstein, and Rosa, [“An Approach of Automatic SPARQL Generation for BIM Data Extraction.”](https://www.mdpi.com/2076-3417/10/24/8794)
- Bonduel et al., [“The IFC to Linked Building Data Converter - Current Status.”](http://ceur-ws.org/Vol-2159/04paper.pdf); Focus on IFC to RDF conversion


## Ontologies:

When it comes to linked data in the AEC domain, there are a variety of ontologies that have been developed to describe different aspects of a building. Below, we have provided a list of some of the existing ontologies in this domain, catagorized into their specific domain of discourse:

### Building:

* [IfcOWL](https://standards.buildingsmart.org/IFC/DEV/IFC4/ADD2_TC1/OWL/index.html): Directly based on the ['IFC4_ADD2_TC1'](https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/) EXPRESS schema, using ['IFC-to-RDF'](https://github.com/pipauwel/IFCtoRDF) convertor. It contains all classes and properties that are outlined in the IFC schema. 
IFC, or the Industry Foundation Classes are an open international standard for Building Information Model (BIM) data that are exchanged and shared among software applications used by the various participants in the construction or facility management industry sector. The standard includes definitions that cover data required for buildings over their life cycle. This release, and upcoming releases, extend the scope to include data definitions for infrastructure assets over their life cycle as well.
Hence, IfcOWL is a comprehensive ontology that contains resources applicable to the entire lifecycle of a building, and all its associated disciplines.

* [Digital Construction Ontologies (DiCon)](https://digitalconstruction.github.io/v/0.5/): DiCon is a modularized ontology network designed to enable semantic interoperability between systems in the construction and renovation domain. Its various modules are further sighted here in their respective categories.

### Building topologies:

* [Building Topology Ontology (BOT)](https://w3c-lbd-cg.github.io/bot/): A minimal ontology used to describe the core topological concepts of a building. The relationships between spatial elements in a building and their surrounding building elements can be effectively mapped through this ontology.
BOT offers many alignment modules with other ontologies, including:
    * [BRICK](https://raw.githubusercontent.com/w3c-lbd-cg/bot/master/BRICKAlignment.ttl)
    * [DERIROOMS](https://raw.githubusercontent.com/w3c-lbd-cg/bot/master/DERIROOMAlignment.ttl)
    * [DogOnt](https://raw.githubusercontent.com/w3c-lbd-cg/bot/master/DOGONTAlignment.ttl)
    * [DUL](https://raw.githubusercontent.com/w3c-lbd-cg/bot/master/DULAlignment.ttl)
    * [IfcOWL](https://raw.githubusercontent.com/w3c-lbd-cg/bot/master/IFCOWL4_ADD2Alignment.ttl)
    * [SAREF4Bldg](https://raw.githubusercontent.com/w3c-lbd-cg/bot/master/SAREF4BLDGAlignment.ttl)
    * [ThinkHome](https://raw.githubusercontent.com/w3c-lbd-cg/bot/master/THINKHOMEAlignment.ttl)
    * [Realestate Core](https://raw.githubusercontent.com/w3c-lbd-cg/bot/master/RECAlignment.ttl)

* [Bosch Building Technologies - Foundation Ontology](https://github.com/boschglobal/building-technologies-ontology-central/tree/main/com/bosch/bt/Foundation/2.0.0): A module of larger ontological framework developed by [Bosch Building Technologies](https://www.boschbuildingtechnologies.com/xc/en/). The foundation ontology is the digital common foundation layer of other domain ontology models within this ontological framework. The Foundation Ontology model defines common concepts like the space topology structure, assets, data points, etc.

### Building elements:


