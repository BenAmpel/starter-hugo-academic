---
title: 'Smart Vulnerability Assessment for Scientific Cyberinfrastructure: An Unsupervised Graph Embedding Approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Steven Ullman
  - Sagar Samtani
  - Ben Lazarine
  - Hongyi Zhu
  - admin
  - Mark Patton
  - Hsinchun Chen

date: '2020-11-01T00:00:00Z'
doi: '10.1109/ISI49825.2020.9280545'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2020 IEEE International Conference on Intelligence and Security Informatics (ISI)*
publication_short: In *IEEE ISI*

abstract: The accelerated growth of computing technologies has provided interdisciplinary teams a platform for producing innovative research at an unprecedented speed. Advanced scientific cyberinfrastructures, in particular, provide data storage, applications, software, and other resources to facilitate the development of critical scientific discoveries. Users of these environments often rely on custom developed virtual machine (VM) images that are comprised of a diverse array of open source applications. These can include vulnerabilities undetectable by conventional vulnerability scanners. This research aims to identify the installed applications, their vulnerabilities, and how they vary across images in scientific cyberinfrastructure. We propose a novel unsupervised graph embedding framework that captures relationships between applications, as well as vulnerabilities identified on corresponding GitHub repositories. This embedding is used to cluster images with similar applications and vulnerabilities. We evaluate cluster quality using Silhouette, Calinski-Harabasz, and Davies-Bouldin indices, and application vulnerabilities through inspection of selected clusters. Results reveal that images pertaining to genomics research in our research testbed are at greater risk of high-severity shell spawning and data validation vulnerabilities.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Vulnerability Scanning
- Deep Learning
- Graph Embedding
- GitHub
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://par.nsf.gov/servlets/purl/10258092'
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