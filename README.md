# RPPA-Workflow
This workflow is for the analysis of data collected from reverse-phase protein array (RPPA) experiments, with control and experiment groups. The Jupyter Notebook script (available for use locally or through Google Colaboratory) takes the RPPA data in the form of a CSV file and calculates the statistical significance of each endpoint (protein). The results of the analysis are then made available in the Jupyter Notebook output cells and in the form of a network visualization in Cytoscape (an open-source network visualization software).

See RPPA Network Analysis Workflow SOP for detailed usage instructions.

## (Requirements) For Google Colaboratory and Local use:
  Cytoscape 3.10.1 or later, installed on user’s computer.
## (Requirements) For Local use:
  Jupyter notebook v2023.4.1011241018 or later
  
  Python 3.10.9 or later
  
  Python packages:
  - py4cytoscape
  - pandas
  - NumPy
  - SciPy

## References
- Coarfa, C., Grimm, S. L., Rajapakshe, K., Perera, D., Lu, H. Y., Wang, X., Christensen, K. R., Mo, Q., Edwards, D. P., & Huang, S. (2021). Reverse-Phase Protein Array: Technology, Application, Data Processing, and Integration. Journal of biomolecular techniques : JBT, 32(1), 15–29. https://doi.org/10.7171/jbt.21-3202-001
- Harris, C.R., Millman, K.J., van der Walt, S.J. et al. Array programming with NumPy. Nature 585, 357–362 (2020). DOI: 10.1038/s41586-020-2649-2.
- Kluyver, T., Ragan-Kelley, B., Pérez, F., Granger, B., Bussonnier, M., Frederic, J., Kelley, K., Hamrick, J., Grout, J., Corlay, S., Ivanov, P., Avila, D., Abdalla, S., Willing, C., & team, J. development. (2016). Jupyter Notebooks—A publishing format for reproducible computational workflows. In F. Loizides & B. Scmidt (Eds.), Positioning and Power in Academic Publishing: Players, Agents and Agendas (pp. 87–90). IOS Press. https://eprints.soton.ac.uk/403913/ 
- McKinney, W. (2010). Data Structures for Statistical Computing in Python. In S. van der Walt & J. Millman (Eds.), Proceedings of the 9th Python in Science Conference (pp. 56–61). https://doi.org/10.25080/Majora-92bf1922-00a 
- Otasek, D., Morris, J. H., Bouças, J., Pico, A. R., & Demchak, B. (2019). Cytoscape Automation: empowering workflow-based network analysis. Genome biology, 20(1), 185. https://doi.org/10.1186/s13059-019-1758-4 
- Shannon, P., Markiel, A., Ozier, O., Baliga, N. S., Wang, J. T., Ramage, D., Amin, N., Schwikowski, B., & Ideker, T. (2003). Cytoscape: a software environment for integrated models of biomolecular interaction networks. Genome research, 13(11), 2498–2504. https://doi.org/10.1101/gr.1239303 
- Szklarczyk, D., Kirsch, R., Koutrouli, M., Nastou, K., Mehryary, F., Hachilif, R., Gable, A. L., Fang, T., Doncheva, N. T., Pyysalo, S., Bork, P., Jensen, L. J., & von Mering, C. (2023). The STRING database in 2023: protein-protein association networks and functional enrichment analyses for any sequenced genome of interest. Nucleic acids research, 51(D1), D638–D646. https://doi.org/10.1093/nar/gkac1000 
- Van Rossum, G., & Drake, F. L. (2009). Python 3 Reference Manual. Scotts Valley, CA: CreateSpace.
- Virtanen, P., Gommers, R., Oliphant, T. E., Haberland, M., Reddy, T., Cournapeau, D., Burovski, E., Peterson, P., Weckesser, W., Bright, J., van der Walt, S. J., Brett, M., Wilson, J., Millman, K. J., Mayorov, N., Nelson, A. R. J., Jones, E., Kern, R., Larson, E., … SciPy 1.0 Contributors. (2020). SciPy 1.0: Fundamental Algorithms for Scientific Computing in Python. Nature Methods, 17, 261–272. https://doi.org/10.1038/s41592-019-0686-2 
