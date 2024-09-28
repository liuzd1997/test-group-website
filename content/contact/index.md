---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: 
      email: test@example.org
      phone: 888 888 88 88
      address:
        street: 3900 E Stevens Way NE
        city: Seattle
        region: WA
        postcode: '98195'
        country: United States
        country_code: US
      coordinates:
        latitude: '47.6536'
        longitude: '-122.3048'
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      #appointment_url: 'https://calendly.com'
      contact_links:
        - icon: browser
          icon_pack: fas
          name: Department Profile
          link: 'https://www.me.washington.edu/facultyfinder/xu-chen'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
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
