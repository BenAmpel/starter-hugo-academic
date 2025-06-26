---
# Leave the homepage title empty to use the site title
title: Benjamin Ampel
date: 2022-10-24
type: landing

sections:
  - block: biography
    id: about
    
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      courses:[]

  - block: tag_cloud
    id: research_interests
    content:
      title: Research Interests
    design:
      columns: '1'
  
  - block: collection
    id: journal_publications
    content:
      title: Journal Publications
      filters:
        folders:
          - journal_publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

    
  - block: collection
    content:
      title: Refereed Conference Proceedings
      filters:
        folders:
          - conference_publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
---
