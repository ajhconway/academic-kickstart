+++
title = "File Systems Fated For Senescence? Nonsense, Says Science!"
date = 2017-02-28  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2017-02-28T14:00:00-07:00
time_end = 2017-02-28T14:25:00-07:00

# Abstract and optional shortened version.
abstract = "File systems must allocate space for files without knowing what will be added or removed in the future.  Over the life of a file system, this may cause suboptimal file placement decisions which eventually lead to slower performance, or aging. Traditional file systems employ heuristics, such as collocating related files and data blocks, to avoid aging, and many file system implementors treat aging as a solved problem. <br/>However, this paper describes realistic as well as synthetic workloads that can cause these heuristics to fail, inducing large performance declines due to aging. For example, on ext4 and ZFS, a few hundred git pull operations can reduce read performance by a factor of 2; performing a thousand pulls can reduce performance by up to a factor of 30. We further present microbenchmarks demonstrating that common placement strategies are extremely sensitive to file-creation order; varying the creation order of a few thousand small files in a real-world directory structure can slow down reads by 15 − 175×, depending on the file system. <br/>We argue that these slowdowns are caused by poor layout.  We demonstrate a correlation between read performance of a directory scan and the locality within a file system’s access patterns, using a dynamic layout score. <br/>In short, many file systems are exquisitely prone to read aging for a variety of write workloads. We show, however, that aging is not inevitable. BetrFS, a file system based on write-optimized dictionaries, exhibits almost no aging in our experiments. BetrFS typically outperforms the other file systems in our benchmarks; aged BetrFS even outperforms the unaged versions of these file systems, excepting Btrfs. We present a framework for understanding and predicting aging, and identify the key features of BetrFS that avoid aging."
abstract_short = ""

# Name of event and optional event URL.
event = "The 15th USENIX Conference on File and Storage Technologies"
event_url = "FASTa"

# Location of event.
location = "Santa Clara, CA"

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["betrfs"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_slides = "https://www.usenix.org/sites/default/files/conference/protected-files/fast17_slides_conway.pdf"
url_video = "https://www.usenix.org/conference/fast17/technical-sessions/presentation/conway"
url_code = ""

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
