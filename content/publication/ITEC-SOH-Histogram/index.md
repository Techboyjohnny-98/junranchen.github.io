---
title: 'Lithium-ion Battery State-of-Health Estimation via Histogram Data, Principal Component Analysis, and Machine Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Phillip Kollmeyer
  - Fei Chiang
  - Ali Emadi

# Author notes (optional)
author_notes:
  # - 'Equal contribution'

date: '2023-07-25'
doi: 'https://doi.org/10.1109/ITEC55900.2023.10187012'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']
# paper-conference

# Publication name and optional abbreviated publication name.
publication: IIEEE Transportation Electrification Conference & Expo
publication_short: ITEC

abstract: Lithium-ion batteries are widely used in electric vehicle powertrain systems. As batteries age, their state of health (SOH), indicated by their usable capacity and power capability, decreases. For reliable battery operation, accurate estimation and prediction of SOH are essential. This paper proposes an algorithm for estimating battery capacity SOH from an open-source fast charging dataset with many different charge profile types. Histogram data is created from the measured time domain data and fed into a feedforward neural network (FNN). To capture the impact of different charge profiles on aging, current and state of charge (SOC) are multiplied together to create an additional synthetic input to the estimator. To reduce the number of inputs to the FNN to only those that contain valuable information, we use principal component analysis to reduce the total number of inputs by 80%. An SOH algorithm is proposed that can estimate capacity throughout the battery’s life with a 1.03% root mean square percentage error (RMSPE) and 0.68% mean absolute percentage error (MAPE).

# Summary. An optional shortened abstract.
summary: 

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
  caption: 'Workflow of the proposed multi-modal knowledge fusion based SOH estimation method.'
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
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
