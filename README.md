# Organized Criminal Violence Event Data (OCVED) 2.0

<br>

This repository presents the database as well as the technical elements and methodological procedures used to develop Organized Criminal Violence Event Data (OCVED) 2.0 in Osorio and Beltran (2020). At its core, this research project integrates innovations in Machine Learning (ML) protocols and Natural Language Processing (NLP) tools in Spanish to generate a geo-referenced database at the daily municipal level on the violent presence of Organized Criminal Groups between 2000-2018. 

To generate this database, the methodological strategy takes advantage of a large collection of articles from local and national newspapers and press releases from a variety of government agencies. To ensure the validity of the input corpora used in this study, the methodological approach relies on Machine Learning algorithms to classify relevant news stories. After selecting the relevant corpora, the research protocol uses Evetus ID (Osorio and Reyes 2017), a rule-based event coding software designed to identify event data from text written in Spanish. In this particular application, Eventus ID is used exclusively to extract the names of organized criminal groups in Mexico and to pinpoint their location as referenced in the original text.

The resulting  database presents geo-referenced data at unprecedented levels of granularity by comprising daily-municipal information about 10 main criminal organizations that can be further disaggregated into more than  200 criminal cells. The application also includes an interactive web interface presenting dynamic heat-maps of criminal territories.  This information is the empirical foundation to identify distinct temporal and spatial trends in the development and contestation dynamics between criminal organizations during this time period.


<br>

## Repository structure

The repository contains the following files:

* **OCVED_2.0.xlsx** Is the Excel file containing the OCVED 2.0 database
* **OCVED_methodology_2.0.pdf** Is the methodological note with the detailed procedures conducted to produce OCVED.
* **actors_and_locations.xlsx** Is the codebook containing the list of Organized Criminal Groups included in COVED, as well as state and municipality codes.



<br>

## Website and interactive maps 

Users are invited to take a look at the OCVED website [https://www.ocved.mx/] where they can find a web interactive map applicaiton to analyze the spatial and temporal trends of Organized Criminal Groups in Mexico.


<br>

## ML replication 

For advanced users interested in getting the details of the Machine Learning algorithms used in this reserch, please consult Alejandro Beltran's GitHub repository: 
[https://github.com/AlejandroBeltranA/OCVED-ML]

<br>

## How to cite

Please use the following citation:

Osorio, Javier, and Beltrán, Aejandro. (2020). "Enhancing the Detection of Criminal Organizations in Mexico Using ML and NLP", *2020 International Joint Conference on Neural Networks (IJCNN)*, Galsgow, UK, July, pp. 1-7, doi:10.1109/IJCNN48605.2020.9207039, [https://ieeexplore.ieee.org/document/9207039]

BibTeX:

````{verbatim}
@article{Osorio2020,
author = {Osorio, Javier, and Beltrán, Aejandro},
title = {Enhancing the Detection of Criminal Organizations in Mexico Using ML and NL},
url = {https://ieeexplore.ieee.org/document/9207039},
Journal = {2020 International Joint Conference on Neural Networks,  IJCNN 2020},
pages = {1--7},
year = {2019},
month = {July},
doi = {10.1109/IJCNN48605.2020.9207039},
place = {Glasgow, UK}
}
````

<br>

## Contact

For comments and suggestions, please contact:

Dr. Javier Osorio, School of Government and Public Policy, University of Arizona.

Email: josorio1 at arizona dot edu

<br>

Thank you!


<br>

<br>

<br>
