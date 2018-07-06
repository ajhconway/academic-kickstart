+++
title = "Optimal Ball Recycling"
date = 2018-07-06T05:41:47+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Michael A. Bender", "Jake Christensen", "Alex Conway", "Martin Farach-Colton", "Rob Johnson", "Meng-Tsung Tsai"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract and optional shortened version.
abstract = "Balls-and-bins games have been a wildly successful tool for modeling load balancing problems. In this paper, we study a new scenario, which we call the ball recycling game, defined as follows: Throw $m$ balls into $n$ bins i.i.d. according to a given probability distribution $\\mathbf{p}$. Then, at each time step, pick a non-empty bin and recycle its balls: take the balls from the selected bin and re-throw them according to $\\mathbf{p}$.  This balls-and-bins game closely models memory-access heuristics in databases. The goal is to have a bin-picking method that maximizes the recycling rate, defined to be the expected number of balls recycled per step in the stationary distribution.<br/>  We study two natural strategies for ball recycling: Fullest Bin, which greedily picks the bin with the maximum number of balls, and Random Ball, which picks a ball at random and recycles its bin. We show that for general $\\mathbf{p}$, Random Ball is $O(1)$-optimal, whereas Fullest Bin can be pessimal. However, when $\\mathbf{p} = \\mathbf{u}$, the uniform distribution, Fullest Bin is optimal to within an additive constant."
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
url_pdf = ""
url_preprint = "https://arxiv.org/pdf/1807.01804"
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
