---
title: 'Identifying and Categorizing Malicious Content on Paste Sites: A Neural Topic Modeling Approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tala Vahedi
  - admin
  - Sagar Samtani
  - Hsinchun Chen

date: '2021-11-01T00:00:00Z'
doi: '10.1109/ISI53945.2021.9624765'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2021 IEEE International Conference on Intelligence and Security Informatics (ISI)*
publication_short: In *IEEE ISI*

abstract: Malicious cyber activities impose substantial costs on the U.S. economy and global markets. Cyber-criminals often use information-sharing social media platforms such as paste sites (e.g., Pastebin) to share vast amounts of plain text content related to Personally Identifiable Information (PII), credit card numbers, exploit code, malware, and other sensitive content. Paste sites can provide targeted Cyber Threat Intelligence (CTI) about potential threats and prior breaches. In this research, we propose a novel Bidirectional Encoder Representation from Transformers (BERT) with Latent Dirichlet Allocation (LDA) model to categorize pastes automatically. Our proposed BERT-LDA model leverages a neural network transformer architecture to capture sequential dependencies when representing each sentence in a paste. BERT-LDA replaces the Bag-of-Words (BoW) approach in the conventional LDA with a Bag-of-Labels (BoL) that encompasses class labels at the sequence level. We compared the performance of the proposed BERT-LDA against the conventional LDA and BERT-LDA variants (e.g., GPT2-LDA) on 4,254,453 pastes from three paste sites. Experiment results indicate that the proposed BERT-LDA outperformed the standard LDA and each BERT-LDA variant in terms of perplexity on each paste site. Results of our BERT-LDA case study suggest that significant content relating to hacker community activities, malicious code, network and website vulnerabilities, and PII are shared on paste sites. The insights provided by this study could be used by organizations to proactively mitigate potential damage on their infrastructure.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Hacker Forums
- Cyber Threat Intelligence
- Deep Learning
- Transformers / LLMs
- Exploit Labeling
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://par.nsf.gov/servlets/purl/10336827'
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_video: 'https://youtube.com'

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---