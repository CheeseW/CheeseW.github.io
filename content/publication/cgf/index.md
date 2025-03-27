---
title: 'Optimized Processing of Localized Collisions in Projective Dynamics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yutian Tao
  - Court Cutting
  - Eric Brandt
  - Eftychios Sifakis

# Author notes (optional)
author_notes:
  - University of Wisconsin - Madison
  - University of Wisconsin - Madison
  - New York University Medical Center
  - University of Wisconsin - Madison
  - University of Wisconsin - Madison

date: '2021-07-21T00:00:00Z'
doi: '10.1111/cgf.14385'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Computer Graphics Forum*
publication_short: In *CGF*

# abstract: "We present a method for the efficient processing of contact and collision in volumetric elastic models simulated using the Projective Dynamics paradigm. Our approach enables interactive simulation of tetrahedral meshes with more than half a million elements, provided that the model satisfies two fundamental properties: the region of the model's surface that is susceptible to collision events needs to be known in advance, and the simulation degrees of freedom associated with that surface region should be limited to a small fraction (e.g. 5%) of the total simulation nodes. In such scenarios, a partial Cholesky factorization can abstract away the behaviour of the collision-safe subset of the face model into the Schur Complement matrix with respect to the collision-prone region. We demonstrate how fast and accurate updates of bilateral penalty-based collision terms can be incorporated into this representation, and solved with high efficiency on the GPU. We also demonstrate iterating a partial update of the element rotations, akin to a selective application of the local step, specifically on the smaller collision-prone region without explicitly paying the cost associated with the rest of the simulation mesh. We demonstrate efficient and robust interactive simulation in detailed models from animation and medical applications."

# Summary. An optional shortened abstract.
summary: We present a method for the efficient processing of contact and collision in volumetric elastic models simulated using the Projective Dynamics paradigm. Our approach enables interactive sim…

tags:
  - Physical Simulation

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

We present a method for the efficient processing of contact and collision in volumetric elastic models simulated using the Projective Dynamics paradigm. Our approach enables interactive simulation of tetrahedral meshes with more than half a million elements, provided that the model satisfies two fundamental properties: the region of the model's surface that is susceptible to collision events needs to be known in advance, and the simulation degrees of freedom associated with that surface region should be limited to a small fraction (e.g. 5%) of the total simulation nodes. In such scenarios, a partial Cholesky factorization can abstract away the behaviour of the collision-safe subset of the face model into the Schur Complement matrix with respect to the collision-prone region. 

We demonstrate how fast and accurate updates of bilateral penalty-based collision terms can be incorporated into this representation, and solved with high efficiency on the GPU. We also demonstrate iterating a partial update of the element rotations, akin to a selective application of the local step, specifically on the smaller collision-prone region without explicitly paying the cost associated with the rest of the simulation mesh. We demonstrate efficient and robust interactive simulation in detailed models from animation and medical applications.

<video controls width="100%" poster="/video/CGF1.png">
  <source src="/video/CGF1.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video controls width="100%" poster="/video/CGF2.png">
  <source src="/video/CGF2.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>