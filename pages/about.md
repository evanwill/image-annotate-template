---
title: About This Template
nav: About
nav_order: 2
---

[image-annotate-template](https://github.com/evanwill/image-annotate-template) is a simple website template for creating a presentation with annotated images.
It uses [Jekyll](https://jekyllrb.com/) static site generation, [Bootstrap 5](https://getbootstrap.com/), and [Annotorious](https://annotorious.dev/).
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
    - Add `annotation-viewer: true` to the front matter.
    - Use the "annotated-image.html" include to add annotated images to the page. Check the comments in the include for all supported options.
- Unpublish the "Annotate" page:
    - If you are done annotating images and don't want the "Annotate" page published, 

## Guidelines

- Supported image types include JPG and PNG. Ensure your file extensions are lowercase, `.jpg`, `.jpeg`, or `.png` only.
- For ease of use, create meaningful filenames without spaces.
- You can set the default annotation styles (fill, opacity, stroke color, stroke width) in "_config.yml" or as front matter on each page.
- If you have issues with the "Annotate Image" page caching old versions of your annotations, open the page in a new browser window.
- Unpublish the "Annotate Image" page when you are done annotating images and don't want it to display publicly by removing the `nav:` option from the front matter (or just deleting "pages/annotate.html").
