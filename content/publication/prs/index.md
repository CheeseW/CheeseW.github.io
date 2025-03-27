---
title: "Long-Term Results of the Murawski Unilateral Cleft Lip Repair"
authors:
- Eugeniusz Murawski 
- Elzbieta H. Gawrych 
- Court Cutting
- Eftychios Sifakis
- admin
- Yutian Tao



- admin
author_notes:
- Pomeranian Medical University 
- Pomeranian Medical University 
- New York University Medical Center
- University of Wisconsin-Madison
- University of Wisconsin-Madison
- University of Wisconsin-Madison

date: "2022-02-07T00:00:00Z"
doi: "10.1097/PRS.0000000000008788"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *Plastic and Reconstructive Surgery 149(2)*
publication_short: In *PRS*

# abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# Summary. An optional shortened abstract.
summary: "Background: In 1968, Ralph Millard published his “Millard II” method for repair of wide, complete unilateral cleft lip and nose deformity. In 1979, Murawski published a major modification …"

tags:
- Virtual Surgery Simulator
- Physics Simulation

featured: true

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://journals.lww.com/plasreconsurg/Fulltext/2022/02000/Long_Term_Results_of_the_Murawski_Unilateral_Cleft.29.aspx
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
#### Background: 

In 1968, Ralph Millard published his “Millard II” method for repair of wide, complete unilateral cleft lip and nose deformity. In 1979, Murawski published a major modification of the Millard II procedure in Polish. This motif was taken up 8 years later by Mohler and 22 years later by Cutting. The Murawski variation on the Millard II procedure has become a dominant motif in unilateral cleft lip repair worldwide. This brief report intends to introduce the method to the English language literature and present long-term results.

#### Methods: 

The Murawski method alters the Millard II procedure by changing the upper medial curve into a point in the columellar base. This creates a broad C flap used to fill the entire defect produced by downward rotation of the medial lip. Millard’s lateral advancement flap becomes unnecessary. A lateral approach to primary nasal reconstruction allows the lateral C flap to be used to construct the nasal floor and sill. The method is described using a physics-based surgical simulator.

#### Results: 

Long-term results of the method are demonstrated with four patients with 15 to 25-year follow-up. None of these patients had any revisions to the lip or nose.

#### Conclusions: 

The Murawski repair was the first to modify the Millard II repair by sharpening the medial columellar incision, eliminating the need for a lateral advancement flap. This motif was put forth in the years to follow by Mohler and Cutting. Long-term results of the method are presented.Humans and animals can control their bodies to generate a wide range of motions via low-dimensional action signals representing high-level goals. As such, human bodies and faces are prime examples of active objects, which can affect their shape via an internal actuation mechanism. This paper explores the following proposition: given a training set of example poses of an active deformable object, can we learn a low-dimensional control space that could reproduce the training set and generalize to new poses? In contrast to popular machine learning methods for dimensionality reduction such as auto-encoders, we model our active objects in a physics-based way. We utilize a differentiable, quasistatic, physics-based simulation layer and combine it with a decoder-type neural network. Our differentiable physics layer naturally fits into deep learning frameworks and allows the decoder network to learn actuations that reach the desired poses after physics-based simulation. In contrast to modeling approaches where users build anatomical models from first principles, medical literature or medical imaging, we do not presume knowledge of the underlying musculature, but learn the structure and control of the actuation mechanism directly from the input data. We present a training paradigm and several scalability-oriented enhancements that allow us to train effectively while accommodating high-resolution volumetric models, with as many as a quarter million simulation elements. The prime demonstration of the efficacy of our example-driven modeling framework targets facial animation, where we train on a collection of input expressions while generalizing to unseen poses, drive detailed facial animation from sparse motion capture input, and facilitate expression sculpting via direct manipulation.