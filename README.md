Overview: The following toy models describe different applications of statistical thermodynamics and reaction kinetics to model properties of gene regulatory networks prior to developing an original predictive model of bidirectional chromatin remodeling and its effects on transcription.

## Toy Model 1: TF Binding
  - Uses statistical thermodynamics to model a system containing one promoter region (for RNAP) and identical TF binding sites (either unbound or bound by TF),

  Model computes the following measures of TF occupancy:
-   average TF binding probability
-   probability that at least one TF binds
-   probability that the maximum possible number of TFs bind

  Model reports expected TF occupancy under dynamic TF concentrations, variable binding sites, as well as with and without cooperativity.

  #### Toy Model 1.5: RNAP binding
  - Model reports expected RNAP binding probability under the above conditions.

## Toy Model 2: Nucleosome Destabilization
- Uses free energy parameters determined by Doughty, B.R., et al. (2024) to model a system containing TF and nucleosome binding sites.
- Model reports TF occupancy & RNAP binding under dynamic TF concentrations, variable TF binding sites, and variable nucleosome binding sites.
  
## Toy Model 3: Mass Action Kinetics and Detailed Balance
  - Uses linear framework established in Estrada, J., Wong, et al. (2016) to model a four-state system with TF and nucleosome binding sites.
  - Model computes the steady state probabilities of each state when detailed balance is satisfied.
