---
title: 'Sequence Training and Data Shuffling to Enhance the Accuracy of Recurrent Neural Network Based Battery Voltage Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Phillip Kollmeyer
  - Satyam Panchal
  - Yasaman Masoudi
  - Oliver Gross
  - Ali Emadi

# Author notes (optional)
author_notes:
  # - 'Equal contribution'

date: '2024-02-05'
doi: 'https://doi.org/10.4271/2024-01-2426'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']
# paper-conference

# Publication name and optional abbreviated publication name.
publication: SAE Technical Paper
publication_short: SAE

abstract: Battery terminal voltage modelling is crucial for various applications, including electric vehicles, renewable energy systems, and portable electronics. Terminal voltage models are used to determine how a battery will respond under load and can be used to calculate run-time, power capability, and heat generation and as a component of state estimation approaches, such as for state of charge. Previous studies have shown better voltage modelling accuracy for long short-term memory (LSTM) recurrent neural networks than other traditional methods (e.g., equivalent circuit and electrochemical models). This study presents two new approaches – sequence training and data shuffling – to improve LSTM battery voltage models further, making them an even better candidate for the high-accuracy modelling of lithium-ion batteries. Because the LSTM memory captures information from past time steps, it must typically be trained using one series of continuous data. Instead, the proposed sequence training approach feeds a fixed window of prior data (e.g., 100 seconds) into the LSTM at each time step to initialize the memory states properly and then only uses the output at the current time step. With this method, the LSTM just requires the prior data window to be continuous, thereby allowing the handling of discontinuities. This also means that during the training process, the data can be shuffled randomly, enabling mini-batches to speed up the training significantly. When these approaches were applied, LSTM voltage estimation error was reduced by 22%, from 28.5 mV to 22.3 mV RMS error over four drive cycles and temperatures from -20 to 25°C.

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
