Phenotype Data Analysis
=======================

Phenotype Data Analysis


```proc genmod data = Phenotype_datanw;
  class diet;
  model DAPI_Stem_cells = diet / type3 dist=poisson;
  lsmeans diet /diff=all;
 /* repeated subject= Animal_ID; */
run;```

jhkhjkhjkhj

hjhjkhjkh

`proc genmod data = Phenotype_datanw;
  class diet;
  model DAPI_Stem_cells = diet / type3 dist=poisson;
  lsmeans diet /diff=all;
 /* repeated subject= Animal_ID; */
run;`