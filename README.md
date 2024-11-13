# Odin Landing Page

Final project of the CSS lessons of The Odin Project Foundations course.

## Goal

Starting from scratch, mimicking the proposed solution using mainly flexbox:

![Proposed solution](https://cdn.statically.io/gh/TheOdinProject/curriculum/81a5d553f4073e593d23a6ab00d50eef8620796d/foundations/html_css/project/imgs/01.png)

## Problems and solutions

### Problem
Each section of the website has a background color that covers the full screen.

However, the width of the sections don't extend to the entire width.

### Solution
Make the `body` flex.

Wrap each `.section` in a `.section-container` that specifies the background color.
Set `max-width` of each `.section` to `1024px`.