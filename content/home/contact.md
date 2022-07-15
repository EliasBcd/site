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
  email: elias.bouacida@univ-paris8.fr
  phone: 
  address:
    street: 2 avenue de la Liberté
    city: Saint-Denis
    region: Seine Saint-Denis
    postcode: '93526'
    country: France
    country_code: FR
  coordinates:
    latitude: '48.9467'
    longitude: '2.3611'
  directions: Enter Building D and take the stairs to Office 115 on Floor 1
  office_hours:
    - 'TBA'
  contact_links:
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://univ-paris8.zoom.us/my/eliasbouacida'

design:
  columns: '2'
---
