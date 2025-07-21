---
title: 'A Convolutional Neural Network for Estimation of Lithium-Ion Battery State-of-Health during Constant Current Operation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Manjula Manivanan
  - Josimar Duque
  - Phillip Kollmeyer
  - Satyam Panchal
  - Oliver Gross
  - Ali Emadi

# Author notes (optional)
author_notes:
  # - 'Equal contribution'

date: '2023-07-25'
doi: 'https://doi.org/10.1109/ITEC55900.2023.10186914'

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

abstract: Accurate state-of-health (SOH) estimation is critical for lithium-ion batteries’ safe and reliable operation. These batteries are widely used for commercial products, including smartphones, laptops, and electric vehicles. In this paper, we develop a convolutional neural network (CNN) based battery SOH estimation model trained to estimate SOH from constant current charge and discharge data. Aging data from four cells, each charged with a different fifteen-minute fast-charging current profile, is used to train and test the SOH estimation model. The model’s accuracy is demonstrated by training with data from one fast-charging aging case and tested using the other three cases, which age at a considerably different rate. The results show that the method is quite robust when the tested cells have more than 80% SOH, with error typically within ±2% and not exceeding ±3%. However, the proposed method has limitations when trying to predict battery health below 80% or when trying to predict battery health from curves with different C-rates. The datasets and the code for the algorithm in this paper are available to download.

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
url_code: 'https://borealisdata.ca/dataset.xhtml?persistentId=doi:10.5683/SP3/6AGUAW'
url_dataset: 'https://borealisdata.ca/dataset.xhtml?persistentId=doi:10.5683/SP3/UYPYDJ'
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
