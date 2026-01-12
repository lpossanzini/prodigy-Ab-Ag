# prodigy-Ab-Ag

Datasets (CSV) for antibody–antigen (Ab–Ag) complexes used to build and evaluate binding-affinity prediction models.

## Contents

All files are in `datasets/`:

- `uncurated.csv`  
  Initial collection of Ab–Ag complexes before the final filtering/cleanup steps.

- `curated_features.csv`  
  Final curated dataset **with computed features** used for training/evaluation.

- `peptide_features.csv`  
  Subset **with computed features** where the antigen is a **peptide** (peptide–antibody complexes).

- `FV_domain_features.csv`  
  Subset **with computed features** where the antibody corresponds to an **Fv-only / truncated variable domain**.
