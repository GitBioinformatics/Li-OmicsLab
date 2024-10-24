---
title: MRanalysis
description: MRanalysis - A Comprehensive Online Platform for Integrated, Multi-Method Mendelian Randomization and Associated Post-GWAS Analyses
categories: newblog
header-img: images/post/MRanalysis/GRAPHICAL_ABSTRACT.png
---
*by [Abao Xing]({{site.baseurl}}/people/abao_xing).*

# Introduction

Mendelian randomization (MR) has emerged as a powerful epidemiological method for inferring causal relationships between exposures and outcomes using genome-wide association study (GWAS) summary data. By leveraging instrumental variables (IVs), such as single nucleotide polymorphisms (SNPs), MR can revolutionize our understanding of disease etiology, inform public health strategies, and accelerate drug discovery. However, the widespread adoption of MR is hindered by several challenges, including inconsistent GWAS data formats, lack of standardized workflows, the need for extensive programming expertise, and limitations in data visualization and interpretability. To address these challenges, we introduce MRanalysis, a comprehensive and user-friendly, web-based platform that provides the first integrated and standardized MR analysis workflow. This includes GWAS data quality assessment, power/ sample size estimation, MR analysis, SNP-to-gene enrichment analysis, and data visualization. Built using the R shiny framework, MRanalysis enables users to conduct common MR methods, including univariable, multivariable, and mediation MR analyses through an intuitive, no-code interface. Besides MRanalysis, we developed GWASkit, a standalone, and installation-free tool facilitating rapid GWAS dataset preprocessing before MR analyses, including rs ID conversion, format standardization, and data extraction, with significantly lower conversion time and dramatically higher rs ID conversion accuracy than the current tools. Case studies demonstrate the utility, efficiency, and ease of use of our developed platform and GWASkit tool in real-world scenarios. By lowering barriers to investigating causal genetic relationships, our platform represents a significant advance in making MR more accessible, reliable, and efficient. The increased adoption of MR, facilitated by MRanalysis and GWASkit, can accelerate discoveries in genetic epidemiology, strengthen evidence-based public health strategies, and guide the development of targeted clinical interventions. MRanalysis is freely available at https://mranalysis.cn, and GWASkit can be accessed at https://github.com/Li-OmicsLab-MPU/GWASkit. Together, these tools are poised to democratize MR analyses and improve understanding of the complex relationships between genes, exposures, and health outcomes.

## Graphical Abstract

<img src="../../../images/post/MRanalysis/GRAPHICAL_ABSTRACT.png"/>

# Gallery

<div class="image-container">    
    <a href="https://mranalysis.cn/gallery/forest/" target="_blank">
        <img src="../../../images/post/MRanalysis/forest.png"/>
    </a>
    <a href="https://mranalysis.cn/gallery/forest-mvmr/" target="_blank">
        <img src="../../../images/post/MRanalysis/forest-mvmr.png"/>
    </a>
    <a href="https://mranalysis.cn/gallery/dag-mmr/" target="_blank">
        <img src="../../../images/post/MRanalysis/dag-plot.png"/>
    </a>
    <a href="https://mranalysis.cn/gallery/go-bar-plot/" target="_blank">
        <img src="../../../images/post/MRanalysis/go-bar-plot.png"/>
    </a>
    <a href="https://mranalysis.cn/gallery/go-bar-plot2/" target="_blank">
        <img src="../../../images/post/MRanalysis/go-bar-plot2.png"/>
    </a>
    <a href="https://mranalysis.cn/gallery/go-circos-plot/" target="_blank">
        <img src="../../../images/post/MRanalysis/go-circos-plot.png"/>
    </a>
    <a href="https://mranalysis.cn/gallery/go-dot-plot/" target="_blank">
        <img src="../../../images/post/MRanalysis/go-dot-plot.png"/>
    </a>
    <a href="https://mranalysis.cn/gallery/kegg-bar-plot-hierarchy/" target="_blank">
        <img src="../../../images/post/MRanalysis/kegg-bar-plot-hierarchy.png"/>
    </a>
    <a href="https://mranalysis.cn/gallery/manhattan/" target="_blank">
        <img src="../../../images/post/MRanalysis/manhattan.png"/>
    </a>
    <a href="https://mranalysis.cn/gallery/pie-chart/" target="_blank">
        <img src="../../../images/post/MRanalysis/pie-chart.png"/>
    </a>
    <a href="https://mranalysis.cn/gallery/qq/" target="_blank">
        <img src="../../../images/post/MRanalysis/qq.png"/>
    </a>
    <a href="https://mranalysis.cn/gallery/venn-diagram/" target="_blank">
        <img src="../../../images/post/MRanalysis/venn-diagram.png"/>
    </a>
    <a href="https://mranalysis.cn/" target="_blank" title="To see more, please visit DataVis Builder">
        <img src="../../../images/post/MRanalysis/mr_logo.png"/>
    </a>
</div>
















