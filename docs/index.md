
# AgriField3D: A Curated 3D Point Cloud Dataset of Field-Grown Plants from a Maize Diversity Panel

[Elvis Kimara*](https://www.linkedin.com/in/elvis-kimara/), [Mozhgan Hadadi*](https://www.linkedin.com/in/mozhgan-hadadi/), [Jackson Godbersen](https://www.linkedin.com/in/), [Aditya Balu](https://scholar.google.com/citations?user=GNuXi6oAAAAJ&hl=en), [Zaki Jubery](https://scholar.google.com/citations?user=P3h1SM0AAAAJ&hl=en), [Adarsh Krishnamurthy](https://scholar.google.com/citations?user=iVTMSxoAAAAJ&hl=en&oi=ao), [Patrick Schnable](https://scholar.google.com/citations?user=UW4mNTW0nOkC&hl=en), [Baskar Ganapathysubramanian](https://www.me.iastate.edu/bglab/)

**Institution**: Iowa State University  
**Equal Contribution**: Elvis Kimara*, Mozhgan Hadadi*


[Paper (arXiv)](https://arxiv.org/pdf/),[GitHub](https://github.com/baskargroup/AgriField3D),[Dataset Card](https://huggingface.co/datasets/BGLab/AgriField3D), [Model Card](https://huggingface.co/BGLab/AgriField3D),[arXiv Abstract](https://arxiv.org/abs/)

 

![AgriField3D](images/Poster2.png "Raw Data and Curated Sample in the AgriField3D Dataset")*Figure 1: Raw Data and Curated Sample in the AgriField3D Dataset.*

## Abstract

The application of artificial intelligence (AI) in three-dimensional (3D) agricultural research, particularly for maize, has been limited by the scarcity of large-scale, diverse datasets. While 2D image datasets are abundant, they cannot capture essential structural details such as leaf architecture, plant volume, and spatial arrangements that 3D data can provide. To address this limitation, we present a curated dataset of 3D point clouds of fully field-grown maize plants with diverse genetic backgrounds designed to be AI-ready for advancing agricultural research. Our dataset comprises over 1,000 high-quality point clouds representing diverse maize varieties collected using a Terrestrial Laser Scanner. To enhance the usability of the dataset, we performed graph-based segmentation to isolate individual leaves and stalk point clouds. Each leaf is assigned a consistent color label across all plants based on its order from bottom to top. Similarly, all stalks are assigned a single, distinct color. A rigorous quality control process was undertaken to manually correct any errors in the segmentation and leaf ordering, ensuring accurate segmentation and consistent color labeling. The dataset includes metadata describing point cloud quality, the number of leaves, and the presence of tassels and maize cobs. This dataset lays the foundation for leveraging 3D data to enable advanced applications in agricultural research, particularly for maize phenotyping and plant structure studies.

---

## Dataset Features

### Nine Sample Images

- Showing the architectural diversity of the maize plants in the dataset.

![Sample Image](images/Nine_Samples.png)

### Procedural Model Samples

- Top row: Workflow of the procedural model generation.
- Bottom row: Generated sample of the procedural models.

![Procedural Models](images/Procedural_Models_Samples.png)

### Comparison with Existing Datasets

- Comparison of AgriField3D dataset with existing datasets.

![Comparison](images/comparison_argifield3d.png)

---

## Acknowledgements

This work was supported by the AI Research Institutes program supported by the **NSF** and **USDA-NIFA** under [AI Institute: for Resilient Agriculture (AIIRA)](https://aiira.iastate.edu/), Award No.2021-67021-35329.

---

## Team

<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
    <div style="width: 30%; text-align: center;">
        <h3 style="font-weight: normal; font-size: 14px; margin: 0;"><a href="https://www.linkedin.com/in/elvis-kimara/">Elvis Kimara</a></h3>
        <img src="images/elvis.jpg" width="150" height="150">
    </div>
    <div style="width: 30%; text-align: center;">
        <h3 style="font-weight: normal; font-size: 14px; margin: 0;"><a href="https://www.linkedin.com/in/mozhgan-hadadi/">Mozhgan Hadadi</a></h3>
        <img src="images/mozhgan.jpeg" width="150" height="150">
    </div>
    <div style="width: 30%; text-align: center;">
        <h3 style="font-weight: normal; font-size: 14px; margin: 0;"><a href="https://www.linkedin.com/in/">Jackson Godbersen</a></h3>
        <img src="images/dummy.png" width="150" height="150">
    </div>
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
    <div style="width: 30%; text-align: center;">
        <h3 style="font-weight: normal; font-size: 14px; margin: 0;"><a href="https://scholar.google.com/citations?user=GNuXi6oAAAAJ&hl=en">Aditya Balu</a></h3>
        <img src="images/balu.d4938a4efb8fe4623b1a.jpeg" width="150" height="150">
    </div>
    <div style="width: 30%; text-align: center;">
        <h3 style="font-weight: normal; font-size: 14px; margin: 0;"><a href="https://scholar.google.com/citations?user=P3h1SM0AAAAJ&hl=en">Zaki Jubery</a></h3>
        <img src="images/Zaki.png" width="150" height="150">
    </div>
    <div style="width: 30%; text-align: center;">
        <h3 style="font-weight: normal; font-size: 14px; margin: 0;"><a href="https://scholar.google.com/citations?user=iVTMSxoAAAAJ&hl=en&oi=ao">Adarsh Krishnamurthy</a></h3>
        <img src="images/adarsh.202221a57a53702b8066.jpeg" width="150" height="150">
    </div>
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
    <div style="width: 50%; text-align: center;">
        <h3 style="font-weight: normal; font-size: 14px; margin: 0;"><a href="https://scholar.google.com/citations?user=UW4mNTW0nOkC&hl=en">Patrick Schnable</a></h3>
        <img src="images/schnable.jpg" width="150" height="150">
    </div>
    <div style="width: 50%; text-align: center;">
        <h3 style="font-weight: normal; font-size: 14px; margin: 0;"><a href="https://www.me.iastate.edu/bglab/">Baskar Ganapathysubramanian</a></h3>
        <img src="images/baskar.052e915b05c921cb3ffa.png" width="150" height="150">
    </div>
</div>





---

## BibTeX Citation

@inproceedings{kimara2025agriField3D,
title={AgriField3D: A Curated 3D Point Cloud Dataset of Field-Grown Plants from a Maize Diversity Panel2},
          author={Elvis Kimara1†, Mozhgan Hadadi3, Jackson Godbersen, Aditya Balu, Zaki Jubery, Adarsh Krishnamurthy, Patrick Schnable, Baskar Ganapathysubramanian},
          booktitle={Arxiv},
          year={2025},
          primaryClass={cs.CV},
          url={}

---
