# Heat Stress Transcription Factor — Structural Analysis
### A comparative protein structure study in rice and wheat using AlphaFold and PyMOL

---

## About This Project

This is an independent bioinformatics project analysing the predicted 
3D structures of heat stress transcription factors in three cereal crops 
— rice (Oryza sativa) and wheat (Triticum aestivum), and maize (Zea mays).

Heat stress transcription factors are proteins that help plants survive 
high temperature conditions by switching on protective genes. 
Understanding their structure helps us understand how cereal crops 
respond to heat stress — which is critical for climate-resilient 
agriculture.

---

## Proteins Studied

| Protein | Organism | UniProt ID |
|---|---|---|
| Heat Stress Transcription Factor A-6a | Oryza sativa (Rice) | Q657C0 |
| Heat Shock Transcription Factor HsfA2-6 | Triticum aestivum (Wheat) | A0A7D5UPA7 |
| Heat Stress Transcription Factor A-6b | Zea mays (Maize) | A0A1D6L3W5 |

---

## Tools Used

- **UniProt** (uniprot.org) — protein identification
- **AlphaFold Database** (alphafold.ebi.ac.uk) — 3D structure prediction
- **PyMOL** — 3D structure visualisation

---

## Key Findings

- Both proteins belong to the same HSF (Heat Shock Factor) family
  confirming evolutionary relationship between rice and wheat
- Rice protein shows predominantly alpha helical structure with
  moderate disordered regions
- Wheat protein shows significantly more disordered regions suggesting
  greater structural flexibility
- Despite structural differences, both proteins share the same
  fundamental design — confirming conserved heat stress response
  across cereal crops
- Maize protein shows unique two-domain architecture with
  prominent beta sheets suggesting functional specialisation
  and greater thermostability

---

## Project Structure
```
HeatStress_AlphaFold_Project/
│
├── data/
│   ├── Q657C0.pdb            # Rice protein structure
│   └── A0A7D5UPA7.pdb        # Wheat protein structure
│   └── A0A1D6L3W5.pdb           # Maize protein structure
├── results/
│   ├── pymol_view.png        # Rice protein visualisation
│   ├── wheat_pymol_view.png  # Wheat protein visualisation
│   └── observations.txt      # Detailed observations and interpretation
│   ├── maize_pymol_view.png     # Maize protein visualisation
│   └── observations_report.md  # Detailed observations
└── README.md
```

---

## Author

**anumitadutta01-coder**
M.Sc. Biotechnology | University of Burdwan (2025)
Independent Bioinformatics Research Project — March 2026

---

## References

- Jumper, J., Evans, R., Pritzel, A. et al. Highly accurate protein structure prediction with AlphaFold. Nature 596, 583–589 (2021). https://doi.org/10.1038/s41586-021-03819-2.
- UniProt Consortium (2023) UniProt: the Universal Protein Database.
  Nucleic Acids Research.
- AlphaFold Protein Structure Database — alphafold.ebi.ac.uk
```

---

**Now save this as README.md** in your main project folder:
```
HeatStress_AlphaFold_Project/
└── README.md   ← here




