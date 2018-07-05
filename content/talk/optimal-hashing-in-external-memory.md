+++
title = "Optimal Hashing in External Memory"
date = 2018-07-04T21:56:58-07:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2018-07-12T13:30:00+02:00
time_end = 2018-07-12T13:55:00+02:00

# Abstract and optional shortened version.
abstract = "Hash tables are a ubiquitous class of dictionary data structures. However, standard hash table implementations do not translate well into the external memory model, because they do not incorporate locality for insertions. Iacono and Patracsu established an update/query tradeoff curve for external hash tables: a hash table that performs insertions in $O(\\lambda/B)$ amortized IOs requires $\\Omega (\\log_\\lambda N)$ expected IOs for queries, where $ N $ is the number of items that can be stored in the data structure, $B$ is the size of a memory transfer, $M$ is the size of memory, and $\\lambda$ is a tuning parameter."
abstract_short = ""

# Name of event and optional event URL.
event = "2018 International Colloquium on Automata, Languages and Programming"
event_url = "ICALP"

# Location of event.
location = "Prague, CZ"

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
