---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: About BookWorld
subtitle:

design:
  columns: "1"
  background:
    image: 
    image_darken: 1.0
    image_parallax: true
    image_position: center
    image_size: cover
    text_color_light: 
  spacing:
    padding: ["20px", "0", "20px", "0"]
---



## Introduction: The first system for constructing fiction-based multi-agent societies

Recent advances in LLMs have enabled social simulation through multi-agent systems. Prior efforts focus on agent societies created from scratch, assigning agents with newly defined personas. However, simulating established fictional worlds and characters remain largely underexplored, despite its significant practical value. In our paper titled "[BookWorld: From Novels to Interactive Agent Societies for Creative Story Generation](https://arxiv.org/abs/2504.14538)", we introduce BookWorld, a comprehensive system for constructing and simulating book-based multi-agent societies.

<center class="half">
  <img src="/uploads/Preview.png" width="100%"/>
</center>

## The Overview of BookWorld
BookWorld provides a complete pipeline from data collection to social simulation, and finally, rephrasing into novelistic text.

<center class="half">
  <img src="/uploads/Pipeline_altered.png" width="100%"/>
</center>

### Data Extraction
 Before the simulation starts, we extract character and worldview data from source materials, used for book-to-system construction.
### Simulation
The simulation begins by initializing role agents and the world agent, loading character profiles, the geospatial  map, the worldview data and other necessary information.

### Rephrasing
After the simulation ends, we collect the simulation records and apply LLMs to rephrase the records into the final, novel-style story.



