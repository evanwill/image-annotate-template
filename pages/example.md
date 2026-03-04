---
title: Example Page
nav: Example
nav_order: 1
foot: template/annotation-viewer.html
---

Write content in Markdown.
Add annotated images using the include!

## Annotated Example

`{% raw %}{% include annotated-image.html image="campus02023.jpg" annotation="campus02023-annotations.json" %}{% endraw %}`

{% include annotated-image.html image="campus02023.jpg" annotation="campus02023-annotations.json" %}