---
title: "Learning active quasistatic physics-based models from data"
authors:
- Sangeetha Grama Srinivasan
- admin
- Junior Rojas
- Gergely Klár
- Ladislav Kavan
- Eftychios Sifakis


author_notes:
- University of Wisconsin-Madison
- University of Wisconsin-Madison
- University of Utah
- Weta Digital
- University of Utah
- University of Wisconsin-Madison

date: "2021-07-19T00:00:00Z"
doi: "10.1145/3450626.3459883"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Graphics (TOG), Volume 40, Issue 4*
publication_short: In *TOG*

# abstract: |2
  


# Summary. An optional shortened abstract.
summary: Humans and animals can control their bodies to generate a wide range of motions via low-dimensional action signals representing high-level goals. As such, human bodies and faces …

tags:
- Physical Simulation
- Differentiable Simulator
- Machine Learning
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
Humans and animals can control their bodies to generate a wide range of motions via low-dimensional action signals representing high-level goals. As such, human bodies and faces are prime examples of active objects, which can affect their shape via an internal actuation mechanism. This paper explores the following proposition: given a training set of example poses of an active deformable object, can we learn a low-dimensional control space that could reproduce the training set and generalize to new poses? 
  
In contrast to popular machine learning methods for dimensionality reduction such as auto-encoders, we model our active objects in a physics-based way. We utilize a differentiable, quasistatic, physics-based simulation layer and combine it with a decoder-type neural network. Our differentiable physics layer naturally fits into deep learning frameworks and allows the decoder network to learn actuations that reach the desired poses after physics-based simulation. In contrast to modeling approaches where users build anatomical models from first principles, medical literature or medical imaging, we do not presume knowledge of the underlying musculature, but learn the structure and control of the actuation mechanism directly from the input data. 
  
We present a training paradigm and several scalability-oriented enhancements that allow us to train effectively while accommodating high-resolution volumetric models, with as many as a quarter million simulation elements. The prime demonstration of the efficacy of our example-driven modeling framework targets facial animation, where we train on a collection of input expressions while generalizing to unseen poses, drive detailed facial animation from sparse motion capture input, and facilitate expression sculpting via direct manipulation.

<video controls width="100%" poster="/video/SIG1.png">
  <source src="/video/SIG1.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video controls width="100%" poster="/video/SIG2.png">
  <source src="/video/SIG2.m4v" type="video/mp4">
  Your browser does not support the video tag.
</video>