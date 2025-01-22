# DGIdb Citation Analysis

This repository contains analyses designed to support a grant application for DGIdb, a leading drug-gene interaction database. The analyses explore citation trends and disease categorization across DGIdb and comparable resources (Pharos and OpenTargets). By examining these trends, we aim to highlight the impact and relevance of DGIdb in the scientific community.

## Repository Structure

- **`data/`**  
  This directory contains the data files used for analysis:
  - Citation CSV files for DGIdb, Pharos, and OpenTargets.
  - Abstract text files associated with the citations for these resources.

- **`citation-history.ipynb`**  
  A Jupyter Notebook that visualizes the citation history for DGIdb, Pharos, and OpenTargets as a grouped histogram. This analysis highlights the temporal trends of citations for each resource.

- **`disease-categorization.ipynb`**  
  A Jupyter Notebook that categorizes the publications citing DGIdb, Pharos, and OpenTargets into major disease areas based on keywords derived from MeSH. The results are visualized as a comparative grouped histogram of disease focus across these resources.

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
   ```

## Contributions

Contributions are welcome! Please submit issues or pull requests to suggest improvements or new analyses.

## License

This repository is open-sourced under the MIT License. See the [LICENSE](LICENSE) file for details.
