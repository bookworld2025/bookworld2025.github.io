---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 45

title: Tips
subtitle: -- for building a 'virtual world'

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

While some existing work has implemented "chatroom" systems with multi-role-playing agents, they still fall short of the envisioned "virtual world." Through the experimental process of this work, we have distilled the following insights to further advance toward a realistic virtual world:

1. Map: We present spatial relationships through a discretely represented map, supplemented with scene mode, which naturally creates narrative space.

2. Environmental Interaction: Character-to-character interaction alone easily creates a "chatroom-like" feeling. In realistic scenarios, many interactions involve the environment. We address this by implementing environmental responses.

3. Reinforcing Worldview with Setting Data: Furthermore, by extracting implicit worldview information from the source material (such as technological development progress in science fiction works, or magic systems in fantasy works) and equipping both role agents and world agents with retrieval modules, we enable their behaviors to remain synchronized with the original worldview.

4. Character Long-term and Short-term Goal Setting: Without clear purposes, characters easily fall into repetitive behavior and lack autonomy. To address this issue, our characters maintain both long-term motivations and short-term goals—the former being lifelong objectives such as defending the nation, while the latter are short-term goals formulated by characters to achieve their long-term motivations, such as reaching reconciliation with another character, which are frequently updated as the story progresses.

5. Controlling the Narrative Chain: When implementing designated plots, the world agent guides each character's behavior at the beginning of each turn, specifically by modifying their short-term goals in conjunction with the designated plot.