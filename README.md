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
