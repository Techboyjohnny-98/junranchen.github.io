---
title: 'Thermal fault detection of lithium-ion battery packs through an integrated physics and deep neural network based model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mina Naguib
  - admin
  - Phillip Kollmeyer
  - Ali Emadi

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2025-04-28'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: Communications Engineering
publication_short: CE

abstract: Battery packs develop faults over time, many ofwhich are difficult to detect early. For instance, cooling system blockages raises temperatures but may not trigger alerts until protection limits are exceeded. This work presents amodel-based method for early thermal fault detection and identification in battery packs. By comparing measured and estimated temperatures, the method identifies faults including failed sensors, coolant pump malfunctions, and flow blockages. The core is a high-accuracy temperature estimation model, integrating a physics-based thermal model with a neural network, achieves a root mean square error of 0.39 °Cand a maximumerror of 1 °Cunder a US06 discharge and 6C charge at 15 °C. Tested on a 72-cell air-cooled pack, the method detects faults using only eight temperature sensors within 13 to 45 minutes, with zero false detections in 11 testing cycles. This approach enables early fault alerts, enhancing reliability and safety in electric vehicles.

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
url_dataset: 'https://borealisdata.ca/dataset.xhtml?persistentId=doi:10.5683/SP3/THZTJC'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overview of the proposed fault detection and identification method.'
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
