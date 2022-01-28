---
# An instance of the Blank widget with a Gallery page element.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Photography
subtitle:

design:
  columns: '1'
#  Options are `cover` (default), `contain`, or `actual` size.  
# image_size: contain
# Options include `left`, `center` (default), or `right`.
#  image_position: center 

filter_button:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
      
{{< gallery album="photography" >}}
  
---

