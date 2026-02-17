# Bio-Chem-CV-Projects

A collection of computer vision applications in Chemistry, Biology, and Chemical Engineering.

## Current Project: 3D-Voxel-Net for Binding Affinity
This project uses **3D Convolutional Neural Networks (CNNs)** to predict the binding affinity ($pK_d$) of protein-ligand complexes. By representing molecular structures as 3D voxel grids, the model learns spatial features of chemical interactions.

### 🧪 Scientific Background
- **Data Source:** PDBbind (Refined Set)
- **Featurization:** Converting `.pdb` and `.sdf` files into occupancy grids.
- **Goal:** Automate virtual screening for drug discovery.

### 💻 Technical Stack
- **Framework:** PyTorch / DeepChem
- **Chemistry Toolkit:** RDKit
- **Architecture:** 3D CNN with MaxPool3D and BatchNorm.

---
## Repository Structure
- `/data`: Placeholder for molecular structure files.
- `/notebooks`: Exploratory Data Analysis and Model Training experiments.
- `/src`: Production-ready Python scripts.
