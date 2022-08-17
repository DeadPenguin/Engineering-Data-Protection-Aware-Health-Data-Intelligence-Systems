# Readme
This repository hosts the thesis paper "Engineering Data Protection-Aware Health Data Intelligence Systems by Design", which was submitted by Martin Hollmann to the Koblenz University Institute for Sotware Technology on August 18th 2022. It further contains the research artifacts generated in line with the thesis-project.

## 1. Thesis 
### 1.1 Paper
The thesis paper is provided as a PDF file and concerns the research conducted in order to generate the other artifacts contained in this repository.
### 1.2 Abstract
The project "KI und Covid" by the Institute for Software Engineering at Koblenz University plans the development of a so called Health Data Intelligence System (HDIS) which is supposed to provide authorities with comprehensive insight into the main and side effects of pandemic events and the actions taken to address them in order to optimize their crisis response measures. To this end, the system will use various kinds of data generated and provided by public and private sources. As the name suggests, this data will also include health data which often concerns individual persons and is considered private data under European and German data protection law.
        
To use this data legally, information systems in general and HDIS in particular have to conform with a large number of requirements. Data protection, however, is often treated as an afterthought during development, as identifying these requirements and finding ways to implement them into a system architecture by design can be a time consuming process that has to be conducted for the development of each individual system. With this thesis, we try to facilitate this process by creating a reference architecture that can serve as a reusable framework for ensuring basic compliance of any HDIS with data protection regulations and encourage the consideration of data protection at every stage of the system's development lifecycle.
        
For this, we compile a list of general data protection requirements and conduct a dedicated analysis of threats specific to HDIS. Lastly, we design a high-level reference architecture for such systems which takes data protection requirements and threat mitigation strategies into account. Our solution is a set of research artifacts that can be applied through a standardized process and aim to facilitate the inclusion of data protection into the development processes at the development stages of requirements engineering and architectural design.

## 2. Legal Requirements Repository
This document contains a list of general legal requirements to achieve basic compliance with the EU General Data Protection Legislation (GDPR) and the Bundesdatenschutzgesetz (BDSG) (en. German Federal Data Protection Legislation). Each requirement features an ID, a category, and a reference to its source article in the respective legislation. Separate worksheets contain links to both legislations and a glossary.

Further information about the contents of the repository and its creation can be found in Chapters 3 and 4 of the thesis paper.

## 3. Threat Repository
The first three pages of the Threat Repository feature three different sets of threats to HDIS (system weaknesses, attack strategies, AI-specific threats). Each entry contains an ID, a summary and a reference to potential mitigation strategies which in turn are listed in two separate worksheets for general and AI-specific mitigation strategies. Each threat and mitigation entry also features a reference to its source. 

Further information about the contents of the repository and its creation can be found in Chapter 5 of the thesis paper.

## 4. Data Protection Reference Architecture (DPRA)
The DPRA is made up of two research artifacts. Further information about the Technical Requirements Repository and the DPRA Diagrams can be found in Chapter 6 of the thesis paper.
### 4.1 Technical Requirements Repository
This document contains three sets of technical requirements for data stores, data flows and processing systems handling private data. The requirements are organized under multiple categories which originate from the Data Protection Goals used as keywords in the Legal Requirements Repository. The last worksheet contains a mapping of the components of the DPRA to the aforementioned categories to visualize which protection goals are addressed by which component.
### 4.2 DPRA Diagrams
This folder contains the diagrams used for visualizing the components of the Data Protection Reference Architecture and their internal structure. The diagrams have been created using the open source app [draw.io](https://www.draw.io/). We provide two source files (.drawio & .xml), which can be used to edit and export the diagrams to different image formats using the web app or downloadable version. 
We further provide the original version of all diagrams as PNG and SVG files in the respective sub-folders. 