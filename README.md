# GIS Project — Via Francigena Mapping (QGIS)

This project presents a GIS-based spatial analysis and visualization of a selected section of the Via Francigena, developed using QGIS as part of an academic project.

The work focuses on integrating geographic, cultural, and environmental data to represent the walking route and its surrounding context in a clear and readable cartographic layout.

[map](./map.png)
---

## Project Objective

The objective of the project was to explore how Geographic Information Systems (GIS) can be used to map and contextualize a historical walking route, combining spatial accuracy with visual clarity.

The project aims to support route comprehension by highlighting both the main path and relevant points of cultural and environmental interest.

---

## Data and Layers

The map integrates multiple vector layers, including:

- Walking route geometry of the Via Francigena
- Cultural heritage points (archaeological sites, churches, landmarks)
- Forested areas and natural landscapes
- Hydrographic features (rivers, watercourses, waterfalls)
- Administrative and contextual boundaries
- Satellite basemap imagery for geographic reference

Each layer was styled to ensure visual hierarchy and thematic distinction.

## Pre-processing

External geospatial datasets were identified, selected, and downloaded to support the analysis of the surrounding environment along the Via Francigena route.

Forest coverage data were sourced from the **Regione Lazio open data portal**, providing detailed information on forest typologies across the entire regional territory.  
These datasets include attribute tables describing forest classification and characteristics relevant to the analysis.


## Attribute Data and Calculations

Attribute tables were actively used to enrich the spatial analysis.

Specific fields were created and calculated using the **QGIS Field Calculator** to store numeric and descriptive information related to the mapped features.  
These calculations were used to associate spatial features with meaningful values, such as distances, positional references, and contextual data linked to specific points along the route.

Although highly technical, this step was essential to connect spatial geometry with analytical information, enabling more precise interpretation of the mapped elements.


---

## Methodology

The project involved the following GIS operations:

- Importing and managing multiple vector datasets
- Ensuring coordinate reference system consistency across layers
- Structuring and organizing layers to improve map readability
- Applying thematic symbology to differentiate routes, natural areas, and points of interest
- Calculating route lengths for different walking segments
- Designing a final cartographic layout optimized for print and visual interpretation

Special attention was given to spatial clarity, scale representation, and legend readability.

---

## Spatial Analysis

The walking routes were analyzed to compute segment lengths, allowing a comparison between different paths within the mapped area.

This quantitative element complements the visual exploration of the route, supporting both navigational understanding and spatial evaluation.

## Spatial Data Processing

Since the forest datasets covered the entire Lazio region, spatial preprocessing was required to limit the analysis to the area of interest.

The following GIS operations were performed:

- Import of regional-scale forest vector layers into the QGIS project
- Overlay of the forest layer with the Via Francigena perimeter
- Spatial **clipping** of the forest dataset to isolate forest typologies within the selected route perimeter
- Extraction of forest-related attributes specific to the study area

This process allowed the transformation of a broad regional dataset into a focused, perimeter-specific layer, containing only the forest information relevant to the mapped section of the Via Francigena.


---

## Cartographic Design

The final output was designed as a print-ready map layout, including:

- Scale bar and north arrow
- Clear legend explaining all thematic layers
- Visual balance between satellite imagery and vector data
- Emphasis on the main walking route and cultural landmarks

The design prioritizes usability, allowing the reader to easily interpret the route and its surrounding environment.

## Route Markers and Point Features

Point features were added along the Via Francigena route to represent specific locations of interest.

Custom symbols were used to visually identify these points, each associated with calculated values and descriptive attributes.  
These markers provide localized information about real positions along the route, supporting both spatial orientation and contextual understanding.

## Print Layout and Output Design

The project includes a print-ready cartographic layout designed within QGIS.

The layout integrates:
- thematic maps
- legends and scale references
- attribute tables summarizing key data
- visual hierarchy optimized for printed output

This phase focused on transforming the analytical work into a clear and communicative cartographic product.

[detail](./detail.png)
---

## Tools

- QGIS

---

## Project Scope

This project was developed for academic purposes and focuses on cartographic representation and spatial analysis rather than navigation or real-time routing.

