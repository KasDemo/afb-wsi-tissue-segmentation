# AFB Tissue Segmentation — Supplementary Data

Supplementary materials for the article:

> **Comparative Analysis of Tissue Segmentation on AFB Whole Slide Images: Classic Computer Vision vs. Machine Learning and Pre-trained Deep Learning**
> Kasidet Saisudsawat, Puritad Pummiwattanarungrot, Fern Chanduayvit, Sutasinee Chimlek, Wansuree Massagram
> *Songklanakarin Journal of Science and Technology* (under review, 2026).

This repository hosts the full supplementary results that exceed the manuscript's length limit.

## Contents

- **`Supplementary_Materials.docx`** — single document containing:
  - **Table S1** — complete ranking of all 49 evaluated methods under the `before` protocol (raw output).
  - **Table S2** — complete ranking of all 49 methods under the `postproc` protocol (after the geometric heuristic; deployment-realistic).
  - **Table S3** — ±20% threshold sensitivity sweep of the three Fixed anchors (Hue = 80, Saturation = 25, Value = 254).
  - Method naming convention and column definitions.

All metrics are computed over N = 26 AFB-stained whole-slide images. The proposed pipeline, **H_Fixed_Morph**, attains a postproc Dice of 0.783 ± 0.154 and Recall of 0.942 ± 0.048 at 0.107 s/slide on CPU.

## Citation

Please cite the article above. (DOI to be added on publication.)

## Contact

Corresponding author: Wansuree Massagram — wansureem@nu.ac.th

## License

Data released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
