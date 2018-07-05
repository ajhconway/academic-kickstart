+++
# About/Biography widget.
widget = "about"
active = true
date = 2016-04-20T00:00:00

# Order that this section will appear in.
weight = 5

# List your academic interests.
[interests]
  interests = [
    "Write-Optimized Data Structures",
    "File Systems",
    "External Memory Theory"
  ]

# List your qualifications (such as academic degrees).
[[education.courses]]
  course = "PhD Candidate in Computer Science"
  institution = "Rutgers University"
  
[[education.courses]]
  course = "MS in Mathematics"
  institution = "Princeton University"
  year = 2011

[[education.courses]]
  course = "BS in Mathematics"
  institution = "Rutgers University"
  year = 2007
 
+++

# Biography

Alex Conway is a PhD student in computer science at Rutgers University, where
he is advised by Martin Farach-Colton. His research interests are in the
theory, application and implementation of external memory data structures and
algorithms. He has worked externsively with write-optimized data structures
such as $B^\varepsilon$-trees, COLAs, LSMs and BOA/BOT hash tables, from both
theortical and systems perspectives.

He is a member of the BetrFS team, which built and maintains the BetrFS
prototype file system. BetrFS is designed around the principle of
write-optimization, and is built using variants of $B^\varepsilon$-trees.
