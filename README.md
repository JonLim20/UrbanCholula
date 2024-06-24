# UrbanCholula
This guide is a step-by-step workflow for establishing an archaeological database using only open software, prepared by the Center for Advanced Spatial Technologies, University of Arkansas. It was produced for the the Urban Cholula Salvage Archaeology Geodatabase (UCSAG) project, founded by the National Endowment for the Humanities Award PW-285206-22. Spanish and English versions of the current version (2.0) are available, alongside the LaTeX source code and figures used for compiling the guide. The reasons behind creating this guide are twofold. First, we find that many archaeologists begin with data collection, record observations in various fields, further organized into tables, rather than beginning data collection and management within a geodatabase. Unless the archaeologist has training and access to GIS, programming, and/or access to relatively easy-to-use geospatial software (e.g., ESRI products), data often remains in more simple digital, digitized forms. These forms are often isolated, i.e., they don’t link or interact with one another, nor are they integrated with other forms of digital data (e.g., georeferenced maps, imagery, point clouds, GNSS data). It can be harder for that data to be indexed, located, reused, compared, and/or incorporated by other researchers, creating a gap between data use and data potential. Second, opportunities for training in spatial data methods in archaeology, let alone spatial data management, are limited (see Klehm 2023; https://doi.org/10.1017/aap.2022.38). As with spatial methods in archaeology and the digital humanities more broadly, there are a series of technical and logistical “bottlenecks” that humanists studying the past find themselves facing: entry-level geospatial courses exist in university coursework, but finding content tailored to archaeological and heritage problems is more difficult to come by; training is found either at the entry or expert level, with little resources or mentorship to bridge that gap; few opportunities exist to explore the potential of new equipment and software; and support systems for geospatial software or instruments are often developed for other industries (e.g. agriculture, forestry), making it difficult to find help. There exists a real need for guidance, mentorship, and training materials.

This guide was developed based on conversations with archaeological colleagues in Mexico and their experiences of data curation, digitization, and organization. They are struggling with the backlog of processing decades of rescue (or salvage) archaeology projects that are in various states of digitization. The data have fairly standardized forms (e.g., artifacts by type, human remains, faunal remains) but are not associated with one another, and their spatial relationships are yet to be explored. Further, our colleagues expressed a strong interest in being able to share the CRM data collectively with other researchers, as—like in the United States—there is less frequently published and harder to find, but no less valuable.

Our workflow intentionally uses FOSS (free and open-source software) platform solutions, including PostgreSQL, PostGIS, and QGIS, as part of our commitment to making not just data more widely available and accessible, but research capabilities and training more equitable despite location and limited resources.
