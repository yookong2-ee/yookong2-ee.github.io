---
# Leave the homepage title empty to use the site title
title: Jangyubin's World
date: 2024-10-5
type: landing

sections:
  - block: features
    content:
      title: <span style="font-size:75%">장유빈</span>
      text: <span style="font-size:110%">전북대학교 공과대학 컴퓨터인공지능학부</span>


  - block: slider
    content:
      slides:
      - title: 힐링
        content: 은 유튜브 보면서 맛있는 거 먹기가 최고.
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
      - title: 귀여운 거 좋아해요?
        content: ㄴ네
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: 주고 공부하는 분야는?
        content: 컴퓨터.입니다.
        align: center
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 최근 관심사?
        content: 날씨요. 더운데 추워. 추운데 더워.
        align: center
        background:
          image:
            filename: recruitment.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '50%'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
  

  - block: collection
    content:
      title: 너에 대해 알려줘
      subtitle:
      text:
      count: 2
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
      view: compact
      columns: '2'

  - block: collection
    content:
      title: 더더
      subtitle:
      text:
      count: 4
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: citation
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="click me! →" %}}
    design:
      columns: '1'
---