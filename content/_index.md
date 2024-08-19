# Leave homepage title empty to use cite title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: /uploads/CV_Heather_Bone.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: 17.svg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: <div style="text-align: center;">Research Overview</div>

      subtitle: ''
      text: |-
         My research focuses on the economics of crime, with a particular focus on illicit drug markets. I am particularly interested in how criminalization and enforcement effects the decisions of criminal actors and the resulting consequences for security and public health. 
         
         Doing so is challenging because of the industry's illicit nature: Criminal enterprises are not tracked in administrative data and often wish to keep their actions hidden, fearing prosecution.  In the spirit of forensic economics, my work leverages big data, machine learning, and geographic information systems to observe the actions of these organizations. 
  
    design:
      columns: '1'

