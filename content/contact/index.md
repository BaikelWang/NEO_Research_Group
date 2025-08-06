---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        需要联系我们，请留言！
      email: iamlgao@njupt.edu.cn
      phone: # 888 888 88 88
      address:
        street: 栖霞区文苑路9号
        city: 南京市
        region: 江苏省
        postcode: '94305'
        country: 中国
        country_code: zh
      coordinates:
        latitude: '32.1211'  
        longitude: '118.9283'
      directions: 材料学科楼203
      office_hours:
        - '工作日 9:00 到 18:00'
        - '非工作日 10:00 到 14:00'
      appointment_url: # https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: True
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
