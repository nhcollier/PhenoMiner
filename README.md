PhenoMiner
==========


Title:		README file for PhenoMiner data release
Version:	1.0 
Author: 	Nigel Collier
Contact: 	Department of Theoretical and Applied Linguistics - University of Cambridge
		Email: nhc30@cam.ac.uk
		and
		European Molecular Biology Laboratory - European Bioinformatics Institute
		(EMBL-EBI), Hinxton, Cambridge. 
		Email: collier@ebi.ac.uk
Date created: 	24th July 2014
Date modified: 	21st July 2015

This repo contains the following data files mined using the PhenoMiner system:

* S1:	XML formatted data file containing text mined phenotypes from the open access
	BMC corpus (July 2014 release), with links to 12 external ontologies and 
	citation data from PMC E-utils. The phenotype mentions have been filtered so that
	each occurs in a minimum of 10 PMC citations (i.e. df >= 10).
* S2:	Association rules mined using Apriori with min_support = 0.0000025,
	min_confidence=0.1, p-value < 0.005 (from Fisher's Exact Test).
* S3: 	S1 file with S2 association rules embedded and filtered to remove those phenotype
	entries that don't participate in S2 association rules. Additional HPO mappings 
	were done by Tudor Groza using Bio-LarK. DTD was also added.
* S4:   A list of abbreviations used in describing the PhenoMiner database and techniques.
* S5:	User documentation for the Web search and REST interface.
* S6:	S3 file hand edited to remove 373 erroneous terms and re-indexed in the form "PMI:nnnnnn".

