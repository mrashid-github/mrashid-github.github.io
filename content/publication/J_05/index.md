---
title: "CNN-based segmentation frameworks for structural component and earthquake damage determinations using UAV images"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Taisei Saida
- admin
- Yudai Nemoto
- Shota Tsukamoto
- Takehiko Asai 
- Mayuko Nishio

# Author notes (optional)
# author_notes:

date: "2023-04-01T00:00:00Z"
doi: "10.1007/s11803-023-2174-z"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-01T00:00:00Z"



abstract: |-
  Buildings undergo various kinds of structural damage during earthquakes, and damage detection and functional assessment of these structures in the aftermath of the events have been challenging issues. Under these circumstances, computer vision techniques offer a promising solution by automating the inspection process. This study presents an effective methodology for automatic structural components and damage detection using unmanned aerial vehicle (UAV) images of damaged buildings. Two types of neural network architectures are considered for appropriate feature extractions in different task detections. The feature pyramid network (FPN) is employed for crack, spall, rebar, and component damage segmentation, while the UNet++ network is utilized for the damage state. For network training and validation, a total of 3805 original images of size 1920×1080 pixels are processed by the proposed method and reduced the image pixels. From the FPN, the achieved highest intersection over unions (IoUs) were 0.59, 0.93, 0.42, and 0.99 for crack, spall, rebar, and components, respectively. These predicted labels were found in close agreement with the labels. Similarly, the UNet++ recognized the semantic information and damage state with an IoU of 0.72. This demonstrated the applicability of the proposed method for automated post-earthquake building inspection process accurately without information loss from the original images.

# Summary. An optional shortened abstract.
summary: "Earthquake Engineering and Engineering Vibration, 2023"

tags: ["Mainshock-aftershock", "Bridges", "Hysteretic", "Damping", "Seismic energy", "Aftershock fragility"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://link.springer.com/article/10.1007/s11803-023-2174-z


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Earthquake Engineering and Engineering Vibration*"
publication_short: "*Earthq. Eng. Eng. Vib.*"

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
