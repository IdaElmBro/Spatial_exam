# Mapping power - A gerrymandering perspective on the 2007 Structural Reform


## Project Description 
The aim of the project is to map the political outcome of the 2007 structural reform to investigate potential gerrymandering in the restructuring of the new municipalities. 
As the reform was implemented by a single political coalition (the blue bloc), i'm investigating potential partisan bias in deciding what municipalities to merge. 
The hypothesis is that blue bloc: 
- ***1)*** optimizes number of mayoral posts, 
and 
- ***2)*** optimizes number of citizens ruled over.


## Outcome when running Spatial.Rmd: 
The analysis: 
- Map of the local political structure pre- (2006) and post reform (2007) in terms of mayoral posts for the red and the blue bloc. 
- Table of the mayoral distribution between blocs pre- (2006) and post reform (2007). 
- Bar plot of the top 30 biggest municipalities based on population in 2007 and their mayoral color. 
- Cartogram of the distribution based on population size post reform. 

To guide further discussion, a quick analysis of the spatial autocorrelation is performed. 
This produces: 
- Maps of the k = 2 nearest neighbors pre- (2006) and post reform (2007). 
- Statistics from a Monte-Carlo simulation of Moran I pre- (2006) and post reform (2007). 


## Repository  

- `Spatial.Rmd`: main markdown containing the entire analysis
- `data`: folder with the data used in the analysis
- `out`: folder containing the outcome of the analysis (all plots are saved as pdf)
- `LICENSE`: License file containing the description of the MIT license.

### How to reproduce the analysis: 

First step for analysis reproduction is to clone the repository and navigate to the folder: 
```yaml
git clone https://github.com/IdaElmBro/Spatial_exam.git 
```

The analysis for the project is all contained within one markdown file: `Spatial.Rmd` (also provided as a html).
In order to reproduce the analysis, all chunks can be run at once or one by one in the RStudio environment. The markdown both installs and loads all the required dependencies, so no setup is necessary. 



