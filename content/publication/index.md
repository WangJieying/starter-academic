---
title: "Spline-Based Dense Medial Descriptors for Lossy Image Compression"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jiří Kosinka
- Alexandru Telea

# Author notes (optional)

date: "2021-08-16T00:00:00Z"
doi: "https://doi.org/10.3390/jimaging7080153"

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Journal of Imaging*

abstract: Medial descriptors are of significant interest for image simplification, representation,
manipulation, and compression. On the other hand, B-splines are well-known tools for specifying
smooth curves in computer graphics and geometric design. In this paper, we integrate the two by
modeling medial descriptors with stable and accurate B-splines for image compression. Representing
medial descriptors with B-splines can not only greatly improve compression but is also an effective
vector representation of raster images. A comprehensive evaluation shows that our Spline-based
Dense Medial Descriptors (SDMD) method achieves much higher compression ratios at similar or
even better quality to the well-known JPEG technique. We illustrate our approach with applications
in generating super-resolution images and salient feature preserving image compression.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  placement: 2
  caption: 'Comparison of SDMD, JPEG 2000 and BPG'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

All experiments in this paper, including the original image datasets,
SDMD encoding results, and computed quality metrics, are openly available at https://github.com/WangJieying/SDMD-resources.

