
I analyzed the published data of the COVID-19 outbreak in the Italian town of Vo’, near Venice, one of the hotspots of the epidemic.

Constructed contact networks of COVID positive patients and of their social vicinities, using R code (https://www.r-project.org/).\ 
Then, I have displayed the graphs using the network visualization software Gephi (https://gephi.org).\
Wrote a presentation with graph slides.\
\
Standard descriptive statistics, as used in clinical medicine, often assumes a homogeneous “melting pot” of datapoints, corresponding to a well-mixed system of chemistry. On the other hand, Graph visualizations of patients networks and their contacts create an immediate an intuitive sense of the structure the disease exists in. This kind of insight could prove valuable to epidemiologists, clinicians and the patients themselves.

Directories of the repository:\
\data – contains tabular R dataframe, derived from the original dataset\
\src – the R code used to extract the patients graph from the data\
\graph – the extracted graph in two formats, .GRAPHML and .GEPHI. The .GEPHI file stores node colors and sizes, if opened in Gephi. GRAPHML is more portable.\
\images – the graph images used in the presentation\

I used the data provided at:\
https://github.com/ncov-ic/SEIR_Covid_Vo\
by the authors of the study: \
 “Suppression of a SARS-CoV-2 Outbreak in the Italian Municipality of Vo’.” Nature, June 2020. Imperial College COVID-19 Response Team, Enrico Lavezzo, Elisa Franchin, Constanze Ciavarella, Gina Cuomo-Dannenburg, Luisa Barzon, Claudia Del Vecchio, et al.  \
https://doi.org/10.1038/s41586-020-2488-1.\
\
Their dataset is unique in many respects. While the town was in lockdown (February and March 2020), most (80%) of the population  (3200 inhabitants in total) was tested for Sars-CoV2 infection, at two distinct times. Of the tested inhabitants, 3% were COVID positive (cca80 patients in total). For each positive individual, an extensive dataset was made available: gender, age class (within a 10 years resolution), hosehold ID, symptoms, matrix of contacts (direct, indirect, household), severity, outcome, date of testing.
