---
title: 'treeArches for learning cell-type hierarchies '
subtitle: 'treeArches automatically identifies novel disease states'
authors:
- admin
tags:
- publication
categories:
- news
date: "2022-07-10"
lastmod: "2022-07-10"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 1
  caption: 
  focal_point: "Center"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

I am excited to share our new work, we tackled: 1)
how to learn a harmonized cell-type hierarchy/taxonomy across many studies 
with different annotations, 2) how to automatically identify novel cell states (e.g. disease)
when mapping new query data.  We use transfer learning and hierarchical classifiers to build and update the hierarchies when new datasets are added. If a population is identified to match reference populations, it will be added to the same level o.w either
as a subpopulation or a new state. 

- See twitter thread here: https://twitter.com/Mohlotf/status/1545328933247373312

- Link to the paper: https://www.biorxiv.org/content/10.1101/2022.07.07.499109v1

- Link to the code and tutorials: https://scarches.readthedocs.io/en/latest/treeArches_pbmc.html

- See advance guide how to use human lung cel atlas to identify disease states: https://scarches.readthedocs.io/en/latest/treeArches_identifying_new_ct.html 
