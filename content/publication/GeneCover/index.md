---
title: "GeneCover: A Combinatorial Approach for Label-free Marker Gene Selection"
authors:
- admin
date: "2025-02-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The selection of marker gene panels is critical for capturing the cellular and spatial heterogeneity in the expanding atlases of single-cell RNA sequencing (scRNA-seq) and spatial transcriptomics data. Most current approaches to marker gene selection operate in a label-based framework, which is inherently limited by its dependency on predefined cell type labels or clustering results. In contrast, existing label-free methods often struggle to identify genes that characterize rare cell types or subtle spatial patterns, and they frequently fail to scale efficiently with large datasets. Here, we introduce geneCover, a label-free combinatorial method that selects an optimal panel of minimally redundant marker genes based on gene-gene correlations. Our method demonstrates excellent scalability to large datasets and identifies marker gene panels that capture distinct correlation structures across the transcriptome.  This allows geneCover to distinguish cell states in various tissues of living organisms effectively, including those associated with rare or otherwise difficult-to-identify cell types. We evaluate the performance of geneCover across various scRNA-seq and spatial transcriptomics datasets, comparing it to other label-free algorithms to highlight its utility and potential in diverse biological contexts.

# Summary. An optional shortened abstract.
summary: Minimally redundant Marker Gene Selection Based on Gene-gene Correlations

tags:
- Marker Gene Selection
- Single-Cell RNA-seq
- Spatial Transcriptomics 

featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://doi.org/10.1101/2024.10.30.621151
url_code: https://github.com/ANWANGJHU/GeneCover
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false
  placement: 3

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
