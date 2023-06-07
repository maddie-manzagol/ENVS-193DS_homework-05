# ENVS-193DS_homework-05
Repo for homework 5 on pitcher plants

General Information: 

The data folder (data.hw5) contains an unzipped folder (knb-lter-hfr.109.18 (1)) which contains multiple files containing text and data analyzing how prey availability effects the pitcher plant species Sarracenia. The file containing the2005 Harvard Forest data and observations used in our project is "hf109-01-sarracenia.csv". For our analysis, we only concerned ourselves with the columns: totmass, species, feedlevel, sla, chlorophyll, amass, num_lvs, and num_phylls. The observations were collected from ten different species of sarracenia in 2005.

Data and File Overview: 

This README file outlines the files within the ENVS-193DS_homework-05 folder (a subset folder within the main github folder). Within the the ENVS-193DS_homework-05 folder there is a code folder, a data folder, this README.md, a gitignore file, and an Rhistory file. The code folder contains the quarto markdown document which contains all the code and short answers to this homework. The data folder (also subset of ENVS-193DS_homework-05) houses the folder (knb-lter-hfr.109.18 (1)) containing data and text from the 2005 Harvard Forest experiment. The only file used in our code is "hf109-01-sarracenia.csv" which is used to test the hypothesis.

Sharing and Accessing Information: 

To access the the data used for the project as well as ancillary data, use the website https://portal.edirepository.org/nis/mapbrowse?packageid=knb-lter-hfr.109.18. To acess the github of this project follow this link https://github.com/maddie-manzagol/ENVS-193DS_homework-05.git 

Methodological Information: 

Two plants of each Sarracenia species were allocated to one of six feeding levels in a regression design ranging from 0-0.25g of finely ground wasps per feeding (for small sized species), 0-0.5g (for medium sized species), and 0-1g (for large sized species). Plants were fed once a week for 7 weeks. "Aboveground size" and "Amass" (mass-based light-saturated photosynthetic rate of youngest leaf)  were measured prior to commencing treatments, meanwhile all other parameters were measured during the duration of the study (meta data). In total, 120 Sarracenia plants ranging from small, intermediate, and large species size were used for the study were collected from the sampling site: Harvard Forest Greenhouse (meta data).

Data-specific Information: 

The subset of data used in our analysis included a species-level identification ("species" column) along with seven other observations including totmass (g), feedlevel(g), sla (cm^2/g), chlorophyll (mg/g), amass (nmol/g/sec), num_lvs (integer unit), and num_phylls (integer unit). Additionally, there is some missing data in the chlorophyll, amass, sla, num_phylls, and num_lvs columns. 