# CCT1–mHTT Colocalization Analysis

This repository accompanies the master's thesis *"Colocalization patterns of mutant Huntingtin and the CCT1 chaperone"*, conducted at the Amsterdam University of Applied Sciences in collaboration with the Prinses Máxima Centrum.

The goal of this project is to quantify spatial colocalization between mutant Huntingtin (mHTT) aggregates and the CCT1 chaperone using 3D fluorescence microscopy data. The pipeline combines both traditional image analysis techniques and deep learning models (e.g., nnU-Net) to segment structures of interest and compute overlap metrics such as Pearson’s coefficient, Manders’ M1/M2, and Dice similarity coefficient.

---

## 🧠 Project Structure

### 🔬 Core Notebook

- **`nnUnet.ipynb`**  
  Implements nnU-Net for segmenting aggregates and CCT1 regions in 3D. Trained models and predictions enable spatial colocalization analysis at high resolution.

- **`logboek.md`**  
  Weekly development and research log documenting the iterative process, meetings, and decisions.

- **`Zelfevaluatieformulier leeruitkomsten_blok4 (1).pdf`**  
  Self-assessment form for evaluating learning outcomes in the context of the graduation project.
---
## 📁 Older code
- **`CPCAM.ipynb`**  
  Visualizes and quantifies CCT1 enrichment at mHTT aggregate locations using intensity-based statistics.

- **`Hybrid_Colocalization_SpotitPy.ipynb`**  
  Combines SpotitPy’s object-based segmentation with traditional colocalization metrics for hybrid analysis.

- **`Microscopy_analysis_new.ipynb`**  
  Main exploratory notebook for preprocessing, visualization, and manual inspection of multi-channel z-stack microscopy data.

- **`aggregate detection.ipynb`**  
  Applies classical image processing techniques (thresholding, morphology) to detect mHTT aggregates from fluorescence channels.
## 📊 Methodology Overview

The analysis pipeline is structured as follows:

1. **Image Loading**: Supports multi-channel .tiff and .lif files with z-stacks.
2. **Segmentation**: Cellpose (for cells), nnU-Net (for mHTT and CCT1), and threshold-based alternatives.
3. **Colocalization Analysis**: Pearson’s, Manders’ M1/M2, and Dice coefficient, optionally visualized.
4. **Output**: Visual overlays, 3D renderings, and tabular summary files per image.

---

## 🔧 Requirements

- Python 3.9+
- Jupyter
- Libraries: `numpy`, `scikit-image`, `matplotlib`, `opencv-python`, `cellpose`, `nnunet`, `napari`, `pandas`

Environment files or setup instructions will be added in future commits. Ensure CUDA support if running nnU-Net on GPU.

---

## 📍 Citation

If you use or adapt this pipeline, please cite:

> Wijnheijmer, N. (2025). *Colocalization patterns of mutant Huntingtin and the CCT1 chaperone* [Master’s thesis, Amsterdam University of Applied Sciences].

---

## 📬 Contact

For questions or collaborations, contact:  
📧 noah.wijnheijmer@hva.nl

---
