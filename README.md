## Taxon classification on protein or nucleotide database

In clinical metagenomics, microbial profiling and pathogen identification are both important fields of use. In both areas, the taxon classification of the next generation sequencing short reads can be performed using numerous tools and databases. Some alignment tools used before the reads’ assignment to their taxa are nucleotide-based, while others are protein-sequence-based. Analysing animal gut microbiomes, we found that various types of databases can produce different results. 

After protein-based classification, much more short reads get classified as bacterial hits. Examining this excess, it seemed that the difference can come from false-positive (FP) assignments. Investigating the reasons, we found that the presence of eukaryotic genomes increased the number of results classified FPs in the different NGS samples.
 
We generated artificial datasets simulating short reads from various eukaryotic genomes managing their exonic, intronic and intergenic regions separately. Classifying these reads on protein and nucleotide databases, we found a typical means of misclassification. Nucleotide based assignment of the eukaryotic reads had lower rates of FPs for each region compared to the protein-based assignments, where we had a higher proportion of FP microbial hits. The excess of FPs was considerably higher in reads from the intronic or intergenic parts of the genome compared to the exonic regions. 
 
Although in metagenome analyses the host genome is filtered out before taxon classification, other eukaryotic genome components (e.g. feed) might remain among the short reads. Our findings suggest that in samples with eukaryotic contamination, the nucleotide-based taxon classification decreases the FP microbial hits.

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/solymosin/nuc_or_prot/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
