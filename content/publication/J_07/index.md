---
title: "System fragility analysis of highway bridge using multi-output Gaussian process regression surrogate model"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Taisei Saida
- admin
- Mayuko Nishio

# Author notes (optional)
# author_notes:

date: "2024-12-01T00:00:00Z"
doi: "10.1177/13694332241291255"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-01T00:00:00Z"



abstract: |-
  This study presents a multi-output Gaussian process regression (GPR) surrogate model for seismic-fragility analysis of bridge structural systems. Multi-output GPR can model the correlations among multiple outputs, accuracy and stability are achieved with fewer training data, which reduces the computational cost of fragility analysis. Furthermore, the explainability of the constructed surrogate model is implemented by adopting an automatic relevance-determination (ARD) kernel in the GPR. The estimated hyperparameters can provide the contribution of the uncertainty of each input parameter to the outputs. The fragility analysis using the multi-output GPR surrogate model was verified by applying it to a seismic isolation highway bridge with multiple spans and a curved geometry. The effectiveness of the multi-output GPR was demonstrated by the construction of an accurate and stable surrogate model with 46 inputs and 28 outputs. The relative contributions of the uncertainties to the structural properties and input earthquake loads could also be understood. The fragility curves, at both the component and system levels, were appropriately obtained using a sufficient number of samples in a Monte Carlo calculation. Furthermore, the failure modes were evaluated, identifying which structural components contributed to the system failure. This enabled discussions on structural system failures from the viewpoint of the structural dynamic characteristics of the bridge and earthquake-load properties.

# Summary. An optional shortened abstract.
summary: "Advances in Structural Engineering, 2024"

tags: ["surrogate model", "Gaussian process regression", "explainability", "Monte Carlo calculation", "structural-reliability analysis", "seismic fragility"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://link.springer.com/article/10.1007/s10518-025-02300-z


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Advances in Structural Engineering*"
publication_short: "*Adv. Civil Eng.*"

# add Almetric adn dimensions badges
add_badge: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---
