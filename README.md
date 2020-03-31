# PCR-pooling
Estimating the efficacy of PCR pooling in boosting detection of Covid-19 infectious.

Interactive Dashboard implements algorithm from (Hanel and Thurner, 2020, preprint) (https://arxiv.org/pdf/2003.09944.pdf).

## Probem statement:
- Extensive population screening to find Covid-19 carriers is an asset against the epidemic.   
- Testing capacity is currently a bottleneck.  
- Pooling samples for PCR has been suggested to boost testing capacity.  
- Is there an optimal sample size to minimise the tests necessary to identify a person as positive? What does it depend on?

## Proposed solution:
- (Hanel and Thurner, 2020, preprint) have suggested a statistical method to gauge the optimal sample size and to quantify the number of missed infectious. 
- We implement an interactive dashboard to tune the method to different regional cohorts.  

### Variables:
- Single test false positives rate. 
- Single test false negatives rate. 
- Infected fraction of the population. In principle, this should also consider a rough estimation of not-yet-found carriers. As a rule of thumb, this number may be 5 to 10 times bigger than official reports. 

### Outputs:
- Best sample size per test. 
- Gain (persons per test). 
- Estimated numbeer of missed infectious, per test.  

Default values are for Luxembourg. 


Author: Daniele Proverbio; Date: 31/03/2020; Affiliation: LCSB, University of Luxembourg
