---
title: "Quantitative Evaluation of Dense Skeletons for Image Compression"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Maarten Terpstra
- Jiří Kosinka
- Alexandru Telea

# Author notes (optional)

date: "2020-05-15T00:00:00Z"
doi: "https://doi.org/10.3390/info11050274"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *information*

abstract: Skeletons are well-known descriptors used for analysis and processing of 2D binary images. Recently, dense skeletons have been proposed as an extension of classical skeletons as a dual encoding for 2D grayscale and color images. Yet, their encoding power, measured by the quality and size of the encoded image, and how these metrics depend on selected encoding parameters, has not been formally evaluated. In this paper, we fill this gap with two main contributions. First, we improve the encoding power of dense skeletons by effective layer selection heuristics, a refined skeleton pixel-chain encoding, and a postprocessing compression scheme. Secondly, we propose a benchmark to assess the encoding power of dense skeletons for a wide set of natural and synthetic color and grayscale images. We use this benchmark to derive optimal parameters for dense skeletons. Our method, called Compressing Dense Medial Descriptors (CDMD), achieves higher-compression ratios at similar quality to the well-known JPEG technique and, thereby, shows that skeletons can be an interesting option for lossy image encoding.


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
  caption: 'Average MS-SSIM vs. CR for 10 image types'
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

The [source code](https://www.dropbox.com/home/CDMD-code) of DMD image compression can be accessed by: https://www.dropbox.com/home/CDMD-code.


