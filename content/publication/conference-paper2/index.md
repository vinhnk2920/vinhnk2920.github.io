---
title: 'UETCorn at MEDIQA-Sum 2023: Template-based Summarization for Clinical Note Generation from Doctor-Patient Conversation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Duy-Cat Can
  - Quoc-An Nguyen
  - Binh-Nguyen Nguyen
  - Minh-Quang Nguyen
  - admin
  - Trung-Hieu Do
  - Hoang-Quynh Le

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-09-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-18T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Conference and Labs of the Evaluation Forum*
publication_short: In *CLEF (Working Notes)*

abstract: Clinical note summarization is a challenging task that aims to extract the most relevant information from unstructured text documents and present it concisely and coherently. Large language models, such as OpenAI’s GPT-3.5, have limitations in terms of trustworthiness and cost-effectiveness for generating complete clinical notes from patient-doctor dialogues. In this paper, we propose a novel template-based approach of for clinical note summarization from dialogue. Our model is under the control of a specific template, which is constructed by our own team and relies on expert validation. The semantic-based partition module fills in the template with key facts extracted from the dialogue using a combination of rule-based and neural methods. The template-based summarization module fine-tunes state-of-the-art (SOTA) BART models and other strategies to generate fluent and informative summaries corresponding to parts in the template. We evaluated our approach on released datasets of MEDIQA-Sum 2023 Shared Tasks, which contain clinical notes from dialogue for various problems. Our approach achieves the best ROUGE-2 and ROUGE-L scores for full note summarization, outperforming several strong baselines.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Template-based summarization
  - Generative Transformer
  - Semantic-based partition
  - Clinical Note Generation
  - Doctor-Patient Conversation

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ceur-ws.org/Vol-3497/paper-117.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}