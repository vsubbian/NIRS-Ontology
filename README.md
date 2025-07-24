# NIRS-Ontology: An Ontology for Non-Invasive Respiratory Support in Acute Care 

This repository contains the **NIRS Ontology**, developed to support knowledge representation in acute care settings. It integrates ventilation modalities, therapy parameters, patient characteristics, and clinical outcomes using standardized vocabularies and rule-based reasoning.

---

## 📁 Repository Structure

| Folder/File | Description |
|-------------|-------------|
| `NIRS-Ontology.owl` | The main OWL ontology file including classes, properties, annotations, and SWRL rules. |
| `README.md` | Project description and usage guide. |

---

## 📦 Getting Started

To explore or extend the ontology:

1. **Open in Protégé**  
   Download [Protégé](https://protege.stanford.edu/) and load `NIRS-Ontology.owl`.

2. **Visualize Class Tree**  
   Open `visualization/nirs_tree.html` in a web browser for an interactive view.

---

## 🧪 Results Reproducibility

All SPARQL queries included demonstrate use cases for reasoning, therapy recommendation, and risk identification.  
To reproduce:

1. Clone this repository.  
2. Load the ontology in a semantic reasoning environment (e.g., Protégé + SPARQL plugin, Jena, or Stardog).  
3. Run SPARQL files under `/examples/queries`.

---

## 🧬 Data Source

The ontology was evaluated using data and clinical scenarios derived from the **eICU Collaborative Research Database**.  
Access: [https://physionet.org/content/eicu-crd/](https://physionet.org/content/eicu-crd/) (credentialed access required).

---

## 📬 Contact

For questions, collaboration, or ontology extension:

**Md Fantacher Islam**  
PhD Student, Systems and Industrial Engineering  
University of Arizona  
📧 fantacher@arizona.edu

---

## 📝 Citation

If you use this ontology, please cite:

> Islam MF, et al. _“Standardizing Non-Invasive Respiratory Support Data with the NIRS Ontology.”_ (Under review, 2025)

