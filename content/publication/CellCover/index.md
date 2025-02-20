---
title: 'CellCover Captures Neural Stem Cell Progression in Mammalian Neocortical Development'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Lanlan Ji
  - Shreyash Sonthalia
  - Daniel Naiman
  - Laurent Younes
  - Carlo Colantuoni
  - Donald Geman

#Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Johns Hopkins University'
  - 'Johns Hopkins University'
  - 'Johns Hopkins University'
  - 'Johns Hopkins University'
  - 'Johns Hopkins University'

date: '2024-08-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']
publication_types: ['article']
# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Definition of cell classes across the tissues of living organisms is central in the analysis of growing atlases of single-cell RNA sequencing (scRNA-seq) data across biomedicine. Marker genes for cell classes are most often defined by differential expression (DE) methods that serially assess individual genes across landscapes of diverse cells. This serial approach has been extremely useful, but is limited because it ignores possible redundancy or complementarity across genes that can only be captured by analyzing multiple genes simultaneously. We aim to identify discriminating *panels* of genes. To efficiently explore the vast space of possible marker panels, leverage the large number of cells often sequenced, and overcome zero-inflation in scRNA-seq data, we propose viewing gene panel selection as a variation of the minimal set-covering problem in combinatorial optimization. We show that this new method, CellCover, performs as good or better than DE and other methods in defining cell-type discriminating gene panels, but captures cell class-specific signals that are distinct from those defined by DE methods. Transfer learning experiments across mouse, primate, and human data demonstrate that CellCover identifies markers of conserved cell classes in neurogenesis, as well as developmental progression in both progenitors and neurons. Exploring markers of human outer radial glia (oRG, or basal RG) across mammals, we show that transcriptomic elements of this key cell type in the expansion of the human cortex appeared in gliogenic precursors of the rodent before the full program emerged in neurogenic cells of the primate lineage. We have assembled the public datasets we use in this report within the NeMO analytics multi-omic data exploration environment, where the expression of individual genes (**[NeMO Individual Genes](https://nemoanalytics.org/p?&l=CellCover&g=HOPX)**) and marker gene panels can be freely explored at **[NeMO: Telley 3 Sets Covering Panels](https://nemoanalytics.org/p?p=p&l=CellCover&c=TelleyCellCover3sets&algo=binary)**, **[NeMO: Telley 12 Sets Covering Panels](https://nemoanalytics.org/p?p=p&l=CellCover&c=TelleyCellCover12sets&algo=binary)**, and **[NeMO: Sorted Brain Cell Covering Panels](https://nemoanalytics.org/p?p=p&l=CellCover&c=LiuCellCoverSorted&algo=binary)**."

#   CellCover is available in [CellCover R](https://github.com/lanlanji/CoveringPackage) and [CellCover Python](https://pypi.org/project/CellCover/).

# Summary. An optional shortened abstract.
summary: 

tags:
  - Label-Based Marker Gene Selection
  - Neurogeneis

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1101/2023.04.06.535943'
url_code: 'https://github.com/lanlanji/CoveringPackage'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
# url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false
  placement: 3

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
