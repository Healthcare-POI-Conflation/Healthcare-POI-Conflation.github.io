---
layout: default
---

![UCIPT_Logo](./img/UCIPT_Logo.jpg)

# Healthcare Point of Interest (POI) Conflation and Spatial Attribute Enrichment Framework

# Abstract

Healthcare Point of Interest (POI) data is an important source of semantic information about healthcare places, however, the task of retrieving accurate healthcare POI information is yet complicated. With the abundance of open-source projects and commercial geographical databases, POI conflation is a useful method to enrich spatial data attributes and coverage through merging POI records from different sources. This study is proposing a novel comprehensive healthcare POI conflation and spatial enrichment framework that engage in multi-step process; POI data collection from Location-Based Services (LBS), geographic and spatial attributes collection, calculating similarity across dataset and POI matching, spatial attributes enrichment, manual validation, Quality Control (QC), and finally a deployable enriched database. The viability of our proposed framework is tested on a case study of drug and substance abuse places in California. 


# Our approach

![pipeline](./img/pipeline.png)

### LBS POI Collection 

The first step is collecting POI data from different sources to be conflated. In this step, we are proposing the use of LBS, because it allows searching for POIs based on a text query. 

### Conflation Process

POIs from different sources sometimes follow different encoding systems, thus a thoughtful conflation policy is necessary to combine POIs databases. 