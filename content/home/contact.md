---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: cdswjct@gmail.com
  phone: 888 888 88 88
  address:
    street: Beijing District
    city: Beijing
    postcode: '100000'
    country: China
    country_code: CN
  coordinates:
    latitude: '0.0'
    longitude: '0.0'
  directions: 0
  office_hours:
    - 'Monday - Friday 8:00 to 18:00'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
