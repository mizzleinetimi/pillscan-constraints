# PillScan – Constraint Diary
## Day 2 (2025‑07‑22)
- Augmented 610 originals → 1 830 images (imgaug pipeline)
- Created dataset_full (2 440 images)
- Split 70 / 20 / 10 into train / val / test
- Uploaded dataset_splits.zip + manifest CSVs

## Day 3 (2025‑07‑22)
- Trained MobileNet V3‑Small on 12 classes → **84 %** val accuracy  
- Quantised to **INT‑8** (3–4 MB) and benchmarked: **24 ms** avg inference  
- Committed models under `/models`, benchmark under `/docs/bench.txt`  
- Missing classes (PARACETAMOL, AMOXYCILLIN, AMPICLOX) slated for Day 5 data‑boost
