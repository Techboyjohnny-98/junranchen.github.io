---
title: 'Battery state-of-health estimation using CNNs with transfer learning and multi-modal fusion of partial voltage profiles and histogram data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Phillip Kollmeyer
  - Ryan Ahmed
  - Ali Emadi

# Author notes (optional)
author_notes:
  # - 'Equal contribution'

date: '2025-04-09'
doi: 'https://doi.org/10.1016/j.apenergy.2025.125923'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']
# paper-conference

# Publication name and optional abbreviated publication name.
publication: Applied Energy
publication_short: APEN

abstract: Accurate estimation of battery state of health (SOH) is critical for ensuring safe and reliable operation, enabling health-conscious control, and supporting second-life applications. Existing health indicators (HIs) used in data-driven models have practicality, accuracy, and robustness limitations. For instance, partial voltage or incremental capacity curves may lead to misleading SOH estimations, while histogram-based methods require extensive training data. This paper proposes a multi-modal fusion model that integrates two types of HIs extracted from partial voltage curves recorded during charging and histogram data during operation. By addressing the limitations of both types of HIs, the proposed model achieves superior performance in terms of accuracy and robustness. The proposed model is validated on two representative datasets, achieving a root mean squared percentage error (RMSPE) as low as 0.74 %, reducing estimation error by up to 42 % compared to existing models and requiring 60 % less training data. The results demonstrate the feasibility and advantages of combining HIs from different sources, underscoring the importance of detailed feature analysis in developing data-driven models for battery state estimation.

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
