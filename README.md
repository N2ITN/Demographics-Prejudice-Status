# Exploring the Demographics of Social Status and Prejudice

This notebook explores survey data on attitudes towards various social groups from a recent research paper (more below).

## Exploratory Data Analysis

### Questions and Hypotheses
Reading this paper sparked my curiousity on patterns might be found within these groups, as seen through their perception in the eyes of the participants. Were there cluster to be found, and more qualitatively, could the data be visualized in a way that would convey the landscape of prejudice more fluently than a table by increasing mental bandwidth and paralellism?
### Approach
The journey towards resolving these questions utilizes various tools and techniques including data cleaning, normalization, subquerying, multidimensional plotting with 3d visualization, dimensionality reduction techniques (t-SNE, PCA, LDA), and more. 

Python libraries used include pandas, SQL, seaborn, and sklearn, and plotly. 

Hopefully this exploration serves to stimulate learning and insight for other data creatives as it has for me.

The code and visualizations are both user editable and executable accessible in any browser by this clicking this button: [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/n2itn/demographics-prejudice-status)



## Summary of the paper
The data source for this analysis is the 2016 study "Answering Unresolved Questions About the Relationship Between Cognitive Ability and Prejudice"
(http://spp.sagepub.com/content/early/2016/07/27/1948550616660592.abstract).
In order to examine patterns of prejudice relating to verbal test scores, the researchers collected survey-based rankings of participant attitudes towards certain social groups. Each participant's negative prejudices were compared to the target group's level of choice in membership, and to the participant's verbal score (intended a proxy for cognitive abiltiy). 

The study found that regardless of cognitive ability, all participants harbored prejudices towards other social groups. However, higher scoring individuals were more prejucided towards groups with higher degree of choice in membership, while low-scorers were biased against those with relatively low choice in membership. 


## Data used
The analysis featured in this Jupyter notebook uses only the survey data collected on attitudes towards target demographics, and does not use any of the verbal test score data.
