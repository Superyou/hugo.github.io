---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "REBNN: in-situ acceleration of binarized neural networks in ReRAM using complementary resistive cell"
authors:
  - Linghao Song
  - admin
  - Xuehai Qian
  - Hai Li 
  - Yiran Chen 

date: 2019-10-23T15:03:23-07:00
doi: "https://doi.org/10.1007/s42514-019-00014-8"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-08-26T15:03:23-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*CCF Transactions on High Performance Computing 1, pages196–208 (2019)*"
publication_short: "CCF Trans HPC"

abstract: "Resistive random access memory (ReRAM) has been proven capable to efficiently perform in-situ matrix-vector computations in convolutional neural network (CNN) processing. The computations are often conducted on multi-level cell (MLC) that have limited precision and hence, show significant vulnerability to noises. The binarized neural network (BNN) is a hardware-friendly model that can dramatically reduce the computation and storage overheads. However, XNOR, which is the key operation in BNNs, cannot be directly computed in-situ in ReRAM because of its nonlinear behavior. To enable real in-situ processing of BNNs in ReRAM, we modified the BNN algorithm to enable direct computation of XNOR, POPCOUNT and POOL based on ReRAM cells. We also proposed the complementary resistive cell (CRC) design to efficiently conduct XNOR operations and optimized the pipeline design with decoupled buffer and computation stages. Our results show our scheme, namely, ReBNN, improves the system performance by 25.36 × and the energy efficiency by 4.26 × compared to conventional ReRAM based accelerator, and ensures a throughput higher than state-of-the-art BNN accelerators. The correctness of the modified algorithm is also validated"

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://link.springer.com/content/pdf/10.1007/s42514-019-00014-8.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
