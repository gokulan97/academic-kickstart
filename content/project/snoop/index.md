---
title: Snoop-based cache coherence protocol for Shakti C-Class processor
summary: 
tags:
- Demo
date: "2018-07-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
# external_link: http://example.org

image:
  caption: Photo by Toa Heftiba on Unsplash
  focal_point: Smart
---
Shakti C-Class processor is a 6-stage in-order core. I implemented snoop-based MOESI cache coherence protocol for multi-core C-Class processor. The protocol was implemented using `Tilelink` interconnect standard and the entire implementation was done in `Bluespec HDL`.