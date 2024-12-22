---
layout: page
title: Quantifying Nondeterminism in SOM models
description: SOM (self-organizing maps) project in collaboration with Professor Iulian Neamtiu.
img: assets/img/som_cover.png 
importance: 1
category: work
related_publications: true
---

### Research Contributions

**Title:** Quantifying Nondeterminism and Inconsistency in Self-organizing Map Implementations  
**Published In:** AITEST Conference 2021  
**Collaborators:** Sydur Rahaman, Raina Samuel, Iulian Neamtiu  

#### Overview  
I contributed to groundbreaking research analyzing the reliability of Self-Organizing Maps (SOMs), a neural network-based technique for clustering and dimensionality reduction. Our work addressed critical gaps in understanding nondeterminism (variability in outcomes across repeated runs) and inconsistency (differences in results across implementations), particularly when applied to medical and other critical datasets.

#### Key Contributions  
- **Toolkit Analysis:** Assisted in benchmarking SOM implementations across four popular toolkits (MiniSom, RKoh, MATLAB, and TensorFlow SOM) using 381 datasets, including health and bioinformatics data.  
- **Statistical Validation:** Helped design statistical tests to identify and quantify nondeterminism and inconsistency using internal and external metrics such as clustering accuracy, trustworthiness, and distortion.  
- **Critical Insights:** Found significant variability in SOM reliability, highlighting the importance of multiple toolkit evaluations for high-stakes applications.  
- **Technical Support:** Supported the development and debugging of TensorFlow SOM implementations to ensure robust comparisons.  

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/som_pic.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/som_pic2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    These figures highlight key challenges in Self-Organizing Map (SOM) reliability, focusing on nondeterminism in quantization error (Figure 4) and topographic product (Figure 5). Figure 4 demonstrates variability in quantization error across runs of the ecoli3 dataset using the RKoh toolkit, where error levels range from low (dark blue) to high (red), underscoring the inconsistency in clustering quality. Figure 5 showcases topographic product nondeterminism in the colic dataset, with the left map displaying a more uniform neuron distribution and better fit, while the right map reveals empty nodes and higher errors, emphasizing the sensitivity of SOM outcomes to repeated executions.
</div>

#### Impact  
This research exposed reliability challenges in SOM usage, prompting the need for rigorous testing and validation. It provides actionable insights for practitioners in fields like healthcare, where consistent and reliable machine learning outcomes are essential.  

### External Links 

- [Our Research Paper](https://doi.org/10.1109/AITEST2021) - Read the full publication *"Quantifying Nondeterminism and Inconsistency in Self-Organizing Map Implementations."*  
- [Making Artificial Intelligence More Reliable](https://news.njit.edu/computing-professor-makes-artificial-intelligence-more-reliable) - Read the article about the impact our research team has had on the AI community.

#### Acknowledgments  
The project was supported by the National Science Foundation under Grant No. CCF-2007730.
