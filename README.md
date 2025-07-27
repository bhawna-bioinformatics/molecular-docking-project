# 🧪 Molecular Docking Mini-Project

## 🎯 Project Overview
“This beginner-friendly project simulates the early stages of the drug discovery pipeline using open-source Python tools. It focuses on analyzing natural compounds and visualizing their interaction potential with the SARS-CoV-2 Main Protease (PDB ID: 6LU7) through molecular descriptors and simulated docking scores.”

### 🔬 Goals:
- Visualize a protein structure in 3D (6LU7)
- Load natural compounds and calculate molecular descriptors
- Simulate docking scores and visualize them
- Practice structural bioinformatics workflows using Python

---

## 🛠️ Tools & Libraries Used
- **RDKit** – for molecular descriptor calculations
- **NGLView** – for 3D protein visualization
- **Biopython** – for working with biological files
- **Matplotlib & Pandas** – for data visualization and manipulation
- **Jupyter Notebook** – as an interactive coding environment

---

## 📁 Project Structure
```bash
molecular-docking-project/
│
├── Molecular_Docking_Mini_Project.ipynb     # Main Jupyter Notebook
├── 6LU7.pdb                                 # Downloaded protein structure
├── docking_scores.csv                       # Mock docking score data
├── README.md                                # This file

Install all required packages using:

```bash
pip install rdkit-pypi nglview biopython pandas matplotlib

## Enable 3D protein visualization in Jupyter:
jupyter-nbextension enable nglview --py --sys-prefix

🎓 Key Takeaways
Learned how to use cheminformatics libraries (RDKit)

Practiced molecular descriptor calculation and analysis

Understood basics of protein-ligand docking workflows


!!! Acknowledgments
Protein structure retrieved from RCSB PDB.
Inspired by open-source cheminformatics tutorials and COVID-19 drug discovery challenges.


