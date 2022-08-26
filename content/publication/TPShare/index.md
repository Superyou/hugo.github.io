---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Tpshare: a time-space sharing scheduling abstraction for shared cloud via vertical labels'
authors:
  - Yuzhao Wang
  - Lele Li
  - admin
  - Junqing Yu
  - Zhibin Yu
  - Xuehai Qian


date: '2019-06-22T00:00:00Z'
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-08-26T14:49:46-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*2019 ACM/IEEE 46th Annual International Symposium on Computer Architecture (ISCA)*"
publication_short: "ISCA2019"

abstract: Current shared cloud operating systems (cloud OS) such as Mesos and YARN are based on the “de facto” two-horizontal-layer cloud platform architecture, which decouples cloud application frameworks (e.g., Apache Spark) from the underlying resource management infrastructure. Each layer normally has its own task or resource allocation scheduler, based on either time-sharing or space- sharing. As such, the schedulers in different layers are unavoidably disconnected, - not aware of each other, which highly likely leads to resource (e.g.,CPU) wastes. Moreover, the tail latency may even be harmed due to the performance interference on shared resources. This paper takes the first step to establish the critical missing connection between the horizontal layers. We propose TPShare, a time- space sharing scheduling abstraction, using a simple but efficient vertical label mechanism to coordinate the time- or space-sharing schedulers in different layers. The vertical labels are bidirectional (i.e., up and down) message carriers which convey necessary information across two layers and are kept as small as possible. The schedulers in different layers can thus take actions according to the label messages to reduce resource wastes and improve tail latency. Moreover, the labels can be defined to support different cloud application frameworks. We implement the label mechanism in Mesos and two popular cloud application frameworks (Apache Spark and Flink) to study the effectiveness of the time-space sharing scheduling abstraction. The label messages of TPShare reduce resource waste and performance interference due to independent time-sharing or space- sharing scheduling of different layers by enabling 1) on-demand fine-grained resource offering, 2) load-aware resource filtering, and 3) resource demand scaling with global view, eventually improving performance and tail latency. We co-locate 13 Spark batch and 4 Flink latency-sensitive programs on a 8-node cluster managed by TPShare to evaluate the speedup, CPU and memory utilization, and tail latency. The results show that TPShare accelerates the Spark programs significantly with even lower CPU and memory utilization compared to Mesos. With higher resource utilization, the throughput of TPShare is drastically larger than that of Mesos. For the Flink programs, TPShare improves the 99th tail latency by 48% on average and up to 120%.

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

url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8980319
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
