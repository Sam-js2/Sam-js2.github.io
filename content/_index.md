---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background.png
          filters:
            brightness: 0.8
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My current research is all affiliated with SOUTH (the Student Operated Undergraduate Tokamak with rf Heating), where I designed the plasma diagnostics systems architecture. This was a unique challenge due to an extremely tight budget, but I found these restrictions encourages some creativity, and greatly enjoyed the chance to work on a fully clean sheet project.

        As a spin-off project, my undergraduate thesis work is on the use of a 2D array of Hall effect sensors to directly image the toroidal field of SOUTH. This device is anticipated to be a great help in the R&D and commissioning stages, and it will significantly de-risk the project.
        
        If you work for a University, National Lab or Fusion company and are interested in collaborating on making SOUTH happen, please either email me directly or [reach out to project through our website](atomcraft.com.au).
---
