---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        <span style="font-weight:800;color:#005baa">C</span><span style="font-size:0.8em">omputer</span><br>
        <span style="font-weight:800;color:#005baa">A</span><span style="font-size:0.8em">nd</span><br>
        <span style="font-weight:800;color:#005baa">M</span><span style="font-size:0.8em">achine</span><br>
        <span style="font-weight:800;color:#005baa">E</span><span style="font-size:0.8em">ngaged</span><br>
        <span style="font-weight:800;color:#005baa">L</span><span style="font-size:0.8em">ab</span>
      image:
        filename: canine/canine1.png
      text: |
        <br>
        
        The **Computer and Machine Engaged Lab** has been a center of excellence for Physical Artificial Intelligence research, teaching, and practice since its founding in 2020.

  - block: slider
    content:
      slides:
        - title: "Welcome to the Lab"
          content: "3D Vision · Robotics · AI"
          align: center
          background:
            image:
              # 이미지 파일은 assets/media/ 에 두고 파일명만 적습니다.
              filename: canine/canine2.jpg
              # 필요 시 밝기/포지션 조절
              filters:
                brightness: 0.7
            position: center
        - title: "Research Highlights"
          content: "Locomotion / Perception / Reinforcement Learning"
          align: center
          background:
            image:
              filename: canine/canine3.png
              filters:
                brightness: 0.6
            position: right
          link:
            text: "See Publications"
            url: "/publication/"
        - title: ""
          align: center
          background:
            image:
              filename: lab_images/image22.png
            position: center
        
    design:
      is_fullscreen: false
      slide_height: '80vh'
      slide_width: '80vh'
      interval: 5000
      loop: true
      css_style: "max-width: 1080px; margin-inline: auto;"
      # spacing:
      #   padding: ['40px', '0', '40px', '0']
      
  - block: markdown
    id: section-1
    content:
      title: Section 1
      subtitle: A subtitle
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
