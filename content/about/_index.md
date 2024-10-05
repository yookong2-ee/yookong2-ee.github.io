---
# Leave the homepage title empty to use the site title
title: Jangyubin's World
date: 2024-10-5
type: landing

sections:
  - block: features
    content:
      title: <span style="font-size:75%"> 🟡Welcome to the show!🟡</span>
      text: <span style="font-size:110%"> 어서오십시오. 이곳은 당신이 상상한 대로 흘러가지 않는 세상입니다.🧙 </span>


  - block: slider
    content:
      slides:
      - title: AI
        content: 'Just opened last month!'
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
      - title: Medical AI
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Development
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: center
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Mathematics
        content: 'Just opened last month!'
        align: center
        background:
          image:
            filename: welcome.jpg
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

  

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">나의 소개</span>
      text: 안녕하세요.                                                                       저는 전북대학교 컴퓨터인공지능학부 2학년에 재학 중인 장유빈이라고 합니다.                    저는 2004년 6월 26일 생이고 원숭이 띠입니다.                                              저의 멋진 사이트에 방문해 주셔서 감사드립니다.                                               저에 대해 더 자세한 정보를 원하신다면                                                       ✆ 010.3878.2673으로 전화주세요.<br><br><br><br>


  - block: collection
    content:
      title: Notifications & News
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
      title: Latest Publications
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