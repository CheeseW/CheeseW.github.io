---
title: "Computer Based Simulation of Facial Flap and Cleft Lip Reconstruction Using Multiresolution Physics"
authors:
  - admin
  - Court Cutting
  - Eftychios Sifakiss


author_notes:
  - University of Wisconsin - Madison
  - New York University Medical Center
  - University of Wisconsin - Madison

date: "2025-03-07T00:00:00Z"
# doi: "10.1145/3450626.3459883"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: Accepted by *Plastic and Reconstructive Surgery*
publication_short: Accepted by *PRS*

# abstract: 
  
# Summary. An optional shortened abstract.
summary: Computer-based simulation of complex local flap reconstructions of the face requires very high density finite elements to render accurately due to the intricate incision designs frequently used.  This is particularly true in detailed cleft lip/nose repairs …

tags:
- Physical Simulation
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
 Computer-based simulation of complex local flap reconstructions of the face requires very high density finite elements to render accurately due to the intricate incision designs frequently used.  This is particularly true in detailed cleft lip/nose repairs.  If the entire anatomic model is embedded in a high resolution solid lattice, the element count becomes so high that simulator performance is very slow, even on a high performance workstation.  
 
 This paper introduces a simulator in which the model is initially presented at a low, but acceptable physics resolution.  As the surgeon operates on the model, only the areas impacted are recut at very high resolution.  This surgical subvolume is then merged back into the rest of the model.  The dramatic reduction in finite element count results in a surgical simulation program that is quite fast, even on a modest personal computer.  This paper presents examples of this simulator used in a variety of facial flap and cleft lip reconstructions.  Future uses in plastic surgery for patient specific simulation, education, and illustration are discussed.  The simulator is available as free, open-source software.

<video controls width="100%" >
  <source src="/video/PRS2.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>