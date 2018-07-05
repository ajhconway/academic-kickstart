+++
title = "BetrFS"
date = 2015-02-01
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = "The $B^\\varepsilon$-tree File System, or BetrFS, is an in-kernel file system that uses $B^\\varepsilon$ trees to organize on-disk storage. $B^\\varepsilon$  trees are a write-optimized dictionary, and offer the same asymptotic behavior for sequential I/O and point queries as a $B$-tree. The advantage of a $B^\\varepsilon$ tree is that it can also ingest small, random writes 1-2 orders of magnitude faster than $B$-trees and other standard on-disk data structures. <br/> The goal of BetrFS is to realize performance that strictly dominates the performance of current, general-purpose file systems."

# Optional image to display on homepage.
image_preview = ""

# Optional external URL for project (replaces project detail page).
external_link = "http://www.betrfs.org/"

# Does the project detail page use math formatting?
math = true

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
