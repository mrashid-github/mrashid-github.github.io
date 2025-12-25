---
title: "Gaussian Process Regression Surrogate Model for Seismic Vulnerability Assessment of Highway Bridge Structure System"
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Taisei Saida
- admin
- Mayuko Nishio


# Author notes (optional)
# author_notes:

date: "2023-08-01T00:00:00Z"
doi: "10.1007/978-3-031-39117-0_53"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-01T00:00:00Z"



abstract: |-  
  System fragility is required especially for the vulnerability assessment of existing bridges that configure transportation network as a structural system. Here, it is essential to consider not only variation of input ground motions but also the uncertainties in physical properties due to deteriorations or other aging effects. In that case, the derivation of system fragility requires the Monte Carlo calculation with high-dimensional input uncertain parameters. This study shows the deep kernel learning (DKL) surrogate modeling for the seismic system fragility analysis. Here, it has also been shown that the multilayer perceptron can be used in the DKL to compress high-dimensional uncertainties into low-dimensional features. In addition, a multi-output Gaussian process was used and correlations between multiple outputs were considered. The target structure for verification was a multi-span curved highway bridge with seismic isolation bearings with high nonlinearities. The input-output data were created by the earthquake response analysis using the FE model, and the DKL surrogate models for demand outputs for limit states evaluations were constructed with considering parameter uncertainties in the properties of bearings and piers. In the results, the system fragilities could be derived with appropriate accuracies at a low computational cost by the DKL surrogate model. In addition, the surrogate model can identify which components' limit states cause the bridge system's limit states.

  
# Summary. An optional shortened abstract.
summary: "EVACES, Milan, Italy, 2023"

tags: ["Surrogate Model", "Gaussian Process Regression", "Structural Reliability Analysis", "Bridge Fragility Functions"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://link.springer.com/chapter/10.1007/978-3-031-39117-0_53


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Experimental Vibration Analysis for Civil Engineering Structures, 2023*"
publication_short: "*EVACES 2023*"

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
