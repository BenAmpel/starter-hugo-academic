---
title: 'Identifying Vulnerable GitHub Repositories and Users in Scientific Cyberinfrastructure: An Unsupervised Graph Embedding Approach '

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ben Lazarine
  - Sagar Samtani
  - Mark Patton
  - Hongyi Zhu
  - Steven Ullman
  - admin
  - Hsinchun Chen

date: '2020-11-01T00:00:00Z'
doi: '10.1109/ISI49825.2020.9280544'

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

abstract: The scientific cyberinfrastructure community heavily relies on public internet-based systems (e.g., GitHub) to share resources and collaborate. GitHub is one of the most powerful and popular systems for open source collaboration that allows users to share and work on projects in a public space for accelerated development and deployment. Monitoring GitHub for exposed vulnerabilities can save financial cost and prevent misuse and attacks of cyberinfrastructure. Vulnerability scanners that can interface with GitHub directly can be leveraged to conduct such monitoring. This research aims to proactively identify vulnerable communities within scientific cyberinfrastructure. We use social network analysis to construct graphs representing the relationships amongst users and repositories. We leverage prevailing unsupervised graph embedding algorithms to generate graph embeddings that capture the network attributes and nodal features of our repository and user graphs. This enables the clustering of public cyberinfrastructure repositories and users that have similar network attributes and vulnerabilities. Results of this research find that major scientific cyberinfrastructures have vulnerabilities pertaining to secret leakage and insecure coding practices for high-impact genomics research. These results can help organizations address their vulnerable repositories and users in a targeted manner.
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

url_pdf: 'https://par.nsf.gov/servlets/purl/10258093'
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