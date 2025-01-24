# DGIdb Citation Analysis

This repository contains analyses designed to summarize impact of DGIdb and compare to other mainstream drug-gene interaction aggregator knowledgebases. The analyses explore citation trends and disease categorization across DGIdb, Pharos, and OpenTargets. By examining these trends, we aim to highlight the impact and relevance of DGIdb in the scientific community.

## Papers considered

The analysis in this repository evaluates works that cite the following papers:

### Drug-Gene Interaction Database (DGIdb)
- [**DGIdb 5.0: rebuilding the drug–gene interaction database for precision medicine and drug discovery platforms**](https://doi.org/10.1093/nar/gkad1040), *Nucleic Acids Research*, 2024.  
- [**Integration of the Drug–Gene Interaction Database (DGIdb 4.0) with open crowdsource efforts**](https://doi.org/10.1093/nar/gkaa1084), *Nucleic Acids Research*, 2021.  
- [**DGIdb 3.0: a redesign and expansion of the drug–gene interaction database**](https://doi.org/10.1093/nar/gkx1143), *Nucleic Acids Research*, 2018.  
- [**DGIdb 2.0: mining clinically relevant drug–gene interactions**](https://doi.org/10.1093/nar/gkv1165), *Nucleic Acids Research*, 2016.  
- [**DGIdb: mining the druggable genome**](https://doi.org/10.1038/nmeth.2689), *Nature Methods*, 2013.  

### Pharos Resource
- [**Pharos 2023: an integrated resource for the understudied human proteome**](https://doi.org/10.1093/nar/gkac1033), *Nucleic Acids Research*, 2023.  
- [**TCRD and Pharos 2021: mining the human proteome for disease biology**](https://doi.org/10.1093/nar/gkaa993), *Nucleic Acids Research*, 2021.  
- [**How to Illuminate the Druggable Genome Using Pharos**](https://doi.org/10.1002/cpbi.92), *Current Protocols in Bioinformatics*, 2020.  
- [**Pharos: Collating Protein Information to Shed Light on the Druggable Genome**](https://doi.org/10.1093/nar/gkw1072), *Nucleic Acids Research*, 2017.  

### Open Targets Platform
- [**The next-generation Open Targets Platform: reimagined, redesigned, rebuilt**](https://doi.org/10.1093/nar/gkac1046), *Nucleic Acids Research*, 2023.  
- [**Open Targets Platform: supporting systematic drug–target identification and prioritisation**](https://doi.org/10.1093/nar/gkaa1027), *Nucleic Acids Research*, 2021.  
- [**Open Targets Platform: new developments and updates two years on**](https://doi.org/10.1093/nar/gky1133), *Nucleic Acids Research*, 2019.  
- [**Open Targets: a platform for therapeutic target identification and validation**](https://doi.org/10.1093/nar/gkw1055), *Nucleic Acids Research*, 2017.  


## Repository Structure

- **`data/`**
  This directory contains the data files used for analysis:
  - Citation CSV files for DGIdb, Pharos, and OpenTargets.
  - Abstract text files associated with the citations for these resources.

- **`citation-history.ipynb`**
  A Jupyter Notebook that visualizes the citation history for DGIdb, Pharos, and OpenTargets as a grouped histogram. This analysis highlights the temporal trends of citations for each resource.

- **`disease-categorization.ipynb`**
  A Jupyter Notebook that categorizes the publications citing DGIdb, Pharos, and OpenTargets into major disease areas based on keywords derived from MeSH. The results are visualized as a comparative grouped histogram of disease focus across these resources.


- **`semantic-scholar-citations.ipynb`**
  A Jupyter Notebook that extracts richer annotations ("influential", "methodology", "background") on citations for papers of interest. The output is given in `./data/semantic_scholar_citation_metadata.json` and can be used to generate visuals for these annotations in the aggregate or by-year.

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/dgidb-citation-analysis.git
   cd dgidb-citation-analysis
   ```

2. **Install required Python packages**:
   The analyses use standard Python libraries such as `pandas`, `matplotlib`, and `numpy`. Install them using:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebooks**:
   Open the Jupyter Notebooks to explore the citation history and disease categorization:
   ```bash
   jupyter notebook citation-history.ipynb
   jupyter notebook disease-categorization.ipynb
   jupyter notebook semantic-scholar-citations.ipynb
   ```

## Contributions

Contributions are welcome! Please submit issues or pull requests to suggest improvements or new analyses.

## License

This repository is open-sourced under the MIT License. See the [LICENSE](LICENSE) file for details.
