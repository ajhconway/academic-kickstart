+++
title = "Optimal Hashing in External Memory"
date = 2018-07-04T20:19:48-07:00
draft = false

# Authors. Comma separated list, e.g. `["Martin Farach-Colton", "Alex Conway", "Philip Shilane"]`.
authors = ["Martin Farach-Colton", "Alex Conway", "Philip Shilane"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "2018 International Colloquium on Automata, Languages and Programming"
publication_short = "ICALP"

# Abstract and optional shortened version.
abstract = "Hash tables are a ubiquitous class of dictionary data structures. However, standard hash table implementations do not translate well into the external memory model, because they do not incorporate locality for insertions. Iacono and Patracsu established an update/query tradeoff curve for external hash tables: a hash table that performs insertions in $O(\\lambda/B)$ amortized IOs requires $\\Omega (\\log_\\lambda N)$ expected IOs for queries, where $ N $ is the number of items that can be stored in the data structure, $B$ is the size of a memory transfer, $M$ is the size of memory, and $\\lambda$ is a tuning parameter."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true 

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "http://drops.dagstuhl.de/opus/volltexte/2018/9043/pdf/LIPIcs-ICALP-2018-39.pdf"
url_preprint = "https://arxiv.org/pdf/1805.09423.pdf"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
