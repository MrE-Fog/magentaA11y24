---
layout: page
title: Design criteria
permalink: /design/
---

## Any deliverable should be able to fulfill these acceptance criteria

Given that I have delivered a design component
- When I examine any component therein
- Then I see
  - The type size is no smaller than 16px.
  - Any interactive target areas are no smaller than 48x48 
  - The focus indication has a minimum area equal to the width of the element and 4px in height.
  - The hover state has a 3:1 or greater contrast ratio between the default and hover states.
  - The focus state has a 3:1 or greater contrast ratio between the default and focused states.
  - The focus indication has a 3:1 or greater contrast ratio against adjacent elements.
  - Color is not used as the sole means of conveying meaning

Given that I have delivered a UI design
- When I open the accessibility annotation layer
- Then, at a minimum I see
  - HTML <title> is defined
  - Logical headings are outlined
  - Links and buttons are assigned name and role
  - Name, role state and group name is defined in the accessibility annotation layer for custom components
  - Alternative text for images is written
  - Ambiguously named components have defined aria-labels