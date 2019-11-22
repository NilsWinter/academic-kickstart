---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Poster Presentation DGPPN 2019"
event: Meeting of the Deutsche Gesellschaft für Psychiatrie und Psychotherapie, Psychosomatik und Nervenheilkunde
event_url: https://www.dgppnkongress.de/
location: Berlin
address:
  street: Messedamm 26
  city: Berlin
  region:
  postcode: 14055
  country: Germany
summary: 
    Poster presentation on the latest results of my Regional Brain Age model and associated changes in patients with 
    Major Depressive Disorder
abstract: 
    Introduction. Deviation between chronological age and brain-based age prediction has frequently been used as an indicator of disease 
    risk and severity in psychiatric and neurological disorders. Here, in a sample of patients with major depressive 
    disorder, we aim to understand to what extent the severity of depressive symptoms is associated with a deviation from 
    the trajectory of normal brain aging. We employ an approach to normative brain age modelling which uses machine learning 
    models to predict chronological age from structural neuroimaging data in healthy individuals. Using these normative 
    models on a sample of depressive patients, we infer the degree of acceleration in brain aging and associate this 
    deviation with the severity of depressive symptoms.
    Methods. We trained regional whole-brain machine-learning models on N = 1,753 healthy adults (17-66 years) to predict 
    chronological age based on structural neuroimaging data using the Harvard Oxford atlas. We then computed individual 
    brain predicted age differences (brain-PAD) for every ROI in an independent sample of depressive patients 
    (N = 513, 18-65 years). Beck’s Depression Inventory (BDI) was used to measure symptom severity in these subjects (3). 
    The region-specific impact of BDI on brain-PAD was estimated using a multi-level Bayesian modelling approach.
    Results. The brain age model predicted chronological age in the healthy reference sample with high accuracy 
    (cross-validated mean absolute error = 4.07 years; Pearson’s r = .93). The Bayesian multi-level model revealed a 
    substantial positive relationship between BDI scores and brain-PAD (slope b = 0.40, CI(95%) = 0.02, 0.78) in 31 of 
    the 69 Harvard Oxford regions.
    Conclusions. These findings suggest a substantial association between depressive symptom severity and accelerated 
    brain aging in multiple regions of the brain. Future studies might address the question whether accelerated brain 
    aging is stable across time.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2019-11-29T13:30:00+01:00
date_end: 2019-11-29T15:00:00+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2019-11-17T22:32:11+01:00

authors: [admin]
tags: [DGPPN, BrainAge]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "methods"
  focal_point: ""
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: 

url_code:
url_pdf: talk/dgppn2019/Poster_Nils_Winter_Brain_Age_DGPPN2019.pdf
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [BrainAge]
---
