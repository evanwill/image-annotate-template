---
title: About This Template
nav: About
nav_order: 2
---

[image-annotate-template](https://github.com/evanwill/image-annotate-template) is a simple website template for creating a presentation with annotated images.
It uses Jekyll static site generation, Bootstrap 5, and the Annotorious JS library.
This makes it easy to host on GitHub Pages or anywhere else.

## Workflow

- Set up your website:
    - Create a copy of the template.
    - Add images to the "objects" folder.
    - Activate GitHub Pages create live site.
- Annotate images:
    - Visit Annotate page.
    - Select image and create annotations.
    - Download annotation data as json.
    - Add annotation json file to project repository "objects" folder.
- Publish annotated images:
    - Create or edit a content page (see "docs/create-website.md" for details).
    - Use "annotated-image.html" include to add annotated image to a content page.
