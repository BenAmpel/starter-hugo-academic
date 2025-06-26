---
# Leave title blank if you prefer the site title in <title> tag
title: "Benjamin Ampel"
date: 2022-10-24
type: landing         # tells Wowchemy this is a landing page bundle

# ↓  The homepage is now configured with a single `blocks:` array
blocks:

  - block: about          # Biography/portrait section
    id: about
    biography: true
    # Adding the param *outside* `content:` stops the .courses panic
    courses: []           # ← leave empty or populate with course objects
    content:
      title: Biography             # Heading shown on the page
      username: admin              # Folder name in `content/authors/`

  - block: tag_cloud      # Research Interests tag cloud
    id: research_interests
    content:
      title: Research Interests
    design:
      columns: 1          # numbers, not quoted strings

  - block: collection     # Journal articles
    id: journal_publications
    content:
      title: Journal Publications
      filters:
        folders: [journal_publication]
        exclude_featured: false
    design:
      columns: 2
      view: citation

  - block: collection     # Conference proceedings
    id: conference_publications
    content:
      title: Refereed Conference Proceedings
      filters:
        folders: [conference_publication]
        exclude_featured: false
    design:
      columns: 2
      view: citation
---
