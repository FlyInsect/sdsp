========file descriptions========

Disease Manifestation Network (DMN) was constructed from the disease-manifestation pairs
from the UMLS semantic network (2013AA version). The disease nodes are represented by 
UMLS concept unique identifiers (CUIs) and the edges are weighted by the cosine similairites
between diseases based on the manifestation features. The disease gene prediction 
approach based on integrated DMN, mimMiner and the PPI network based on HPRD) can achieve
significantly better performance than the approaches based on mimMiner only.  

Related publication:
Chen, Yang, et al. "Comparative analysis of a novel disease phenotype network based 
on clinical manifestations." Journal of biomedical informatics (2014).

 
DMN_2013AA.network	--weighted edges in DMN; nodes in UMLS cUIs
dname.txt		--disease names and synonyms for the nodes in DMN
DMN_snapshot.png	--the Gephi snapshot of the entire network of DMN
module_class.csv	--the label of module (network cluster) for each node
module1.png		--the snapshot of an example module
module2.png		--the snapshot of an example module
subnetwork.png		--the snapshot of a local neighborhood
Crohn_gene_prediction.txt	--gene prediction for Crohn's disease (DMN+mimMiner)
Crohn_drug_prediction.txt	--drug prediction for Crohn's disease based on the gene
							prediction result(DMN+mimMiner)